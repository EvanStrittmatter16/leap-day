---
layout: default
---


## About Me

Hi I’m Evan Strittmatter

I am an undergraduate student at Yale University in my Senior year. Ever since I got my hands on my first Arduino I have been passionate about engineering projects. I was in fourth grade, with little understanding of how electricity worked, let alone what a programmable microcontroller was. Yet I was immediately captivated and started working with my mom to make a LED light up. I had no concept then of the thousands of hours I would spend over the next eleven years coding and wiring up increasingly complex creations with this device and others like it. 
At this point I am focused on accumulating a variety of research experience, particularly concerning sensors and robotics, as the next step along an exciting and fulfilling career path.


## Resume
<a href="images/Resume.jpg">My Resume</a>

## Projects

Over the years I've worked on a wide variety of projects. Here are my proudest creations with applications in Robotics.

### Intelligent Autonomy Lab

For the past three semesters, I have been working in the Intelligent Autonomy Lab at Yale, run by Prof. Ian Abraham.

Humans are very good at tactile object identification – for example, you can reach into your pocket and distinguish between your phone, keys, and wallet all without looking. Robots on the other hand struggle with this form of task. My project is to develop a robotic hand and arm which can identify unknown objects through the use of tactile senses. 
The first step to achieve this is to set up a control system for the robot and direct it to pick up a known object. Working with a grad student, Chuck Wher, we have developed a PD control algorithm for the robot, enabling the arm to move to desired locations and grasp. We modeled this in simulation space using the software Mujoco. Check out the simulations I've done of our controller operating the robot.


<div id="wrapper"> 
    <video id="home1" width="290" poster="images/video.jpg" controls="controls autoplay muted" preload="none"> 
        <source type="video/mp4" src="images/RobotHandWave.mp4" /> 
    </video>
    <video id="home2" width="290" poster="images/video.jpg" controls="controls" preload="none"> 
        <source type="video/mp4" src="images/RobotHandGrasp.mp4" /> 
    </video>
    <div class="clear"></div> 
</div> 
  
  
Still working with Chuck wher, we then adapted our controler to a real-life counterpart. With a similar task in mind, we wanted to establish live user control of the robot via a hand held controler. Here is a video demonstrating a basic implementation of this.
 
 <video id="home1" width="580" poster="images/video.jpg" controls="controls autoplay muted" preload="none"> 
      <source type="video/mp4" src="images/Arm.mp4" /> 
  </video>

The next step is improving the control algorithm for the robotic hand in particular. Inorder to achive more complex problem solutions, like object manipulation (especially for unknown objects), a more complex problem formulation and controler is required. An interesting control problem which demonstrates exact motion and timing is music. Here is a video of the robotic hand, again using mujoco to model contacts, with the new control algorithm I developed for it, playing the first nine notes of Für Elise.

<video id="home1" width="290" poster="images/video.jpg" controls="controls autoplay muted" preload="none"> 
      <source type="video/mp4" src="images/Allegro_Control_Piano.mp4" /> 
  </video>

My plan for continuing this project is to implement this new algorithm on a pyhsical system. I also plan to incorperate this with the Robotic arm to reform the combined system.

### Inductance modeling of an IC in COMSOL at EPC

Over the 2022 and 2023 summer, I worked at EPC - a semiconductor company in Los Angeles. 

#### 2022 Summer LiDAR IC inductance modeling
A major application of their transistor parts is in LiDAR as GaN is especially suited for quick switches between forward and reverse biasing. This makes GaN optimal for LiDAR as it means the LED can be activated in high-frequency short bursts, providing accurate readings in quickly adapting environments. EPC sells complete ICs for this circuit, with the limiting factor on the chips being their inductivity. High inductance resists changes in current, even generating a secondary voltage wave in the chip. My job was to model the inductance in the chip in COMSOL to identify regions in the geometry that contribute strongly to the total inductance of the chip in order to find an optimal design. I developed a modeling procedure and tested it on several different designs to provide the team with insights into promising geometry structures. I also developed a method for testing future iterations of device geometry.  

<img src="images/EPC_ModelValidation.png" width="580"/>. 

I can't publish information containing specific part design, but these pictures show models I developed for testing basic properties of a coil. The large picture on the left shows the electric field vectors inside a coil behaving as expected. The two smaller images demonstrate the skin effect - as frequency increases the current crowds closer to the edge of the circular metal conductor.
Applying these same principles to the model allows the user to make intuitive changes to the model to reduce its natural inductance.



### Team Robotics Projects
I've always had a passion for team robotics. I made this video for my application to Yale, which shows off some of these projects.

{% include youtube.html id="FGk78Fa3bWU" %}. 
    

### Publications and Talks

<a href="images/micromachines-13-00141.pdf">A Comparative Analysis of Microelectrode Topologies for Electrochemical Oxygen Sensing in Biomedical Applications</a>
Micromachines 2022, 13(1), 141; https://doi.org/10.3390/mi13010141. 

I also presented a talk on this topic at the MRS spring convention 2022. 


### Comunities I care about

Beyond my own projects, I also care about my impact on my community. I was inspired to pursue a career in robotics by working with and learning from my parents, mentors, and teachers. Their enthusiasm for creative problem-solving, purveyed through all aspects of science and influenced me in a positive way. Realizing this I have worked with several community groups throughout my life to continue this cycle and keep giving forward. 

#### YOSE
The first of such groups was a volunteer organization founded by one of my good friends in high school. The goal: to inspire excitment for fields of science in underprivileged children in the LA area. Volunteers would lead children on short hikes in the Angeles Crest mountain range, or through the tide pools at beaches, imparting both a passion for nature and facts about the local wildlife in the area.

#### Code Haven
I continued volunteering with the same kind of project at Yale. The Club Code Haven has a similar goal: again working with underprivileged kids, now in the New Haven school system, working to inspire interest in Computer Science. Here we volunteered in a classroom, working with small groups of 3-4 students on a guided project in Scratch of their choosing. My group each created a “Space Invaders” clone where they could blast falling asteroids out of the sky. Every Friday we would meet and work on new aspects of the project, starting first with making a custom character, all the way up to object collisions and iterative code. It was gratifying getting to see the kids playing with their own finished creations by the end of the school year. 

#### South Pasadena Tournament of Roses
Another volunteering community I have enjoyed participating in is the South Pasadena Tournament of Roses. This group centers around constructing the South Pasadena (my hometown) City float. Here I’ve gotten to work on my welding skills as well as getting myself and my brother involved in a community of engineers. I really enjoyed getting to work with my brother on such a large-scale project, watching the float drive through Pasadena at the start of the New Year. Pointing out to my family what parts we had worked on was special.


