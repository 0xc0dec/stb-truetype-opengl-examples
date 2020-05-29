# About
Graphics demos made for learning and playing around with. The code is (hopefully) clean and self-documented,
all dependencies are included for easier building.

There are no complex abstractions aka "engine", but a small library of shared code is still used.
The goal is to keep things easy to understand while taking away as much boilerplate stuff as possible.

# Building and running
* `cd build`.
* `cmake -G "Visual Studio 16 2019" -A x64 ..` (or run a suitable build script from the folder, e.g. `gen-msvc-2017-x64.cmd`).
* Build using the generated IDE files.
* Run executables inside `build/<Debug|Release>/`.

# Controls
Some demos use first person camera. Use `W-S-A-D-Q-E` keys to move and hold right mouse button to rotate.

# Demos
## Transform
Object transform hierarchies and (first person) camera via reusable `Transform` and `Camera` classes.

![Image](/demos/transform/screenshot.png?raw=true)

## Skybox
Skybox rendering on a single quad mesh using a bit of shader magic.

![Image](/demos/skybox/screenshot.png?raw=true)

## TrueType
TrueType font rendering using [stb_truetype](https://github.com/nothings/stb) library.

![Image](/demos/stb-truetype/screenshot.png?raw=true)

## ImGui
Basic [ImGui](https://github.com/ocornut/imgui) integration example.

![Image](/demos/imgui/screenshot.png?raw=true)

## To be continued...

# Dependencies
* stb_truetype
* stb_image
* SDL
* GLEW
* glm
* ImGui
