---
layout: page
title: Giang's portfolio
permalink: /portfolio/
---

# Professional
## Prison Architect (Windows, Linux, macOS, PS4, Xbox One, Nintendo Switch)
with Double Eleven, 2022

![© Paradox Interactive](https://raw.githubusercontent.com/tongtunggiang/tongtunggiang.github.io/master/assets/images/d11_pa.jpg)
- DLCs: Going Green, Second Chances, Perfect Storm.
- Work on new features, maintained/refactored existing code and fixed bugs.
- Work on many different areas of the game: gameplay logic, UI, AI, optimisation, asset tooling, rendering, etc.
- Enforce modern C++ practices (smart pointers, constexpr, RAII, templates,...)
- Help and coach junior programmers.
- Do code reviews.
- Assist the lead programmer in sprint planning and designing feature solutions.

## Epic Odyssey (Android, iOS)
with Hiker Games, 2019

![© Hiker Games](https://raw.githubusercontent.com/tongtunggiang/tongtunggiang.github.io/master/assets/images/hiker_eo.jpg)
- The last project before leaving Vietnam for the UK - work on prototype and pre-production stages.
- The development process used Unity 2019.
- Work on several tools: quest creation and serialisation, player progress, dev-mode mock formation and more.
- Gameplay mechanis implementation: quest interaction, camera control, fog of war, dialogue system.

## Arena of Survivors (Android, iOS)
with Hiker Games, 2018

![© Hiker Games](https://raw.githubusercontent.com/tongtunggiang/tongtunggiang.github.io/master/assets/images/hiker_aos.jpg)
- The development process used Unity 2017, Photon Unity SDK, Photon Quantum SDK.
- Take the main responsibility for input handler, core mechanics, network replication algorithms and data structures.
- Lead the learning and adapting process of Exit Games’ Photon Unity Network SDK, and later, Quantum Deterministic SDK for the team.
- Build a successful workflow based on git branching and Jenkins automated builds.
- Get myself familiar with a wide range of concepts along the way, including (notably) the Entity-Component-System (ECS) programming model, C# unsafe code, network optimisation, and CI/CD environment.
- Perform network and gameplay optimisation.

## FZ9: Timeshift (Android, iOS)
with Hiker Games, 2017

![© Hiker Games](https://raw.githubusercontent.com/tongtunggiang/tongtunggiang.github.io/master/assets/images/hiker_fz9.jpg)
- The development process used Unity 5.6.
- Fix legacy bugs and do refactoring occasionally.
- Work closely with game designers to deliver new features and content.
- Design and develop data structures to store configurations of new PvP mode, where players build their base to store their gold and get more of that by invading others’ bases.
- Expand the replay feature for the new PvP mode, where players can check how did other ones solve their formation.
- Design and program new features with code cleanness in mind.
- Using FSM and State pattern to create the boss of the story mode’s chapter 7.

## Galaxy Gunner: Adventure (Android)
with Tofu Games, 2017

![© Tofu Games](https://raw.githubusercontent.com/tongtunggiang/tongtunggiang.github.io/master/assets/images/tofu_galaxygunner.jpg)
- The development process used Unity 5.6.
- Refactor legacy code to reduce technical debts.
- Develop gameplay systems: player combat system, enemy system and weapon system.
- Develop a simple 2D timeline system to play 2D cutscenes that can be triggered by various conditions.
- Create a data-oriented behaviour tree system for NPCs.
- Design and program data structures for storing player progress and inventories.
- Apply the git-branching model and train other teammates to use that.
- Assist other programmers when they need technical advice or a solution.
- Perform game optimisations.

# Personal
Occasionally, I do pet projects for fun. These projects can be anything. Some of them are pieces that I find interesting at work. Some of them are just learning, research and experiment. Some of them are improvements to existing solutions, both mine and others. Some of them are tutorials for things that I made mistakes before and I want to share that painful experience.

## Learn graphics programming (WIP)
- Follow learnopengl.com as I have absolutely zero idea how to write a renderer from scratch.
- Learn about graphics pipeline, texture, vertex, shader, buffers, lighting, camera and a lot of other basic stuff.
- Occasionally going off route by spending way too much time designing engine subsystems...

## Unity-EnTT
- Continue with EnTT, this time with Unity. 
- Write a very simple tower defense logic layer in ECS with EnTT.
- Link: https://github.com/tongtunggiang/unity-entt

## Rewrite my first game in university with C++ and SDL using ECS architecture
- Rewrite my first game: same gameplay, same horrible mechanics, new ECS practices (powered by EnTT).
- Link: https://gitlab.com/TongTungGiang/GreenSwordfish

## ECS Experiment with Unity

- Use Unity 2019.3.
- Write two demos: one in traditional Mono and the other one in ECS and throw many agents to the scene.
- Performance comparison.
- Learn the uniform grid spatial partitioning technique and implement it in ECS using multi hash maps.

## Line of Sight Implementation in UE4

- Use Unreal Engine 4.18.
- Playing around with UE4’s procedural mesh generation.

## An Object Pool solution for Unity 3D

- A common optimisation practice.
- Data-driven workflow friendly allowing quick setup.
- Should be applicable on most Unity versions.


## A C#-inspired event and delegate implementation in C++

- Built on the foundation of the Observer pattern.
- Featuring function pointers encapsulated in a class.
- … and a colourful output window just for fun.
