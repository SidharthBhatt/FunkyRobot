I designed the chassis with Onshape and 3d printed it at home. After, several iterations I had minimized the robot's footprint and maximized space for electronics. 

Onshape: https://cad.onshape.com/documents/a9824bbfdd060f6b1b0a735a/w/9a609be5ec08fa04e5a09f19/e/9d9f4e09387bd903938f9d47?renderMode=0&uiState=6664e0d098a26519e4ec676d


![image](https://github.com/SidharthBhatt/FunkyRobot/assets/81537231/ccc2e4ef-2a1e-49e9-b555-b97fc364e199)

The electronics consisted of a Arduino uno, TB6612FNG motor driver, and Polulu Microgear motors with encoders. The l298n motor driver is most commonly used, however its only ~60% efficient. One the other hand, the TB6612FNG is ~90% because it has Mofset switches, however there wasn't too much information online. Soldering was necessary to connect the header pins to many of the PCBS and connect jumper wires together. In order for the robot to go straight, I programmed and tuned a PI loop. 
![image](https://github.com/SidharthBhatt/FunkyRobot/assets/81537231/6e7897f0-3b1b-4720-9a32-83fc82fbf71a)

