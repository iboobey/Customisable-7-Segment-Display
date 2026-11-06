---
title: "Customisable 7-Segment Display"
author: "İboo"
description: "My project is an mechanical 7 segment display that uses a cam system which can be customisable."
created_at: "2026-08-01"
---

# 2026-08-02: Devlog #005

**Total time spent: 8 hour 21 minutes**

[content missing due to database mishap]

# 2026-08-02: DEVLOG #004

**Total time spent: 9 Hour 45 Minutes**

Hi everybody! Hope y'all are alright :)
My last devlog was 4 days ago, since then I worked on an important part of the project. Displaying big numbers that are more than 1 digit. I called the big number system.
___
****Design****
___
As I said I generally worked on the big numbers system but I also designed some more useful things that I will mention right now.

-**Numbers that are more than 1 digit**-

Most of the 7 segment displays use more than 1 motor (a motor per digit) when used dise by side, this looks a lot cleaner as a display, however it makes the total cost and total work a lot more. Because you have to code, connect it to a microcontroller, solder the motors for energy (as far as I know microcontrollers can't supply electricity more than 2 motors simultaneously.)
Some people might not want to do all of this stuff. For them I designed a 10:1 gear ratio with a geneva mechanism. This enables you, to put the displays side by side and only need 1 **-more powerful-** motor. 
This system works for all displays that includes 10 different symbols (numbers) in the cam system. (There is some modification needed if you want to do the same with the displays that include 3,4,5,**6**,7,8 or 9 symbols. I will mention this later in this devlog.)

-**A step towards customisability**-

I designed the 8 different cam shafts that allows the pieces (arcs and curves) to be inserted at the sides, making it customisable. All of these 8 different cam shafts have different number of sides(3,4,5,6,7,8,9,10). So they can be used to limit how many symbols are in the circulation in the display system. For example if you want only the numbers 0,2,5,8 to show up you can use the 4 numbered cam shaft and customise it to show the numbers you want. This gets rid of the need to turn more than 36 degrees (1/10 of the full rotation, the cam shaft number 10 uses this (Cam shaft number 10 is the shaft if you want to use all digits 0-9)) if you want to go from 5 to 8 for example.

I didn't designed the arc and curve pieces yet but they will be my priority in the future.

-**The Clock System**-

You can make the clock system as a big number system using motors (1 per display), but as I said that can bring a lot of work. 
If you don't want to do all of that work, you can make use of the 10:1 gear ratio and a new module that turns the 10:1 gear ratio to 6:1 .
 10:1 gear ratio will be used between, for example, units place of minutes and tens place of the minutes. And the 6:1 gear ration will be used between the seconds and the minutes and between the minutes and the hours.
The 10:1 and 6:1 gear ratios combine to make a 60:1 gear ration that is the exact ratio of the seconds to minutes or minutes to hours.
But with this you also have to change the cam shafts of the tens place of the seconds minutes and hours to cam shaft number 6 , so that they only have digits 0-5.

If this seems like a lot of work yes it is. But i will also make the design of the needed cams for the cam shaft number 6. So you don't have to customise yourself.

-**Last few things**-

I designed a connector to attach more than 1 display side by side.
I also customised the connector to be a colon(:),a dot(.) or a comma(,). You can use these as to represent numbers like 12.35 and 14,85 or hours like 13 : 11.

___
****Future Plans****
___
▪Build it from cardboard
▪Make a servo attachment and the code for the clock system.
▪Make the custom pieces for every shaft.
___
I also want to mention that there will be A LOT of part files for this project, cause every cam shaft requires a different width for the custom pieces.
___

I finally finished writing this devlog. I might speaked a lot more than needed but thats on me sorry :) Also for all the fellow readers that read all of this devlog. Thanks A LOT :):).

Kendinize iyi bakın. See you laterr.
15/07/26
![image.png](https://cdn.hackclub.com/019fc1d7-09cc-7ef5-affa-17599cf6372a/image.png)
![image.png](https://cdn.hackclub.com/019fc1d7-27c9-7b77-9b67-d78aff31a429/image.png)

# 2026-08-02: Devlog #003

**Total time spent: 2 hours**

[content missing due to database mishap]

# 2026-08-02: DEVLOG #002 - More Design Changes

**Total time spent: 7 Hours 30 Minutes**

Hi everybody!
Last 2 days I have spent WAY more time on things than I expected to spent. But, because this project it pretty fun for me, that wasn't really a problem : )

Also I am trying to learn, how to make my devlogs enjoyable to read. If you have any ideas or suggestion for me please dm me or mention it in the discussion ( comments) part of this devlog.

Now I should probably mention what I did :]
___
****Design****
___
As I mentioned on my first devlog, I wanted this display to be 3D-Printable. So I mainly worked on that and a few other things.


**-***Making it 3D printable***-**

Added pins and slots for each of the 7 segments.

Modyfied the shaft that turns the cams, so that it is easier to assemble.

Added a spring system so when the knob is turned for every number the cams click in to the place. (Yes that satisfying * ***********click*********** *)

Adjusted the knob to no need any glue.

**-***Some other few things***-**

Made the shaft that turns the cams a square so that it can rotate the cams without glue(x2).

Made cam spacers to space out the cams and to not need glue(x3).

Made an honeycomb design on two of the faces of the box. This makes it lighter, less materials to print and I also think that it looks cooler.
___
****My plans for the future days****
___
▪Design a banner for the projects stardance page.
▪Make it customisable via some curve and arc pieces
▪Build it from cardboard
▪Make an attachment for the clock (A Geneva mechanism)
▪Make a servo attachment and the code for the clock feature.
___

Yes, this devlog was mainly about not using any glue.
I specifically wanted to resolve this issue, because i don't really want to use anything that is not 3D printable, unless, it is a non negotionable (like servo motors).

Also **please** tell me if I can change anyting about my devlogs to make it more enjoyable.

Görüşmek Üzere. Byeee

11/07/26

![image.png](https://cdn.hackclub.com/019fc1d2-36c5-70c3-bb1e-8bd60387ef25/image.png)
![image.png](https://cdn.hackclub.com/019fc1d2-3a62-745a-8972-4004001e5455/image.png)
![image.png](https://cdn.hackclub.com/019fc1d2-5149-7c03-8946-15b1ac1be537/image.png)
![image.png](https://cdn.hackclub.com/019fc1d2-70a7-78f6-acd0-fe25f822ae6f/image.png)

# 2026-08-02: DEVLOG #001  -  Starting The Main Design

**Total time spent: 5.5 hours**

Hi everybody! Last few days, I have been working on a 7-segment display that uses customisable rotating cams. I found hackclub 3 days ago so I couldn't log all my progress into the system. Because of that I want to give a little journal to adress what I have been working on.
Also I want to mention because this project is "mechanical" I will generally write about the designing, building and trouble shooting phase.
___
July 1 - July 6
___
My first experience with Fusion.
I designed the main system of the 7-segment display (7 segments, rack and pinions , the box and most importantly the base₁₀ cams.)
There were some problems in some of the cams, so I remodeled some of them. And it worked. But due to the Fusion July 2026 update I can't simulate the cams rn on my computer ( It bugged a bit)
___
July 6 - July 9 (Today)
___

I tried for more than 2 hours to solve the issue with Fusion, but sadly, I wasn't successful.

I also designed the rotary knob to control the design. But it might need some adjustments in the future.
___
My plans for the future days
___
▪Make it customisable via some curve and arc pieces

▪Make it 3D printer friendly

▪Build it from cardboard

▪Make an attachment for the clock (A Geneva mechanism)

▪Make a servo attachment and the code for that
___
My current time spent is 1 hour at lapse + ~4.5 hours before learning about lapse.

My project might seem similar to Engineezy's 7-segment display, It's cause thats what gave me the idea of starting this project. 
Altough it might seem similar, the internal mechanism will have some changes. It will be like a modded version even though I don't have the CAD files for his project, I only looked to his videos that is available on his youtube.

09/07/2026

![image.png](https://cdn.hackclub.com/019fc1ca-faf1-7f83-ba24-22b5044db598/image.png)
![image.png](https://cdn.hackclub.com/019fc1cb-1247-7bd7-aa45-4dad64edd4ff/image.png)

# 2026-08-02: DEVLOG #000

**Total time spent: 0 hours**

Hi Guys!! I have been working on an project for more than 1 month. I started this project in Stardance YSWS. But because they are not very hardware friendly, I wanted to migrate my project to here,Forge. I already had 4 devlogs in Stardance, and I will copy-paste them into here.
 -For the Reviewers- 
Don't worry they are all mine.

___
Yes, I know that this devlog is not really about devolopment but I wanted to write it to clarify things. 
___
Also the image that I am putting here will be explained in an upcoming devlog.![image.png](https://cdn.hackclub.com/019fc1c8-1b27-74ae-bf70-55074e5caaa2/image.png)

