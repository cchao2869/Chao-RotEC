# Soft Robotic End Effector
## Chao - Robot Arm Planning Document, Engineering 3 2023/24

## Introduction
The future of robotics lies in soft grippers inspired by nature. This shift to "soft robotics" allows for a more seamless integration of robots into everyday human activites. Soft robots use flexibile materials that are less dangerous in human-robot interactions compared to the "hard robotics" of the past. This design was inspired by the rise in soft robotics and several bioinspired robot grippers [1]. 

The natural world has evolved over billons of years to create the most effective and veratile ways to grip objects. Natural grippers use three techinques in unison to seamlessly grasp a variety of objects: friction, mechanical interlocking, and adhesion. Friction is fairly intuitive; It is the resistence to motion when two surfaces are in contact. This force increases as the pressure of contact increases. For example, when a human hand grasps a pen, friction between the surface of the pen and the fingers keep the pen from slipping out of the hand. As the hand applies more pressure, the normal force between the hand and pen increases, and thus the friction increases as normal force and friction are directly proportional (F = μs × N). Friction and mechanical interlocking work in tandem. Mechanical interlocking occurs when the physical shapes and structures of appendages interlock with the irregularities of the objects' surface [see Figure 1 and 2]. Mechanical interlocking increases the friction between the two surfaces, because the surface area of contact increases as these structures interlock. Finally, adhesion is the molecular attraction between surfaces, usually by means of Van der Waals forces (temporary dipoles with slight charges between the molecules of the interacting surfaces) [see Figure 3]. Animals that exhibit this gripping mechanism usually do so by an adhesive secretion. For instance, tree frogs release a muscus from their toe pads that form capillary adhesion with the surface they are grasping to [see Figure 4]. Animals with effective grasping techniques use the three gripping mechanisms (friction, mechanical interlocking, and adhesion) in coherence in order to grip effectively. However, most bioinspired robots focus on soley one gripping mechanism or fail to integrate all three effectively. The goal for this project is to use all three of the gripping mechanisms in unison to create an effective bioinspired end effector.

Fig. 1 [2]
![image](https://github.com/cchao2869/Chao-SoftRob/assets/91699474/a3b5420e-0040-47b5-8dec-3befcbc049e3)
Fig. 2 [5]
![Capture](https://github.com/cchao2869/Chao-SoftRob/assets/91699474/33a4dd03-a1c3-4a43-81d1-e9bee91a2b45)
Fig. 3 [2]
![image](https://github.com/cchao2869/Chao-SoftRob/assets/91699474/68dc9c9a-31a1-4a15-9f17-9c2d2d848c65) 
Fig. 4 [2]
![image](https://github.com/cchao2869/Chao-SoftRob/assets/91699474/f2f613ae-36af-4adb-a32e-8efcf71cfac5) 


## Related Works
Soft robotics as well as effective grippers found in the natural world were thouroughly researched prior to the modeling process. 

## Design and Fabrication
While the majority of soft robotics pneumatic, this is not possible with the current supplies available in the Sigma Lab. In order to create a soft robotic end effector, it was determined that a compliant mechanism would be the best way to achieve the design goal. The compliant mechanism was designed using TPU, a more flexible 3-D plastic. Effective grippers also employ  underactuation (i.e., having a higher number of degrees of freedom than the number of actuators), which makes it possible to conform to objects shapes with the constraits to movement [2]. Using underactuation and a compliant mechanism, the design was fabricated in the closed position, and is opened using on actuator that tightens strings connected to each petal. This design has two degrees of freedom (yaw rotation, as it is assumed that the robotic arm will provide pitch and roll, and 

## Conclusion
While the design is still in the prototyping phase, the next steps are to create a more finalized CAD model and make sure the compliant mechanism is opening and closing correctly using the Kevlar string. After the soft gripper is consistently working mechanically, the actuator and code will be completed in order to allow the design to close and open with an input. Additionally, the design will implement sensors in the interior walls of the petals in order to sense when an object is inside so that the gripper will work autonomously. This design version is similar to a Venus flytrap [3], which closes only after an electrical charge is transmitted from the trigger hairs inside its petals. This electricame charge must reach a threshold value in order for the trap to close, which makes the plant work efficiently and not waste energy. The soft robotic end effector will mimic this by only beginning the closing sequence after the sesor has reached a HIGH value twice within a twenty second time period. Finally, the design will be able to rotate in the yaw direction in order to implemet underactuation, seen in nature and most soft robotics. 

## References
[1] “The Soft Grip of Animals Inspires Scientists to Improve Robots.” Wageningen University and Research, Experimental Zoology, 16 Dec. 2020, www.wur.nl/en/newsarticle/the-soft-grip-of-animals-inspires-scientists-to-improve-robots.htm. 

[2] Langowski, J., Dodou, D., Kamperman, M. et al. Tree frog attachment: mechanisms, challenges, and perspectives. Front Zool 15, 32 (2018). https://doi.org/10.1186/s12983-018-0273-x

[3] Shintake, Jun, et al. “Soft Robotic Grippers.” Wiley Online Library, John Wiley & Sons, Inc, 7 May 2018, onlinelibrary.wiley.com/doi/full/10.1002/adma.201707035. 

[4] Volkov, Alexander G et al. “Kinetics and mechanism of Dionaea muscipula trap closing.” Plant physiology vol. 146,2 (2008): 694-702. doi:10.1104/pp.107.108241

[5] Autumn, Keller. “Evidence for Self-Cleaning in Gecko Setae.” ResearchGate, Feb. 2005, www.researchgate.net/publication/8101087_Evidence_for_Self-Cleaning_in_Gecko_Setae. 
