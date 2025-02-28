---
layout: post
title:  "Fusion(Amazing Seasun Game)"
summary: "Game Developer Intern"
date:   2024-08-20 00:00:00
preview: /assets/internshippreview.PNG
---

![Picture 1](/assets/internship_showcase1.PNG)

During the summer of 2024, I worked as a Game Developer Intern on the Fusion team at Amazing Seasun Games, which was in its pre-research stage. My role primarily resembled that of a Tool Engineer, focusing on developing a Procedural Content Generation tool in plain Unreal Engine 5, without relying on plugins, for use by level designers. Although UE5 already includes a PCG plugin, the team lead believed exploring and learning the technique from scratch was beneficial.

I researched PCG implementation by studying resources such as the Deep Dive into the Electric Dreams Project Inside Unreal talk and the Level Design Summit: Urban Planning in Games from GDC 2024. These resources helped me gain a comprehensive understanding of Epic's PCG tool development logic and level designers' modular segmentation strategies.

As a result, I developed an environment generation tool in UE5 based on the Spline system and Blueprint. The tool features two modes: one for auto-generating objects based on size and another for manual placement with optional randomization.

Additionally, I implemented a PCG rule to prevent environment-road intersections by dynamically updating the valid line segments on the Environment Spline and regenerating the environment when intersections occurred. Unfortunately, not all bugs in the road logic were resolved before the end of my internship.

If you want more details,[Github Repo](https://github.com/chelliy/Internship_Work_Showcase)