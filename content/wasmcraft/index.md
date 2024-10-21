+++
date = "2022-08-14T00:00:00-05:00"
template = "page.html"
weight = 4
title = "Wasmcraft"
slug = "wasmcraft"
draft = false

[extra]
time = "Summer 2022"
page_identifier = "projects-wasmcraft"
summary = "An optimizing transpiler from WebAssembly to Minecraft Datapacks."

[extra.image]
path = "wasmcraft/wasmcraft.webp"
alt = "wasmcraft"
visible_in_main = true
+++

<!-- more -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/wCHB1UgwM9o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Overview

_Minecraft_ is a popular sandbox game that mostly revolves around placing and breaking blocks.
As with many sandbox games, it features cheat commands that can perform various actions.
These include actions like filling areas, teleporting creatures, or updating scores.
Commands can be bundled into a group called a "datapack", and as it turns out,
these datapacks are actually turing-complete[¹](https://xkcd.com/2556/).

Wasmcraft is a tool to convert programs in WebAssembly (a popular form of code for browsers)
into a _Minecraft_ datapack.
This means, in essence, that you can run arbitrary programs inside of the game.
The video above demonstrates several different programs all compiled with Wasmcraft
running inside of _Minecraft_.

Notably, this makes me the first person in the world to be able to play Doom in unmodified ("vanilla") _Minecraft_.

### Features

- Optimizations for better performance
  - Strength reduction
  - Constant folding
  - Copy elimination
- Full SDK for writing programs
  - Compiler
  - Debugger
  - Simulator
- Minimal setup
- Works with many existing codebases

### Code

The code can be found on my GitHub page [here](https://github.com/SuperTails/wasmcraft2) if you would like to give it a try.
PRs and bug reports are accepted!