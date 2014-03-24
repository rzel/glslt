# gestalt

Gestalt is a GLSL plugin for Light Table.
It initially targets the OpenGL ES GLSL Specification.
The goal is for the program to be a good teacher.
Essentially, someone should be able to learn GLSL by fiddling with a sample program through the guidance of the plugin.

In terms of functionality, this translates to:

- Powerful autocomplete for all built-in functions, with inline documentation
- Live re-rendering of a shader as you modify it
- inline, helpful errors for invalid shaders
- Graphical tools for feeding input (e.g. images, webcam) and observing intermediate values/output of a shader
- Debugging functionality, e.g. stepping through the rendering pipeline on a per-vertex or per-pixel basis
- C-Tags-esque support for viewing the overall structure of a GLSL program in terms of functions, structs, variables.
- Fullscreen mode to display the live output of the program under the text.

For this to work, we need:

- A GLSL parser, ideally an incremental one
- A file watcher
- A pipeline for capturing/redirecting errors
- A default WebGL context for rendering and plugging in new inputs
- Nice tools like color pickers, matrix renderers...

Progress:

[*] Initial Readme
[ ] Parser
[ ] Autocomplete
[ ] Live preview
[ ] ...
