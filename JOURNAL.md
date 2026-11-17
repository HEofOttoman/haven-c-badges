---
title: "Haven Canberra Badges"
author: "Henry W"
description: "Badges for Haven Canberra"
created_at: "2026-10-13"
---

## October 12: Starting 3 Hours
![help](<assets/Screenshot 2026-10-22 185522.png>)

![kicad schem](<assets/Screenshot 2026-10-10 184327.png>) 
![easyeda](<assets/Screenshot 2026-10-10 183841.png>)

I made this
I did schematic, it is enough for back then. 
I yoinked it from shelley's nfc card

that's an issue bc I don't have the footprint that I can port over.

uh yeah so I did the easyeda2kicad stuff

but then antenna didn't connect correctly

So I decide to use notaroomba's lib in the cybercard

Help.

I decided to manually assign LB & LA to the two ends of the antenna coil with E [properties]. That should work? But I still think the design is horrendous. I think that I should prolly use Figma to get a better outline

<!-- <a href="https://gitviewsmap.onrender.com/heofottoman">
  <img src="https://gitviewsmap.onrender.com/badge/heofottoman.svg" alt="GitViewsMap Visitor Badge" />
</a> -->

## 26 October: Finishing up 5 Hours
![conflicting pcb design? I had a worse one before](<assets/Screenshot 2026-10-22 224307.png>)
Oh god help I can't decide aaaa. I had trouble thinking about the designs of my pcb.
I start narrowing down my PCBs design choices because I had a LOT to think about. All in all I hope this will end up good 🤞

(Actually from 24 October?)
I'll try list what goes through my head in designing and what needs to be decided but:

1. Where the carillon sits on the thirds
2. Where to place the antenna
   1. The sections of the antenna intersecting with the antenna will be removed/replaced with the metallic finish, and I think that could potentially look amazing
   2. Metal finish near the antenna will also interfere

3. Where to put the light that comes led from the NFC to tie the design together
   1. I could put it on the mountain because mountain light
   2. Or on the carillon because glowie
   3. Or on the colored haven logo (what im thinking rn, easiest without moving) 
   4. Or beneath in the basically unused bottom 
   5. Or even behind on the telstra tower

4. Where to put the artistic solder mask cutout and metal finish
   1. thinking of putting the metal in the haven | CBR Canberra 
   2. Or I could put it on the owl but that would interfere with the antenna :hs: I really wanna

5. The black/white negatives of the back (+where to put :canberraisbetterthansydney: )
6. To expand/modify the board shape rn :wiltedrose: 
   1. pointy corners, filleting them
   2. Might not be enough space, too compact. Perhaps be more square?
   3. or change the angles of the 'barb'  to be less steep

I def ended up reducing the sharpness of the 'crest'. And I also added daven

## 27 October: I MUST SHIP - 8 Hours

8 PM - I am now arranging the massive array of objects into layers. I have to round the corners and make sure it's rounded 30 on the other asw. I re-exported the Board outline from figma & imported it with 0.1225 scale. Exported entire layers designed in figma to kicad at 98.5mm high
The back silkscreen I imported as graphics
349 something * 0.1225 yielded a result that was pretty close to what I needed
![thing old vs new](<assets/Screenshot 2026-10-27 230921.png>)
I had to reimport a bunch of stuff because OF DAVEN 