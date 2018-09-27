+++
title = "Custom OpenGL Graphics Engine in C++"
date = 2017-08-26T22:57:39+09:30
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["other"]

# Project summary to display on homepage.
summary = "A custom graphics engine written in C++ using OpenGL."

# Optional image to display on homepage.
image_preview = "opengl-engine-cover.png"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

[[gallery_item]]
album = "Screenshots"
image = "opengl-sc01.png"

[[gallery_item]]
album = "Screenshots"
image = "opengl-sc02.png"

+++

A custom graphics engine written in C++ using OpenGL.

[Download Here](https://github.com/jackv24/ComputerGraphicsAIE/releases/) | [View Source Code on GitHub](https://github.com/jackv24/ComputerGraphicsAIE)

This custom graphics engine was written using C++ and OpenGL, utilising AIE's Bootstrap, which includes a few extra things such as ImGui. The shaders shown below were written in GLSL.

![Demonstration gif](/img/opengl-gif.gif)

This graphics engine supports static and animated models in OBJ and FBX format, though animations are only supported in FBX. Render targets are used to display the post-processing effects shown above.

{{< gallery album="Screenshots" >}}