# MCFunctions-Power-Tower
Minecraft function that creates a challenging dungeon tower.

*View of the base of the Power Tower*
![power-tower-1](https://cloud.githubusercontent.com/assets/1922739/26525583/52ede67e-4329-11e7-9efd-53040438e9a1.png)

*Looking up at the Power Tower (it's nearly 200 blocks tall!)*
![power-tower-2](https://cloud.githubusercontent.com/assets/1922739/26525584/7ddb5088-4329-11e7-8593-3fa09a4f6698.png)

## What this function does
This MCFunction adds the function command **/function powertower:build** to your Minecraft world/server. When this command is run, it builds a huge tower at (X,Y,Z) coordinate (0,60,0). The tower is full of monsters and other dangers. The challenge is to collect the beacons from the tower bosses.

## How to install and use
Copy the *powertower* folder into the *data/functions* folder of your Minecraft server world or game save. Then type in the commands **/reload** and **/function powertower:build** to build the Power Tower. Do not enter the comand more than one (doing so will result in duplicate boss mobs). It is advised that you execute the command while in creative mode as it will teleport the player to the tower location when you run the function.

## License and redistribution
You may use, redistribute, and modify this project and any files contained within. Have fun!

## Developer's notes
The .py python file procudurally generates the .mcfunction file. If you wish to modify this function, you should do so by changing the .py file rather than the .mcfunction file. Traps and some other features are randomized each time the python script is run, thus even without making changes, you can generate a new mcfuntion file that is slightly different.
