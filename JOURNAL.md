---
title: "aerix-20x20"
author: "I AM LITREALLY FBI"
description: "a 20x20 rp2350 flight controller"
created_at: "2026-11-09"
---

# 2026-11-10: finish

**Total time spent: 3 hr**

![image.png](https://cdn.hackclub.com/01a1c482-0a2f-72d4-b15d-4b45d435dbc3/image.png)
![image.png](https://cdn.hackclub.com/01a1c482-2d9f-7124-bbe1-b71800821982/image.png)
![image.png](https://cdn.hackclub.com/01a1c482-58a7-7e15-9bd4-878e0c0f39cb/image.png)
![image.png](https://cdn.hackclub.com/01a1c482-7274-7360-9884-16cb009dacf0/image.png)

finished the design by making the silkscreen better and laying out all the components properly fixing all the traces and making the whole thing better and better, 
![image.png](https://cdn.hackclub.com/01a1c483-7366-7105-8a6c-d59860939910/image.png)
![image.png](https://cdn.hackclub.com/01a1c483-a94e-76f3-969f-851a731f0354/image.png)

here is the final done thing took a lot of time read a lot datasheet it, as i have designed fc's earlier it was easy for me this time

# 2026-11-09: laying stuff out

**Total time spent: 1h 30m**

![image.png](https://cdn.hackclub.com/01a1c19e-1fa8-73a1-b466-e5c341fdcd65/image.png)
![image.png](https://cdn.hackclub.com/01a1c19e-9838-7bf7-b66b-e19848ead2c4/image.png)
![image.png](https://cdn.hackclub.com/01a1c1a0-c0fa-7758-a12b-84399e5330c8/image.png)
proper layout so i figured out i can place my mcu in middle and the rp2040 in the middle and baro on top and figure out  this layout and place the 5 debug pads so i can use those prongs make a adapter and debug it and all of that and i plan to use openpixel osd 

# 2026-11-09: laying out start

**Total time spent: 2 hour**

![image.png](https://cdn.hackclub.com/01a1c138-e664-7e9d-8d74-a482a46ff78a/image.png)
![image.png](https://cdn.hackclub.com/01a1c138-faf9-790f-85ba-bb0521d0d55f/image.png)
![image.png](https://cdn.hackclub.com/01a1c139-0b8f-70ca-ba99-d1cc640ecbc5/image.png)
![image.png](https://cdn.hackclub.com/01a1c139-1dc2-764c-a51c-7571022d1b47/image.png)
![image.png](https://cdn.hackclub.com/01a1c139-2ccd-7d1e-bcca-de2b7ce00cfc/image.png)
![image.png](https://cdn.hackclub.com/01a1c139-516b-7a05-8f7d-127a71100094/image.png)

laying out all the items in the pcb figuring out the best layout how to wire the osd and everything in the pcb and where to place the rp2354 and all the other ic

switched between a lot of places and all

# 2026-11-09: schematic doonen

**Total time spent: 2 hours**

MCU 

![image.png](https://cdn.hackclub.com/01a1c070-bf83-7d6a-a988-844413b30783/image.png)

SENSOR & BLACKBOX

![image.png](https://cdn.hackclub.com/01a1c070-fe0b-797c-b5fe-99633d18baeb/image.png)

osd, rgb, buzzer

![image.png](https://cdn.hackclub.com/01a1c071-5f82-7cee-896d-66ccb7095093/image.png)

power

![image.png](https://cdn.hackclub.com/01a1c071-af18-7d2f-a2e8-a6061b139dcf/image.png)

connector and pads

![image.png](https://cdn.hackclub.com/01a1c072-0aef-7bd9-bbc5-511621afb878/image.png)

I organized the KiCad schematic, wired up the gyro and Blackbox flash, and added the analog OSD, buzzer, and RGB LEDs. I also laid out the connector and solder pad pinouts and picked a shorter inductor to keep the board low-profile. Next up is PCB placement and routing.

# 2026-11-09: start

**Total time spent: 20 mins**

![image.png](https://cdn.hackclub.com/01a1bfc0-3ee2-785c-9f47-1758cfb3d44c/image.png)

I’m building a compact FPV flight controller around the RP2354A, with a 20 × 20 mm mounting pattern. The goal is simple: fit it in a race build and go fast fast brr brr.

I picked the ICM-40609-D as the gyro and accelerometer. The part I’m most excited to test is the analog OSD. The RP2354A will generate the overlay itself, and a small analog circuit will mix it into the camera feed before it reaches the VTX. That lets me put flight data on screen without a dedicated OSD chip.

