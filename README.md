# Water Freezing Simulation
### A CS-580 course project

## Authors
Hanyuan Xiao, Xiaocheng Tang

## Prerequisites
- [`blender`](https://www.blender.org) 2.79

## Usage
* Open Blender file `Freezing water`
* Change background image to `background_img` in repo or anything else by selecting `Plane.001` in upperright corner and going to attribute `Properties - Material - Surface - Color`.
* Select `Cube.001` and go to attribute `Properties - Physics - Fluid` and then click `Bake` to bake fluid.
* After baking process, you should be able to see animation by dragging on timeline.
* If you would like to see fully rendered animation, please go to attribute `Properties - Render` and click  `Animation` on top to render animation. You may need to specify an `output` directory to save the image if default one is unavailable at your machine. Also make sure `Cycles Render` is selected on top which should be correctly set by default.

## Tip
- If there is any error, you can check in system console by clicking `Window - Toggle System Console` on top left corner of GUI.
