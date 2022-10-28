# MinePath
A Minecraft client with built-in pathfinding.  
![Alt Text](https://github.com/KaiSomething/MinePath/blob/main/images/demo.gif)

### Installation
Create a new folder in `.minecraft/versions`. Drag the `MinePath.jar` and `MinePath.json` files into the folder.  
Create a new installation in the Minecraft launcher and you're done!

### Usage  
Use the command `.path {x} {y} {z}`  
But be careful! If you give the client an unreachable destination it **WILL CRASH** (this includes destinations outside render distance).  
Do I plan on fixing this? No. I made this a long time ago and I dont care enough to fix it.

### How it works
This project uses my own implementation of the A* pathfinding algorithme but in 3D.
