# Vanta Mk.I by Joshua aka Controw_
Created 5/20/25

~ 70 hours

## 5/24/25 Start cad and deciding on components 
 11:04am - 9:48pm 10 hours and 44 minutes 
 
 ### Control Board
- I chose the BTT Manta E3EZ as the main controller board since setup is straightforward, and the fact that it allows the installation of a compute module that supports use of Klipper as the printing software (which I want to use.) Thankfully, it includes native support for dual Z motors- good for improving bed leveling precision in this build. I considered other boards, but the E3EZ's plug-and-play layout and expandability made it a preferable fit. Looking forward to testing its CAN bus support down the line if I add toolhead mods
  
 ![image](https://github.com/user-attachments/assets/104b4016-269a-4e1b-8348-7e780de05468)

  
### Motors
- For the motors, I chose the StepperOnline NEMA 17 stepper motors with 0.9° step angle. High-resolution movement ensures accurate articulation and positioning. Chose standard NEMA 17 motors with 1.8° step angle for the Z-axis since precision is less critical there and for less cost

### Extruder
- For the extruder, I chose the Orbiter V2 kit from Triangle-lab (Direct Drive). It has high torque and a compact form, and offers reliable filament control for rather precise printing, especially with flexible or exotic materials. Lightweight planetary gear system minimizes strain on the carriage while maintaining performance

![image](https://github.com/user-attachments/assets/07bd8d8c-aecb-4bc4-bfec-a260c6ce2002)

### Build Plate
- For the build plate, I chose the Anycubic Kobra 3 Build Plate Assembly. Wanted to use an off-the-shelf build plate assembly from an existing printer model to reduce complexity and cost, and I can cut off time from the construction of the full assembly. After comparing several options online, I chose the Kobra 3 plate since I’m happy with the size, cost, and since it's heated


## 5/25/25 Work on cad again and finalizing components

### Z Axis Configuration
- Went with 2 independent Z motors for stability, even motion, and dual Z gives the ability to shift the build plate ever so slightly for tramming

### XY Gantry
- For the XY gantry, I went for linear rods because they are easy, inexpensive, and reliable

### PSU
- For the PSU I went with a basic 24V 20A 480W Because of its versatility

 12:37PM to 3:12AM 14 hours 35 minutes 

cad at end of day 2

![image](https://github.com/user-attachments/assets/8e7646f1-fcd5-4da5-959e-c68dcf80a550) 

## Start of day 3 5/26/25 working on cad a bit more
 12:52 PM - 5:36 PM 4 hours 44 minutes
- Got the general place for the z axis motors and lead screws 
- Mounted rails to motion arm

Cad at end of day 3 

![image](https://github.com/user-attachments/assets/0ba0139a-3437-4226-acea-aa4e997f04ed)

## Start of Day 4 5/27/25 Making a parts list and mounting second SCARA motor
9:34 PM - 11:42 PM 3 hours 8 minutes

[Parts List](https://github.com/K73T-T/Vanta-MK.I/blob/main/Parts%20list.md)

Mounted second motor 

![image](https://github.com/user-attachments/assets/b7da0158-a4f8-48d1-ae84-e2e315986f14)

## Day 5 5/28/25 
8:46 PM - 11:12 PM

Adjusted clearence for first motor mount so the belt does not clip into it

![clip no yes](https://github.com/user-attachments/assets/99e0faef-5eaa-4cc0-afc2-3fd0d8358593)

[Found wiring diagram for BIQU Manta e3ez](https://os.ratrig.com/docs/boards/btt/manta-e3ez/) [another one](https://cdn.shopify.com/s/files/1/1619/4791/files/E3EZ_1200x.png?v=1700039972)

Mounted the control board (14 minutes)

![image](https://github.com/user-attachments/assets/b5fe10d3-dd9d-49cd-bb22-27a299731e3c)

Mounted PSU (46 minutes)

Added mount for power switch (33 Minutes)

![image](https://github.com/user-attachments/assets/6b3ca01a-b613-467e-8cec-470e8312a775)

Finalized z axis motor positions, will make mounts tomorrow
 
Cad at end of day 5

![image](https://github.com/user-attachments/assets/22d49697-b906-4fc7-be20-7f0098709b79)

## Day 6 5/30/25 

Made A bill of materials
4:36 PM - 7:02 PM 

## Day 7 5/31/25 More cad

Mounted both z axis motors - 46 Minutes

![image](https://github.com/user-attachments/assets/1a4c9fea-3753-4662-85b0-32e1edee57e4)

Moved control board for better accessibility - 13 minutes

![image](https://github.com/user-attachments/assets/b44285db-c9a5-4855-9c27-bc5dfb4da10d)

I realized that the second arm was not possible to cnc so i optimized it for subtractive manufacturing - 1 hour 33 minutes

![image](https://github.com/user-attachments/assets/1f250a2d-2dec-444e-ae18-60ff970de816)

after making a mount for the extruder and hot end it removed over 100mm of usable z aixs build volume so i made the disicion to increase the hight of the printer by 100m by changing the 2020 extrusions from 500 to 600 mm and the 10x450 mm rods to 10x550mm rods - 11:35 PM - 1:59 AM 2 hours 24 minutes

![image](https://github.com/user-attachments/assets/5264fdcd-dabd-4d8d-9218-680cdc80b4c6)

![image](https://github.com/user-attachments/assets/35c56497-5322-4b0a-b7f7-5de7746e4cb5)

made feet for the bottem of the printer 47 minutes

I modeled them after the feet for the Anycubic kobra 2 Neo because I already have a set of them since I swaped them out for taller ones on my kobra 2 neo

![image](https://github.com/user-attachments/assets/f8e41873-4fe0-4045-b288-2e3f48937b83)

## Day 8 6/3/25 

Worked out the resolution of the printer was ~0.21 mm and i was dissatisfied with this so i did some research and found [this video by Unnecessary Automation on youtube](https://www.youtube.com/watch?v=52_t2FcqHOs) of them making a strain wave gearbox to increse the resolution of a nema 17 stepper motor and found that they published the files on [printables](https://www.printables.com/model/1098371-strain-wave-gearbox/files) so i modified them a bit to work better for my application, and found that after the addition of this gearbox it greatly improved the resolution from ~0.21mm to ~10-20 microns (0.01 - 0.02 mm) without microstepping and with a microstep of 1/2 it brings the resolution down to sub 10 micron accuracy which is much much better than before (~21x better) with the only real downside being the theoretical speed of the printer will be greatly lowered (time spent ~ 2 hours)

![image](https://github.com/user-attachments/assets/7a11c302-c3a0-4ffb-b88d-6d3e6c67e94a)

## Day 9 6/4/25 

Made a simple external spool roller (45 Minutes)

![image](https://github.com/user-attachments/assets/02a4a283-034b-4349-822f-0d29168ae329)

Added a PTFE tube mounting point to for a PTFE tube to go from the frame to the extruder (22 Minutes)

![image](https://github.com/user-attachments/assets/bdc7b033-5deb-4bea-b1b5-b15d14c430b5)

## Day 10 6/8/25

Made use of the extra 200mm of 2020 extursion by adding a support to the front two frame rods (23 Minutes)

![image](https://github.com/user-attachments/assets/811b9d6f-91d0-4a80-9864-c1734afa2ad8)

Added suport arms to the rear 2 frame rods (34 minutes)

![image](https://github.com/user-attachments/assets/981b5d27-03d6-44b1-80dc-6f5ee2fd174e)

Mounted limit switches (20 minutes)

![image](https://github.com/user-attachments/assets/e0b35399-64e7-49dc-ad3d-0ff047918941)
![image](https://github.com/user-attachments/assets/ee25fc10-637b-4f31-9b67-870790f89a2f)

Lightend the build plate mount (30 minutes)

![image](https://github.com/user-attachments/assets/b75d2d45-9ac2-45da-8614-0f1339ccf9ac)

## Day 11 6/11/25

After some feedback I have decied to change the frame to use 2020 extrusions instead of the 10mm rods to increase stabity  (2 Hours)

![image](https://github.com/user-attachments/assets/95a94ac4-728b-4cd0-a277-ec17bbb38e87)

## Day 12 6/12/25

Added two more 2020 extrusions to the top and moved the PTFE tube fitting (30 minutes)

![image](https://github.com/user-attachments/assets/fd705aae-5d44-4299-b68e-b0defe60ab57)

## Day 13 6/13/25

Added linear rails for the build plate to make it more stable (1.5 hours)

![image](https://github.com/user-attachments/assets/b3114787-e38c-41d9-9dca-63ca480827fb)

## Day 14 6/16/25

Moved limit swtiches because the way they were before would not work for a SCARA system (25 Minutes)

![image](https://github.com/user-attachments/assets/95642553-bf55-4235-9a9a-70c76c5141b7)

## Day 15 6/26/25 

Found that my FRC Team had quite a few 2020 and 2040 extrusions that they had no use for so I was able to use them for my printer instead of having to buy them, which saved me over $80.

![image](https://github.com/user-attachments/assets/11006645-8945-4faa-be9f-27344316a79b)


Started cutting out 2020 extrusions and will cut the rest on Monday (30 mintues)
![image](https://github.com/user-attachments/assets/8a3304ba-6caa-43c7-acde-48e5bab6b2b8)




