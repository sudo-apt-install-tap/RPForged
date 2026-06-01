---
title: RPForged: A RP2040 Devboard.
author: Tap
description: It is based on a RP2040. It has USB C port.
created_at: "2025-12-25"
---

# 1/2/2026 10 AM - Making the schematic.   

### 30.12.25

I made the schmatic for the devboard today(Just the PD RP2040 and the USB C tho). This will serve as a basic devboard to replace Arduino nano or RPi Pico in my projects. Read the documentations for the RP 2040 and also learnt about decoupling caps and how to reduce voltage.<BR>
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NjY2NjksInB1ciI6ImJsb2JfaWQifX0=--c83f008602aea8bdfa77931b608cca4b05dcff6d/image.png) <BR>
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NjY2NzAsInB1ciI6ImJsb2JfaWQifX0=--dc7f8462aa01a3df154d85e9b7d56cf668f8a152/image.png)


**Total time spent: 2hour 30minutes**

# 1/2/2026 6 PM - FINISHED THE SCHEMATIC!! FINALLY!!  

Ive finished the schematic and honestly it looks dang good. I mostly followed the tutorial also tried to read the documentation, couldn't understand anything will probably try to read it again.

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NjcwNjUsInB1ciI6ImJsb2JfaWQifX0=--ee1a63f30395a05874e7566f11dab9591bef1aa1/image.png)
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NjcwNjYsInB1ciI6ImJsb2JfaWQifX0=--f3e5790824ed57b20c8386345aeb0416ffb780f1/image.png)
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NjcwNjcsInB1ciI6ImJsb2JfaWQifX0=--2074bcca3b8b783df2c97d4b16168cfa46e85ecb/image.png)
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NjcwNzMsInB1ciI6ImJsb2JfaWQifX0=--d2e7fe8c3bb36a1e7a282d968a7df8a655516672/image.png)
  
**Total time spent: 2hour 30minutes**


# 1/5/2026 - Routing, drawing and pain  

### 3.01.25
I am having some issues with the caps. All GND pads are getting connected as 1v which basically makes it impossible to route. I am currently trying to understand why this is happening but yeah I wasted like 1hr plus 30mins to get the layout right.

Alas i had to redo the caps in the schematic and now everything works fine, took me like 45mins to figure it out and reroute the traces.

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzMzNzEsInB1ciI6ImJsb2JfaWQifX0=--865e36e63fc1304ca219601e8ae1800063908501/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzMzNzMsInB1ciI6ImJsb2JfaWQifX0=--8cbcee96f43fc357b910fef22a45abdda66e0ffb/image.png)


### 4.01.25
FINISHED THE ROUTING and the silkscreen. I made some art and yeah it looks great. Also i did the groundpour but some components were not connecting to it so i used vias and traces to connect all of them, in total this took me a WHILE like 3hrs :sob:. I am not really the most effective worker.

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzMzNTMsInB1ciI6ImJsb2JfaWQifX0=--6bba4f5ac4394899dd6d66c3cd2084ce263ede0e/image.png)

![Untitled-2026-01-04-1536](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzMzNjAsInB1ciI6ImJsb2JfaWQifX0=--b042b6576bd6aaf810234e7efffdec6c3d6a75db/Untitled-2026-01-04-1536.png)

![Untitled-2026-01-04-1536(1)](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzMzNjksInB1ciI6ImJsb2JfaWQifX0=--2e7b0bdeb3d91e903d649e0a449d42ffcdb0bce9/Untitled-2026-01-04-1536(1).png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzU4MTMsInB1ciI6ImJsb2JfaWQifX0=--4b502c8f73cf9197f5a754d4d6e6c2f448f52d5e/image.png)
3.3V Caps

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzU4MTYsInB1ciI6ImJsb2JfaWQifX0=--2efaa7943fb13b6e35f1a584319c981098f4a0f2/image.png)
Crystal Wiring

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzU4MTcsInB1ciI6ImJsb2JfaWQifX0=--4ab6b4141eeae0e67dde61f21fbfd9e0f3411c3d/image.png)
PD Wiring

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzU4MzMsInB1ciI6ImJsb2JfaWQifX0=--6b5601ca8ba029a3822c5728ea519b6b4e8ccf41/image.png)
GPIO Wiring

### 5.01.25
Fixed DRC errors for the ground pour and thermal relief. Now i have some board clearance, trace clearance and courtyard overlaps left. This took me another 45mins.
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzMzNTgsInB1ciI6ImJsb2JfaWQifX0=--4e31d29ec132635cf6645b60be78bd93d5264e97/image.png)

**Total time spent: 2hour 30minutes**
   

# 1/6/2026 1 PM - Rerouted the PCB  

The routing was a rats nest. So I thought I should try to fix it. I did not have the patience to route it by removing every track. I deleted every component except the RP USB and the pins. Then I place and routed the components. Now my pcb looks like a spiders nest straight and obtuse. I think that this wiring is objectively better than the old one. Ive reduced the via count from 52 to 45 and made it look better. I am overall very happy about how this has turned out<br>
![Front RT](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzQ4NjksInB1ciI6ImJsb2JfaWQifX0=--67854ef09015c35aa67189b836a471bb72ab4098/Front%20RT.png)
<br>
![Back RT](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzQ4NzAsInB1ciI6ImJsb2JfaWQifX0=--c347db20e25ef7e693e73b9c2e868d61dfcb2f17/Back%20RT.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzU4MjcsInB1ciI6ImJsb2JfaWQifX0=--002ddf6fc57258117ae6467c20c7f1a52c7beecc/image.png)
New 3.3V Caps.
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzU4MjgsInB1ciI6ImJsb2JfaWQifX0=--1122a477a22397740a61501f8269f49e8a795df9/image.png)
PD and Flash Wiring.
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzU4MjksInB1ciI6ImJsb2JfaWQifX0=--4c02bda027b5396502c75e5890365a484dc0a132/image.png)
GPIO Wiring  

**Total time spent: 2hour**

# 1/6/2026 3 PM - JLC ORDER ADDED TO CART  

I did the BOM and the CPL files. Changed them according to the tutorial. After I tried to upload the BOM and CPL to JLCPCB for PCBA it gave me errors constantly. I asked around in #kais-kitchen on slack and @Simon Peijnenburg helped me. Turns out i just had to change the BOM's formati to .XLSX. After such a long time it is alas done.
![Cart](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzQ4OTcsInB1ciI6ImJsb2JfaWQifX0=--9322fe8537aa734d2b8ea1b4c1af887cd7e81fd7/Cart.png)

**Total time spent: 1hour 30minutes**

# 1/23/2026 - Ordered The PCB and The PCBA And Made Some Fixes!  

So I got the approval finally YAY!!! So Ive changed the silkscreen a bit. Some components were also changed due to high prices on JLCPCBA. Ive done the order for the pcb and the pcba now. Ive also ordered some pin headers for the board from robu.in.
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODg5OTcsInB1ciI6ImJsb2JfaWQifX0=--283b728d335f8987212b8fe7a17c8e61246711c4/image.png)

**Total time spent: 1hour 30minutes**

# 1/27/2026 - Removed All Micro-Vias  


So it turns out that JLC cant fabricate microvias without the 4 wire kevlar test. I didn't know this. I had to reroute the whole PCB **AGAIN**! But now I've removed all the microvias and am using only regular vias. Also Ive ordered the PCB with PCBA. The headers have been purchased from robu.in.

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6OTI4MDAsInB1ciI6ImJsb2JfaWQifX0=--cf005c2ed388c106f09ae2cc7728fd9963205e9a/image.png)
Email from JLC

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6OTI4MDEsInB1ciI6ImJsb2JfaWQifX0=--2feba0d1af2e77516deb249be44ad7e187c28ffd/image.png)
Confirmation from JLC.

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6OTI4MDIsInB1ciI6ImJsb2JfaWQifX0=--96c6bcf2a627b7b90c54c9377edbbbc4b4307218/image.png)
PCB View

![Front RT](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6OTI4MDQsInB1ciI6ImJsb2JfaWQifX0=--b6714083b681e09c5cb078b925f87a2566f8538d/Front%20RT.png)
PCB Front RT

![Back RT](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6OTI4MDUsInB1ciI6ImJsb2JfaWQifX0=--8520c27ca07994a159e542fd1543023190e49bef/Back%20RT.png)
PCB Back RT

**Total time spent: 5hour**

# 2/10/2026 - So it turns out that I kinda bricked my board.  

Well this is **embarrassing**. I made the schematic wrong! I just now realized it! I basically wired the crystal wrong. I connected the XIN and XOUT pins (1 and 3) to GND and shield pins (2 and 4) to XIN and XOUT pins. This has kinda bricked my board. Before i discovered this I de soldered the 1k ohm resistor on the push button and lost the resistor 💀. I also thought this was due to run floating So i connected it to both GND and 3v3.... pst it dint work. So I am getting a hot plate soon so I can probably fix it soon enough! Will update.

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTAxNTU0LCJwdXIiOiJibG9iX2lkIn19--d6ad402724a92628db7e09ab5c8a6a5c3b1b6ffa/image.png)
  
**Total time spent: 5hour**

# 2/11/2026 - Fixed the PCB  

_Time spent: 0.5h_  

So I changed the schematic and the PCB. I will need to fabricate it again! I have about 3USD left in my card so I will apply for a topup of like 10USD. I will handsolder all the components!
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTAyMzMwLCJwdXIiOiJibG9iX2lkIn19--007195b09ad53a2e6e444133f4c3f0fa3f88908e/image.png)  

**Total time spent: 30minutes**

# 3/2/2026 - THIS IS CRAZY!!  

### Intro

So I did the pan reflow method. Yeah, I know, it’s infamous. Safe to say it works!! Completely unreal. Devboard is stable, crystal aligned perfectly. Next repeating the process on my other assembled board.

----

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTEzNzY3LCJwdXIiOiJibG9iX2lkIn19--d92f7bcfa468b51ae38fc111c7a5950fd30c8ca5/image.png)<br>
PCB on pan.

----

### To Those Who wanna do this(which I do not recommend):

- Make sure that you add a good amount of flux.
- Heat up the pan rapidly, then put it to medium heat.
- Make sure the board doesn't get too hot otherwise the pads may be in danger!

----

**Total time spent: 1hour 30minutes**
