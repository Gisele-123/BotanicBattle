# **Python Version: Botanic Battle**  
A simple **Plants vs. Zombies** game.  



## **Implemented Features**  
### **Available Plants:**  
Sunflower, Peashooter, Wall-nut, Snow Peashooter, Cherry Bomb, Threepeater, Chomper, Puff-shroom, Potato Mine, Spikeweed, Scaredy-shroom, Squash, Jalapeno, Sun-shroom, Ice-shroom, Hypno-shroom.  

### **Available Zombies:**  
Regular Zombie, Flag Zombie, Conehead Zombie, Buckethead Zombie, Newspaper Zombie.  

### **Game Mechanics:**  
- Uses **JSON** files to store progress data (e.g., zombie spawn positions, timing, and background info).  
- Allows **plant card selection** at the beginning of each level.  
- Supports **multiple game modes**:  
  - **Day Mode**  
  - **Night Mode**  
  - **Moving Conveyor Belt Mode**  
  - **Wall-nut Bowling Mode**  

## **System Requirements**  
- **Python 3.7** (Recommended but not required)  
  - **For Linux Users**: If your system comes with **Python 3+ pre-installed**, the game should run fine. However, directly upgrading to **Python 3.7** on Linux Mint may cause issues with system dependencies.  
- **Python-Pygame 1.9**  

## **How to Start the Game**  
```sh
$ python main.py
```  

## **How to Play**  
- Use the **mouse** to **collect sunlight**, **select plant cards**, and **place plants**.  
- You can set the **starting level** by modifying the `START_LEVEL_NUM` value in `source/constants.py`:  
  - **Level 1 & 2:** Day Mode  
  - **Level 3:** Night Mode  
  - **Level 4:** Moving Conveyor Belt Mode  
  - **Level 5:** Wall-nut Bowling Mode  

## **Screenshots**  
![Screenshot 1](https://raw.githubusercontent.com/marblexu/PythonPlantsVsZombies/master/demo/demo1.jpg)  
![Screenshot 2](https://raw.githubusercontent.com/marblexu/PythonPlantsVsZombies/master/demo/demo2.jpg)  
![Screenshot 3](https://raw.githubusercontent.com/marblexu/PythonPlantsVsZombies/master/demo/demo3.jpg)  