# IndustrialRuins
This repository hosts the release version of the demo application "Industrial Ruins".

"Industrial Ruins" is a little program that was made by JXMaster in the Computer Graphic Course in my university. It simply draws a 2D scene with some Industrial Ruins and riverbank.

The whole program was written in C++, using Direct3D 11 as rendering backend.

You can download a copy of the program, and share with your friends freely.

## System Requirements
OS: Windows 7 and above. (Supporting DirectX 11.0)

Runtime: Visual C++ 2015 Redistributable.

There should not be any requirement for CPU and Graphics.

## Guidelines.
If you can't see the Debug Window, press '`' key, which is often the console key in most game engines.

The Debug window will present you with some parameters that you can twist to get the color you want.

If you are satisfied which the result, you can press "Save Current Preset to Config.jx" button to get a "Config.fx" file, you can then share this file with your friends, and they can reload your result by pressing "Load Preset from Config.jx" buttom.

Remember to put the "Config.jx" file in the same directory of the exe file, and do not change the filename(You can rename the file to save lots of copies, just remember to rename them back when you need to reload them:) ).

## Rendering Features.
* Full-scene HDR with tone-mapping and bloom.
* Simple Screen-space Reflection for water surface.
* Use Simplex Noise to generate water waves.
* Simple Post Process.

## Release Notes.
### V1.1
* Fixed the bug that keyboard input will keep going without delay(which makes it hard to input characters).
* Add support for using your own filename for saving/loading config files.

## Author Info.
JXMaster form School of Digital Media of Jiangnan University in Wuxi, Jiangsu Province, China.

Twitter: @JXMaster
