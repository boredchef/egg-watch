---
title: "tamagotcha!"
github: "https://github.com/boredchef/egg-watch"
description: "i am making a bird tamagotchi that chirps and poops. i want to build it because it seems like a cool gift and because i have a bird irl that does the same stuff."
created_at: "2026-10-11"
total_time: "1h 30m"
---

# October 11, 2026: designed schem & pcb
<!-- fabricate:entry 350 -->

## woo! day one
today I designed my PCB's schematic and the pcb itself in KiCad. for my tamagotchi I wanted it to have a way to feel movement like for ex. shaking so I added the MPU5060 component so I could do things with movement

## challenges
- some issues i ran into while working on my schematic was when I ran the schematic through the electrical design checker i forgot to add no connect flags and apparently the "power" outputs on the esp32 symbol were "passive" so i got tons of errors about the checker being confused why i was using 5v on a passive pin. so i added some power flags so that the checker wouldn't scream at me. 
- another problem was that the pushbutton footprint from easyeda2kicad library would have not worked since the pads that should be separated actually shared the same thing so it would have been shorted so i had to change the pad numbers :/ 

## things for future me
need 2 work on more routing on the pcb and drc problems bc there are some. 

![](https://fabricate.hackclub-assets.com/19a299032617d6c0e2a4800670021a355ff9862c6f6aedc18e18a22c5ff5b6c4/image-png/image.png)
![](https://fabricate.hackclub-assets.com/3e6f60ad1bf4410bb387c7b395b176bf0c82c6bc03343ed39b2d87593918ebec/image-png/image.png)

Timelapse: https://lapse.hackclub.com/timelapse/henh8CpOTUKy

**Total time spent: 1h 30m**
