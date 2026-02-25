# CS 330 Module Two (2-2 Assignment) — 3D Transformations (Hourglass Pyramids)

## Overview
This project is part of SNHU’s CS 330 (Computational Graphics and Visualization).  
The goal of Module Two’s 2-2 Assignment is to apply **3D transformations** to two 4-sided pyramids so they match the required visual result: an **hourglass shape** where the pyramid tips meet.

## What This Program Does
- Renders two 3D pyramid meshes in an OpenGL window.
- Applies transformation logic in `SceneManager::RenderScene()` to:
  - Position the pyramids vertically
  - Rotate one pyramid so it is inverted
  - Align both pyramid tips to meet in the center

## Key Concepts Demonstrated
- Model transformations (Scale, Rotate, Translate)
- Matrix ordering and transformation composition
- Scene rendering using OpenGL + GLM
- Working with preconfigured Visual Studio OpenGL projects

## Files Updated
- `SceneManager.cpp`
  - `SceneManager::RenderScene()` — modified transformation values for both pyramids to achieve the hourglass configuration.

## How to Build and Run
1. Open the `.sln` file in **Visual Studio 2022**
2. Set build configuration to **Debug** and platform to **x86** (or the project default)
3. Build and run:
   - **Build:** `Ctrl + Shift + B`
   - **Run:** `F5`

## Controls
- Close window normally (or press ESC if your template supports it)

## Screenshot / Result
Expected output:  
- A pyramid oriented upward
- A pyramid inverted above it
- Both tips meet to form an hourglass-like shape

## Author
Kevin Simmons  
CS 330 — SNHU
