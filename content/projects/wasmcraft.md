+++
date = "2022-08-14T00:00:00-05:00"
title = "Wasmcraft"
description = "An optimizing transpiler from WebAssembly to Minecraft Datapacks."
slug = "wasmcraft"
draft = false

[taxonomies]
    categories = ["projects"]
    tags = ["zola"]

[extra]
    page_identifier = "projects-wasmcraft"
+++

An optimizing compiler from WebAssembly to code for the game Minecraft.

<!-- more -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/wCHB1UgwM9o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Overview

_Minecraft_ is a popular sandbox game that mostly revolves around placing and breaking blocks.
As with many sandbox games, it features cheat commands that can perform various actions.
These include actions like filling areas, teleporting creatures, or updating scores.
Commands can be bundled into a group called a "datapack", and as it turns out,
these datapacks are actually turing-complete.

Wasmcraft is a tool to convert programs in WebAssembly (a popular form of code for browsers)
into a _Minecraft_ datapack.
This means, in essence, that you can run arbitrary programs inside of the game.

lorem ipsum dolor sit amet.

### Features