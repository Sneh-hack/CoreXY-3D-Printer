---
title: "3D Printer"
github: "https://github.com/Sneh-hack/CoreXY-3D-Printer/tree/main"
description: "A Custom 3D Printer!!! No idea how I will make it... but I will! "
created_at: "2026-10-01"
total_time: "32h 30m"
---

# October 1, 2026: Learnt how a 3D Printer Works + Roughly Designed Mine

To be honest, I have no idea how a 3D printer works. Or at least HAD no idea. So the first thing I did was a lot of research and when I say a lot, I mean a LOT. From the key components required to make a 3D printer to the basic mechanics. I used a combination of youtube videos and Google AI to learn all this. I watch youtube tutorials and not just two or three, like 15 - 20 whole tutorials on different people making different 3D printers. As I watched the tutorials, I took notes on how each 3D printer worked and the key components they used. At the end, I thought a Core XY Printer would be the easiest to make. The mechanics and everything felt very simple and straight forward to make. Based on all that, I started designing my own 3D printer. This was a rough design, no CAD models. Just sketches notes on a piece of paper. I split the process in to four parts; Mechanical Frame, Motion, Electronics, Nozzle + Extruder. The Mechanical Frame was quite simple, a frame made of aluminium extrusions. The motion included planning out the X, Y and Z axis. Also simple. Here I started using Google Ai to figure out which motors would be the best option; Nema 17. For the electronic, I also used AI to help me and decided to use Raspberry Pi CM4, BTT Manta M8P V2.0 for the motherboard and BTT TMC2209 for the stepper motor drivers.

![](https://fabricate.hackclub-assets.com/e5b922cb692d34eb8704f3028540527dd58eec01e3e29c4920868e074f373b8a/WhatsApp%20Image%202026-10-01%20at%2022.09.53.jpeg)
![](https://fabricate.hackclub-assets.com/128b0151134015fb52907f5e55224530eed548a0bcc6bbd9ba975ef52da600ff/WhatsApp%20Image%202026-10-01%20at%2022.09.53%20%283%29.jpeg)
![](https://fabricate.hackclub-assets.com/0a31cb8d31ad8b1c7e5494240196c4036e706355249f0f6fe54ed5d358160304/WhatsApp%20Image%202026-10-01%20at%2022.09.53%20%282%29.jpeg)
![](https://fabricate.hackclub-assets.com/725f33f927376c39f9a9889266bab59845b800dc978df29e61ca3c25e6a7d61b/WhatsApp%20Image%202026-10-01%20at%2022.09.53%20%281%29.jpeg)

**Total time spent: 4h 30m**

# October 7, 2026: CAD Model

I started creating a CAD model based on the design I had in mind. I started making it and spent a few hours on it but then thought that there had to be a easier and faster way of doing this. Then, I had an idea. I researched existing CAD models of CoreXY 3D printers and modified it to fit my design. I used Rolohaun's SimpleCore 3D printer CAD model on his github page and changed it so that it would fit my electronics and meet the dimensions I had in mind. The main parts and the frame stayed the same since Rolohaun's printer also used nema 17 motors and aluminium extrusions. So, in order to add a personal touch to my printer, I added a cool back panel with ash-greninja (Pokemon), acrylic side and top panels to show the electronics and mechanics and cool LED strips to take the 3D printer next level. Later on, I am thinking of adding a display and other unnecessary and random but cool things but I'm not to sure yet. Just to explain how I made the back panel; I got an image off google, turned it into a vector drawing, imported onto shapr3D and extruded the shapes. This took a lot longer then I expected and was one of the most annoying things I had don't. I only needed to extrude some shapes, not all (that is what would give the 3D effect). Doing each one by one would take forever since there were a billion shapes. So I selected all the shapes I had to extrude and extruded them at once. But...every time I was done selecting all the shapes, I would accidentally touch something else and all the shapes would be unselected. Yes... You ca imagine how annoying that would be, selecting a billion shapes just so that you have to do everything over again. And this happened multiple times. Originally I was planning to do this for all 4 Panels (Top, back and both sides) but then I realise it would take forever and wouldn't be worth it so I scrapped that idea. Now that I think about it, I feel like it was a good decision because having a different image on all 4 panels would make the design look over-done and too crowded. The acrylic panels keep it nice and simple and also show the mechanics. Below are a few images of my CAD model (top, side, front and angled views):

![](https://fabricate.hackclub-assets.com/0c3dd8a50ac8f73f2f812cc121aae94e7b091c392298aaef77446e4189add57d/Angled%20View.png)
![](https://fabricate.hackclub-assets.com/0ba94b0efdc72f61de547af487e761ce8d3b8b1eeebfcae69a918bd676f57cb0/Front%20View.png)
![](https://fabricate.hackclub-assets.com/e20e2ec03ce8496d40c6eaa976f0880835705052a98a79ebcb28e2a0c3612525/Side%20View.png)
![](https://fabricate.hackclub-assets.com/6e82262b62669ff24e451ede669456da38bc1a30e2126ee2b18977560d29f88f/Top%20View.png)

**Total time spent: 20h**

# October 8, 2026: BOM and Repository

I completed a prepare BOM for the 3D printer and uploaded all the files onto my github repository. This took a lot more time than I expected because of two main reasons. One, it was my first time using github and two, I overestimated the budget. A lot of my files were over 100mb so I couldn't upload them directly nor could i use github desktop. I had to use LFS and that took forever to figure out. And like I said before, I don't know much about 3D printers and coding so I didn't realise that I don't have to code the firmware. I can use firmware like MainsailOS that already exists. In addition, I can download them directly onto my raspberry pi, on Raspberry imager, I don't have to download it onto my laptop and upload it. That's why I didn't add a file for my firmware on my repository. So figuring all that out took a lot of time. Secondly, I over estimated my budget as I said before. Because of that, I kept adding items but when I calculated the total cost, it was over a 1000 AUD! So then I had to go through my entire list and source cheaper retailers. So that also took forever. But eventually I was able to finish the BOM and my repository. Images below:

![](https://fabricate.hackclub-assets.com/d6e6c97b6cced3e8f6ab9ea4352e4f88af1cc65a00debccd3475ba5b739738e6/image-png/Screenshot%202026-10-06%20at%2010.56.31%E2%80%AFpm.png)
![](https://fabricate.hackclub-assets.com/9e6e419679a7f57bf97c327998dbc420af6981f65e420054d4c014ff4dfba1c0/image-png/Screenshot%202026-10-08%20at%203.21.41%E2%80%AFpm.png)

**Total time spent: 8h**

