---
layout: post
title:  "Fusion(Amazing Seasun Game)"
summary: "Game Developer Intern"
date:   2024-06-20 00:00:00
preview: /assets/postpreview.png
---

![Picture 1](/assets/fullsize.png)

In 2024's summer, I worked as Game Developer Intern in the Fusion team from Amazing Seasun Game, which is in its pre research stage. Specifically, what I have done here is more like a Tool Engineer focusing on developing Procedural Content Generation tool in plain UE5(no plugin) for level designers. Although UE5 already have its PCG plugin, the team lead believe there is no harm to explore and learn the technique. 

I conducted research on PCG implementation, studying resources such as the "Deep Dive into the Electric Dreams Project | Inside Unreal" talk and the "Level Design Summit: Urban Planning in Games" from GDC 2024, to gain a comprehensive understanding of Epic's PCG tool development logic and level designers' modular segmentation strategies.

What I have complished is an environment generation tool in UE5 based on the Spline system and Blueprint, featuring two modes: one for auto-generating objects based on size and another for manual placement with optional randomization.

Also I implemented a PCG rule to prevent environment-road intersections by updating the valid line segments on the Environment Spline and regenerating the environment when intersections occurred. Unfortunatly, bugs aren't all fixed in road logic's final version before my intern ends.

If you want more details,[link](https://github.com/chelliy/Internship_Work_Showcase)