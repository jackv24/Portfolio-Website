+++
title = "Networked Multiplayer Pong / Brick Break"
date = 2017-06-26T22:55:49+09:30
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["game"]

# Project summary to display on homepage.
summary = "A networked multiplayer mashup of pong and brick break, using RakNet, OpenGL, and C++"

# Optional image to display on homepage.
image_preview = "network-pong-cover.png"

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

+++

A networked multiplayer mashup of pong and brick break, using RakNet, OpenGL, and C++

[View Source Code on GitHub](https://github.com/jackv24/NetworkingAIE)

This game runs with two clients connected to a server. The server is authoritative, and the clients implement dead-reckoning by only sending data when important events occur, such as a ball bouncing, a block breaking, etc. The game is simulated on the clients and server for smooth gameplay, but the only data the clients themselves can send is key presses.

Data is only sent when these events happen, making efficient use of bandwidth, and gameplay is accurately synced across clients.

{{< figure src="img/pong.gif" title="One of two clients running the game. Setup is one server, two clients." >}}