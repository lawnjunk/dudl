# dudl
> a doodle pad

# about
This is my first [zig](https://ziglang.org) project and also just my first
project with a systems programming language. It mostly exists as a learning
exercise, but I also love to draw and will probs use this tool a lot if I find time
to get it built.

# TODO
* create a model for representing a layer that fills the screen
* crate a draw square fn for writing to the layer
* create a render layer fn for writing the layer to the screen
* figure out how to zoom in and out and around

# crazy goals that may never be met
* features
  * undo/redo
  * layers
    * blend modes
    * masks or alpha lock
    * transform
  * import/export image
  * canvas expand and crop
  * zoom/scroll?
    * also snap to window?
  * vim modes (insert and normal)
    * insert - keyboard will select and apply tools
    * normal - select layers, swap layer order, change layer blend mode, etc...
  * configurable keyboard shortcuts
* tools
  * pen
    * radius
    * shape
  * blender
    * radius
    * shape
  * roller
  * fill
    * should have a way to visualize fill area before apply
    * should have a way to modify sensitivity to "like" colors
  * spray-paint
    * noise-algo selector
    * grain size
    * grain freq
    * grain shape
  * gradient
    * linear or circular mode
  * text
    * font select
    * font size
    * foreground (per char)
    * background (per char)
  * polygon lasso
  * lasso
  * color picker
* strech-goal
  * wasm/web interface
  * animation mode with tween helpers
  * font-maker
  * liquify tool
  * brush designer
  * lua/fennel script loader/runner for automating tasks and generating art
  * implement a server/client arch for controlling these features from scripts or
