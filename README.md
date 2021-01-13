# Master-Thesis
Framework for automatic human and object annotation from the scene in the form of 3D Pointcloud

**Note: There is no coding in this repo since I was not allowed to showcase my code. This will only include the overview of my project with the complete workflow.** 
      
 **After designing the framework, I also prepare labeled dataset of 3D pointcloud (human and other object class) and then trained a 3D classifier after that, deploy it for realtime testing** 
 
- The task was to design a framework that will take the streams of 2D images with their corresponding depth information. The framework will perform automatic human and object annotation in the form of 3D pointcloud from the scene. 

- The framework was designed to work in the industrial environment whereas, industrial environment is different from normal environment. Different lighting condition, presence of robot, different obstacls, reflections, asymmetric backgrounds etc.

Framework is based on C++ and the following libraries I used:

- OpenCV 3.4.3 (for 2D image processing)

- PCL 1.8 (for 3D pointcloud processing)

**Framework design**

![](Images/workflow.JPG)

- This whole process was a part of a giant project in the step of Industry automization. 

- Main target was to detect the human in the scene. since the end goal is to train the AI algorithm that will detect the human in the scene(3D pointcloud) and localize it so that   it can behave according to its position. If the human is in the range where is can collide with robot if the robot move in that direction then robot will behave according to       define rule. 

- The future steps of this project was to make robot able to not just human detection but also to identify human limbs so that it can interect with human in the production           sector. Thats why human localisation was important.
 
