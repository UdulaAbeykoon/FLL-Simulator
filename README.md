# FLL SIMULATOR
![SimultorDEMOImage](FLLSIMdemogameplay.png)

## 🤖What is FLL Sim?

FLL Sim is a free-to-use application that simulates LEGO robots, enabling students to learn and practice block programming without the need for a physical robot.

## 💻Why I made FLL Sim

This tool was specifically designed to support students participating in the First LEGO League (FLL) competition, offering them a unique opportunity to refine their programming skills in a virtual environment.

By replicating the core functionalities of LEGO robots, the application empowers students to experiment, test, and improve their coding abilities, even during the off-season when access to physical robots might be limited. The platform includes interactive simulations, where there is a demo robot and a practice field where users can program using blocks similar to the EV3 Classroom IDE.

With this tool, my goal was to bridge the gap between theoretical learning and actual hands-on practice.


## ⚒️ How the SIM was made

1.  I developed FLL Sim by first designing realistic 3D models of a LEGO EV3 robot and the competition environment, replicating the field where the robot operates.  I used Onshape to create the robot's skeleton, ensuring accurate dimensions and functionality, and then 
    used Blender to add textures, bringing the models to life with a polished, professional appearance. These detailed models form the foundation of the simulation, ensuring an authentic and immersive experience 
    for users.

2.  To create the programming interface, I utilized Google's open-source library, "Blockly", which allows for the creation of visual, drag-and-drop coding blocks. I customized these blocks to mirror the exact functionality used in real FLL competitions, ensuring the 
    simulation aligns closely with the programming logic students would use on a physical EV3 robot.

3.  Finally, I integrated the custom blocks with the 3D models, enabling users to program the simulated robot directly through an intuitive drag-and-drop interface. This seamless connection allows users to see their code in action as the robot performs tasks on the 
    virtual field, providing an engaging and effective learning platform.

## 🚧 Challenges Faced in Making FLL Sim
Creating FLL Sim was an exciting but challenging journey, filled with technical and design obstacles that required innovative solutions.

The BIGGEST Challenge: Integrating 3D Models with Blockly Code

One of the most significant challenges in creating FLL Sim was connecting the 3D robot model with the block-based code generated by Blockly. This integration required translating the user's drag-and-drop code into precise commands that could control the robot's movements and interactions within the virtual environment.
Initially, I explored various platforms like Unity and Webots to streamline this process, but each came with its limitations, such as performance issues, steep learning curves, or restrictions in customization. After extensive trial and error, I decided to build a custom solution tailored to my vision for the app. This approach allowed me to create a seamless interaction between the Blockly programming interface and the 3D simulation, ensuring a smooth and engaging user experience.
Although it was a demanding process, overcoming this challenge was pivotal in achieving the functional and intuitive application I had envisioned.

## 📈Next Steps
I would like to continue this project to improve user experience and make it easily accessible by deploying the project as a web application. 

