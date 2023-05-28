# EngineRoom
## Virtual Reality Engine Room
The below link is for the final application that was built. However the pictures associated are for the first version. The updated version pictures will be included in this repo. 
Note: the app will work on android phone. It will be available for cross platform including IOS and Oculus.
# Application Page and Download Link
https://adnanaaa.itch.io/vr-engineroom


# Project Summary
![image](https://github.com/adnanO999/EngineRoom/assets/88556508/389b5428-42d2-4394-95fd-1ad5172c2bc3)

This project is the result of my work during the VIP course(Vertically Integrated Project). Throughout this journey I enhanced my skills in C# scripting along with better understanding for the UNITY game engine.
The project is devided into several parts:
* Building the engine and single piston using solidworks.
* Animating the engine and single piston and exporting the animations as fbx
* Creating Unity scenes  
* Setting up the environment that uses GoogleCaedboard
* Creating a usable app

The engine was designed on SolidWorks where I employed my skills in modeling and followed existing models to complete the engine. Moreover animation was done on SolidWorks and imported to unity via external package added to SolidWorks (Simlab FBX exporter)

# Engine and Single Piston Design 
## Engine design
The engine was designed on SolidWorks where I employed my skills in modeling and followed existing models to complete the engine. Moreover animation was done on SolidWorks and imported to unity via external package added to SolidWorks (Simlab FBX exporter)

![image](https://github.com/adnanO999/EngineRoom/assets/88556508/b5487f1e-fe58-47fd-81de-cc84d450d2d9)
![image](https://github.com/adnanO999/EngineRoom/assets/88556508/59c4f1a0-924d-4967-a96d-86b8b230f802)
![image](https://github.com/adnanO999/EngineRoom/assets/88556508/f879acfc-cc71-4b2b-9603-8d17eaf11339)

## Single Piston
The single piston will be used to exolain the four stroke engine. I used an existing model for the single piston however with slight modification for the cam contact. Moreover I created the animation to be consistent with the four stroke engine. This will be explained in the animation section.
![image](https://github.com/adnanO999/EngineRoom/assets/88556508/afdf5177-221e-4719-9714-c82cb6dd35c2)


# Animation
Using Solidworks Basic Motion I animated both the engine and the single piston. This is done by adding the corresponding contact type, gear ratios, and other necessary mates. As we can see below the animation of the single piston was designed to be consistent with the four stroke engine. The animation will be later segmented and played at lower speed to be able to explain and visualize each stroke alone.


https://github.com/adnanO999/EngineRoom/assets/88556508/541e1e9e-778b-4a63-a51b-089275107637


# Creating Unity Scene
To begin with I imported the GoogleCardboard package however DayDream was depricated therefore I tried to modify the implementation in order to obtain a compatible pacjkage with the Unity version that I was using. After setting up the package I created two scenes:
* Main Scene: includes the engine where the user can visualize the different components along with the animation at a variable speed based on user prefernece. Morover engine sound was consistent with the chosen speed.
* The second scene included the single piston where the user is able to select one stroke to visualize its motion along with reading and hearing a synchronized explanatory text and audion

All these functionalities were implemented through scripts. The user can interact with the scene through reticle pointer and teleportation areas. Morover the user has the option to walk when he/she tilts his/her head. This was a script that detects the camera angle and based on certain threshold the player starts to move according to the user head tilting direction.

# Demo
![WhatsApp Image 2023-05-28 at 14 10 28](https://github.com/adnanO999/EngineRoom/assets/88556508/e708a6dd-38e9-4477-871f-7247fa7ec85b)
![image](https://github.com/adnanO999/EngineRoom/assets/88556508/91dfafef-fd4a-44c1-bb56-aef82c126b04)
![image](https://github.com/adnanO999/EngineRoom/assets/88556508/14a0d489-31be-4673-a78f-27876ce9e8a1)
![image](https://github.com/adnanO999/EngineRoom/assets/88556508/b05d9d71-d7c6-4847-a2a7-53581b5062cf)
![image](https://github.com/adnanO999/EngineRoom/assets/88556508/71dba423-bdcd-4dcd-8954-0f6f2f0a006f)

