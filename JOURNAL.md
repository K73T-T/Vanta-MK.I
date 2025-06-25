# Vanta Mk.I by Joshua aka Controw_

5/24/25 Start cad and deciding on components 
 11:04am - 9:48pm 10 hours and 44 minutes 
- for the controller I decided to go with the BTT Manta E3EZ since it is easy to setup and it has ports for dual Z motors
- for motors I decied to go with stepperonline Nema 17 0.9 deg step for the arms since they need to be as precise as possible and nema 17 1.8 deg step for the Z axis
- for the extruder I choose the orbiter v2 kit from Triangle-lab as it is a powerfull and reliable direct drive extruder
- for the buildplate I decied that it would be more cost effect and reliable to go with a buildplate assembly from a printer that is already on the market, and after some looking on the internet for a printer with a build plate that is a size that I am happy with I went with the Kobra 3 build plate assembly from Anycubic since it is heated and cost affective
5/25/25 Work on cad again and finalizing components
 12:37PM to 3:12AM 14 hours 35 minutes 

cad at end of day 2

![image](https://github.com/user-attachments/assets/8e7646f1-fcd5-4da5-959e-c68dcf80a550) 

Start of day 3 5/26/25 working on cad a bit more
 12:52 PM - 5:36 PM 4 hours 44 minutes
- got the general place for the z axis motors and lead screws
- mounted rails to motion arm

Cad at end of day 3 

![image](https://github.com/user-attachments/assets/0ba0139a-3437-4226-acea-aa4e997f04ed)

Start of Day 4 5/27/25 Making a parts list and mounting second SCARA motor
9:34 PM - 11:42 PM 3 hours 8 minutes

[Parts List](https://github.com/K73T-T/Vanta-MK.I/blob/main/Parts%20list.md)

Mounted second motor 

![image](https://github.com/user-attachments/assets/b7da0158-a4f8-48d1-ae84-e2e315986f14)

Day 5 5/28/25 
8:46 PM - 11:12 PM

Adjusted clearence for first motor mount so the belt does not clip into it

![clip no yes](https://github.com/user-attachments/assets/99e0faef-5eaa-4cc0-afc2-3fd0d8358593)

[Found wiring diagram for BIQU Manta e3ez](https://os.ratrig.com/docs/boards/btt/manta-e3ez/) [another one](https://cdn.shopify.com/s/files/1/1619/4791/files/E3EZ_1200x.png?v=1700039972)

Mounted the control board (14 minutes)

![image](https://github.com/user-attachments/assets/b5fe10d3-dd9d-49cd-bb22-27a299731e3c)

Mounted PSU (46 minutes)

Added mount for power switch (33 Minutes)

![image](https://github.com/user-attachments/assets/6b3ca01a-b613-467e-8cec-470e8312a775)

finalized z axis motor positions will make mounts tomorrow
 
Cad at end of day 5

![image](https://github.com/user-attachments/assets/22d49697-b906-4fc7-be20-7f0098709b79)

Day 6 5/30/25 

Made A bill of meterials
4:36 PM - 7:02 PM 

Day 7 5/31/25 More cad

Mounted both z axis motors - 46 Minutes

![image](https://github.com/user-attachments/assets/1a4c9fea-3753-4662-85b0-32e1edee57e4)

Moved control board for better accessibility - 13 minutes

![image](https://github.com/user-attachments/assets/b44285db-c9a5-4855-9c27-bc5dfb4da10d)

I realized that the second arm was not possible to cnc so i optimized it for subtractive manufacturing - 1 hour 33 minutes

![image](https://github.com/user-attachments/assets/1f250a2d-2dec-444e-ae18-60ff970de816)

after making a mount for the extruder and hot end it removed over 100mm of usable z aixs build volume so i made the disicion to incress the hight of the printer by 100m by changging the 2020 extrusions from 500 to 600 mm and the 10x450 mm rods to 10x550mm rods - 11:35 PM - 1:59 AM 2 hours 24 minutes

![image](https://github.com/user-attachments/assets/5264fdcd-dabd-4d8d-9218-680cdc80b4c6)

![image](https://github.com/user-attachments/assets/35c56497-5322-4b0a-b7f7-5de7746e4cb5)

made feet for the bottem of the printer 47 minutes

![image](https://github.com/user-attachments/assets/f8e41873-4fe0-4045-b288-2e3f48937b83)

Day 8 6/3/25 

Worked out the resolution of the printer was ~0.21 mm and i was dissatisfied with this so i did some research and found [this video by Unnecessary Automation on youtube](https://www.youtube.com/watch?v=52_t2FcqHOs) of them making a strain wave gearbox to increse the resolution of a nema 17 stepper motor and found that they published the files on [printables](https://www.printables.com/model/1098371-strain-wave-gearbox/files) so i modified them a bit to work better for my application, and found that after the addition of this gearbox it greatly improved the resolution from ~0.21mm to ~10-20 microns (0.01 - 0.02 mm) without microstepping and with a microstep of 1/2 it brings the resolution down to sub 10 micron accuracy which is much much better than before (~21x better) with the only real downside being the theoretical speed of the printer will be greatly lowered (time spent ~ 2 hours)

![image](https://github.com/user-attachments/assets/7a11c302-c3a0-4ffb-b88d-6d3e6c67e94a)

Day 9 6/4/25 

Made a simple external spool roller (45 Minutes)

![image](https://github.com/user-attachments/assets/02a4a283-034b-4349-822f-0d29168ae329)

Added a PTFE tube mounting point to for a PTFE tube to go from the frame to the extruder (22 Minutes)

![image](https://github.com/user-attachments/assets/bdc7b033-5deb-4bea-b1b5-b15d14c430b5)

Day 10 6/8/25

Made use of the extra 200mm of 2020 extursion by adding a support to the front two frame rods (23 Minutes)

![image](https://github.com/user-attachments/assets/811b9d6f-91d0-4a80-9864-c1734afa2ad8)

Added suport arms to the rear 2 frame rods (34 minutes)

![image](https://github.com/user-attachments/assets/981b5d27-03d6-44b1-80dc-6f5ee2fd174e)

Mounted limit switches (20 minutes)

![image](https://github.com/user-attachments/assets/e0b35399-64e7-49dc-ad3d-0ff047918941)
![image](https://github.com/user-attachments/assets/ee25fc10-637b-4f31-9b67-870790f89a2f)

Lightend the build plate mount (30 minutes)

![image](https://github.com/user-attachments/assets/b75d2d45-9ac2-45da-8614-0f1339ccf9ac)

Day 11 6/11/25

After some feedback I have decied to change the frame to use 2020 extrusions instead of the 10mm rods to increase stabity  (2 Hours)

![image](https://github.com/user-attachments/assets/95a94ac4-728b-4cd0-a277-ec17bbb38e87)

Day 12 6/12/25

Added two more 2020 extrusions to the top and moved the PTFE tube fitting (30 minutes)

![image](https://github.com/user-attachments/assets/fd705aae-5d44-4299-b68e-b0defe60ab57)

Day 13 6/13/25

Added linear rails for the build plate to make it more stable (1.5 hours)

![image](https://github.com/user-attachments/assets/b3114787-e38c-41d9-9dca-63ca480827fb)

Day 14 6/16/25

Moved limit swtiches because the way they were before would not work for a SCARA system (25 Minutes)

![image](https://github.com/user-attachments/assets/95642553-bf55-4235-9a9a-70c76c5141b7)



