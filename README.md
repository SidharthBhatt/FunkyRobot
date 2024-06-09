## Background

The objective is to avoid obstacles, go through checkpoints, and reach the endpoint as close to the target time as possible. I have a lot of robotics experience as I have done FTC for four years, however the reason this event was so difficult was the extremely low margin of error necessary to win. The best robots scores differ by mere seconds. 

## Interesting Stuff

I designed the chassis with Onshape and 3d printed it at home. After, several iterations I had minimized the robot's footprint and maximized space for electronics. 

**Onshape:**

https://cad.onshape.com/documents/a9824bbfdd060f6b1b0a735a/w/9a609be5ec08fa04e5a09f19/e/9d9f4e09387bd903938f9d47

![image](https://github.com/SidharthBhatt/FunkyRobot/assets/81537231/f9508c63-3070-4fb0-9c16-6a5ab833f244)


![image](https://github.com/SidharthBhatt/FunkyRobot/assets/81537231/ccc2e4ef-2a1e-49e9-b555-b97fc364e199)

The electronics consisted of a Arduino uno, TB6612FNG motor driver, and Polulu Microgear motors with encoders. The l298n motor driver is most commonly used, however its only ~60% efficient. One the other hand, the TB6612FNG is ~90% because it has Mofset switches, however there wasn't much information online. 
![image](https://github.com/SidharthBhatt/FunkyRobot/assets/81537231/6e7897f0-3b1b-4720-9a32-83fc82fbf71a)

Soldering was necessary to connect the header pins to many of the PCBS and connect jumper wires together. In order for the robot to go straight, I programmed and tuned a PI loop. 
![image](https://github.com/SidharthBhatt/FunkyRobot/assets/81537231/316a73b5-c953-48c9-ad0c-ab714a2a6162)


The code has a lot of comments and has been simplified several times. There are different commands that can be added to the que that are executed when the button is pressed. A PI loop accounts for the difference in the two encoders counts and corrects for it at the end of every command.
# Initial Plan in October
![image](https://github.com/SidharthBhatt/FunkyRobot/assets/81537231/c168ddbd-62e8-43e0-8744-a0ad85098cf9)
![image](https://github.com/SidharthBhatt/FunkyRobot/assets/81537231/4eb1cf6a-e903-4107-a37f-f5921f8a2260)

# First Snapshot in December
yes... don't ask me how but this bundle of wires actually worked (after some extensive troubleshooting)
![image](https://github.com/SidharthBhatt/FunkyRobot/assets/81537231/320ea31f-72af-42c0-8de8-0be1d102e99b)

# Second Snapshot in January 
![image](https://github.com/SidharthBhatt/FunkyRobot/assets/81537231/b127d4b4-33f1-467d-a30b-31f5c5cba6b8)

# Final Product in March (with SO MUCH tuning):
![image](https://github.com/SidharthBhatt/FunkyRobot/assets/81537231/04f54921-7c48-4a8a-9303-f82cfbaafc28)
