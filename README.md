# leanclr4unity_demo

本项目是 [leanclr4unity](https://github.com/focus-creative-games/leanclr4unity) 的示例项目。

## 项目简介

`leanclr4unity_demo` 用于演示如何在 Unity 中使用 `leanclr4unity`。  
示例尽量保持精简，便于快速验证运行流程与平台构建。

## 示例场景与脚本

- 示例场景：`main`
- 包含脚本：
  - `Hello`：在 `Update` 中打印日志
  - `RotateCube`：旋转场景中的对象

## 目录结构（关键部分）

- `Assets/Scenes/main.unity`：示例场景
- `Assets/Hello.cs`：日志输出逻辑
- `Assets/RotateCube.cs`：物体旋转逻辑

## 使用方式

1. 使用 Unity 打开本项目目录。
2. 在 `Project` 面板中打开 `Assets/Scenes/main.unity`。
3. 点击 `Play` 运行场景：
   - 在 Console 中可看到 `Hello` 脚本输出的日志；
   - 场景对象会按 `RotateCube` 逻辑持续旋转。

## 构建说明

- WebGL：`File -> Build Settings -> WebGL -> Build`
- Win64：`File -> Build Settings -> PC, Mac & Linux Standalone -> Target Platform: Windows -> Build`

## 平台支持

- 已验证支持：`WebGL`、`Win64`
- 其他平台理论上也可支持，但尚未测试

## 相关链接

- leanclr4unity: <https://github.com/focus-creative-games/leanclr4unity>
