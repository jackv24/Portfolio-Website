+++
title = "Dungeon Chop Chop"
date = 2017-09-26T22:08:26+09:30
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["game"]

# Project summary to display on homepage.
summary = "A top-down rogue-like dungeon crawler, with co-op play!"

# Optional image to display on homepage.
image_preview = "dungeon-chop-chop-cover.png"

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
album = "UI"
image = "dungeon-map.gif"

[[gallery_item]]
album = "UI"
image = "dungeon-options.png"

[[gallery_item]]
album = "Effects"
image = "dungeon-tree-sway.gif"

[[gallery_item]]
album = "Effects"
image = "dungeon-ground.gif"

[[gallery_item]]
album = "Effects"
image = "dungeon-quicksand.gif"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc01.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc02.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc03.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc04.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc05.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc06.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc07.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc08.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc09.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc10.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc11.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc12.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc13.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc14.png"

[[gallery_item]]
album = "Screenshots"
image = "dungeon-sc15.png"

+++

{{< youtube qHSR8Jajxno >}}

[Download](https://github.com/jackv24/DungeonChopChop/releases) | [View Source Code](https://github.com/jackv24/DungeonChopChop)

# My Contributions
Here are some of my contributions to this game:

## Level Generator

This level generator is used to generate every level in the game, through the use of different profiles. It can generate an Overworld with different biomes, and Dungeons with a key and chest room.

Source code for the Level Generator and run-time level managing [can be found here.](https://github.com/jackv24/DungeonChopChop/tree/master/Assets/Scripts/Level)

{{< figure src="img/dungeon-levelgen.gif" title="The Level Generator in action, generating the Overworld (slowed down - actual layout generation is much faster)" width="50%" >}}

## User Interface
Most of the user interface of the game was implemented myself, excluding the in-game HUD.

The map shows what tiles have been visited, and supports showing map icons and dynamically zooming and resizing at run-time.

There is also a fully functioning options menu that can be accessed in-game or from the main menu, and save's preferences for next boot.

{{< gallery album="UI" >}}

## Visual Effects
I was also responsible for writing all of the shaders we use throughout the game. This includes a foliage shader for rendering swaying grass and trees, a ground shader for tiling UVs based on world position, a spinning shader for quicksand, and a simple flashing shader for indicating character damage.

{{< gallery album="Effects" >}}

# Editor Tools
A number of editor tools were created to aid development. One of these was an enemy spawner editor, which allowed editing of multiple spawner profiles, and visualizing spawn points.

{{< figure src="img/dungeon-enemy-spawner.PNG" >}}

# Screenshots

{{< gallery album="Screenshots" >}}