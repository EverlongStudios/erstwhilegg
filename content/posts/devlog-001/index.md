---
title: "Devlog 1"
date: 2022-01-15
description: "New year, new game, and new blog"
cover: "blog1-2048x1110.png"
useRelativeCover: true
draft: true
---

I've decided to start working on a game a few months ago in my spare time and I've really been enjoying the experience of making something creative and fun. I've recently decided to name this project "Erstwhile" (which means "formerly" or "past") and make a development blog to detail the progress. I fell in love with software development by reading development blogs so I thought it would be nice to start my own.

{{<video src="2021-12-05-19-23-40_Trim">}}


I grabbed some character and environment assets from the Unity asset store a while back during a big sale, so I started with those.  I combined the rigged character mesh with some free animation assets I got from mixamo.com and I had an avatar ready to go. I wrote a simple movement script I had a pretty good Idle, Run, and Roll character controller. 

{{<video src="2021-12-06-11-10-10_Trim">}}


{{<video src="2021-12-06-11-33-29_Trim">}}


{{<video src="2021-12-06-19-26-17_Trim">}}


I added what I thought was a pretty good looking mock up of how I wanted the game environment to look. I usually spend a lot of time on the world generation, but here I took a different approach and I'm just working with manual placement until I get a very solid feeling prototype and working vision for the game. 

{{<video src="2022-01-03-11-32-48_Trim">}}


I made a nice looking set for me to start working on the mechanics. 

{{<video src="2022-01-04-18-22-52_Trim">}}


I'm very new to animations, so I was happy to see a good result when I used Blend Trees for the walk-run transition. I'm still executing a lot of animations in code rather than through the Unity animation state machine, and using it more for just playing new animations on demand. 

{{<video src="2022-01-09-18-21-57_Trim">}}


I added a basic combo for the player. Noticed it was difficult to read the weapon movement so I reached for swinging trails as the next task. 

{{<video src="2022-01-10-00-54-56_Trim">}}


This was my first time using Unity's particle system, and I was seriously impressed. I used the default particle texture, and within the particle customizer panel I had a really great trail effect. Excited to use this system for more stuff soon. 

I also integrated Unity's cinemachine for the dampened camera follow behavior and it was a total breeze and no code.

{{<video src="2022-01-12-16-59-14">}}


I thought the idea of making a 3D UI and just overlaying another perspective camera over the main player camera was a cool idea. I got to use emissive materials for the first time and when mixed with the post processing effects I have I think it reads very nicely. 

{{<video src="2022-01-12-15-33-49">}}


I needed to use the new UI element I built, so I made a simple stamina system. It consumes on attacks and rolls and will recharge when not doing those actions. 


Thanks for reading, hope you enjoyed it. I also do a lot of these updates on [my twitter](https://twitter.com/f0ssel) if that's your thing. 
