# leanclr4unity_demo

This project is a demo project for [leanclr4unity](https://github.com/focus-creative-games/leanclr4unity).

## Overview

`leanclr4unity_demo` shows a minimal Unity integration example for `leanclr4unity`.  
The project is intentionally lightweight so you can quickly validate runtime behavior and platform builds.

## Demo Scene and Scripts

- Demo scene: `main`
- Included scripts:
  - `Hello`: prints logs in `Update`
  - `RotateCube`: rotates objects in the scene

## Key Project Structure

- `Assets/Scenes/main.unity`: demo scene
- `Assets/Hello.cs`: logging behavior
- `Assets/RotateCube.cs`: cube/object rotation behavior

## How to Run

1. Open this project with Unity.
2. Open `Assets/Scenes/main.unity` in the `Project` window.
3. Press `Play`:
   - Logs from `Hello` appear in the Console.
   - Scene objects rotate continuously via `RotateCube`.

## Build Instructions

- WebGL: `File -> Build Settings -> WebGL -> Build`
- Win64: `File -> Build Settings -> PC, Mac & Linux Standalone -> Target Platform: Windows -> Build`

## Platform Support

- Verified: `WebGL`, `Win64`
- Other platforms are expected to work as well, but have not been tested

## Related Link

- leanclr4unity: <https://github.com/focus-creative-games/leanclr4unity>
