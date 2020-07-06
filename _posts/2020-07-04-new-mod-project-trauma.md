---
layout: page
title: "New Mod Project: Trauma"
date: 2020-07-04 08:45:00 -0500
categories: mod-announcement, minecraft, coding
---

Welcome all, friends and family, colleagues and associates, bitter and hated enemies, etc. I decided it was far past time for me to have my own cozy little screaming corner from which I can project my soul into the void, so here we are! Technology is grand. Right now as you read this I am breaking a cartoonishly large wine bottle over my laptop, and by breaking I mean breaking open and drinking in healthy moderation.

This accomplishment comes on the coattails of another! Just last week[^1], I released a mod for Minecraft on CurseForge. While I've made mods in the past (usually as simple custom solutions for servers I've run) this is the first time I've felt confident enough in a concept to release it publically.

[^1]: At least, I'm pretty sure. I'm between jobs and my country is crumbling to the ground, so time is a little hard to track for me right now.

## Introducing Trauma

Trauma is based on a mod that I originally made for a 1.12 modpack I was developing. My goal was to improve the survival aspect of the game, through the weakest vector I could think of: the health system.

From the [CurseForge][] page:

> This mod implements an alternate health and damage system. The following changes to the base mechanics are made:
>
> 1. Players no longer die at zero health. Instead, they enter a  knockdown state with severe penalties (slowness, mining fatigue, and  weakness).
>
>    1. Healing back up to at least one full heart will revive them.
>    2. If a player is not revived within ninety seconds, they will bleed out and die (for real).
>
> 2. Any time a player takes damage, they have a chance of gaining an 
>
>    *injury*.
>
>    1. For every injury a player has, one heart of health becomes incapable of healing.
>    2. Injuries do not go away on their own, but sleeping through the night will heal one.

The original was made with [Forge][], which, while it worked, had to necessarily be limited in certain features due to the need to comply with Forge's general ideology. This version is instead made with [Fabric][], which is an extremely interesting project that I absolutely attribute the technical successes of this mod to. I have a lots of thoughts about Fabric and it's role in the evolving modding community, but that is a topic worthy of it's own post.