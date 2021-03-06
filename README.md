# graspreview

## An object-centric perspective of robotic grasping

1. Introduction
 
	1.1 Brief overview of hand-centric grasping (hand design, hand kinematics, contact model, hand IK, reachability. A large amount of work focus on this part, with the assumption that a better hand will lead to a better grasp.)

	1.2 Introduction of object-centric grasping (force closure, form closure, caging, claim why this perspective is more essential and crucial, why is this important.)
 
	1.3 Core problems of object-centric robotic grasping (multi-contact planning, Compliant interaction, Robust manipulation. With drawings that shows the definition of each problem.)

2. Planning of object-centric grasping 
 
	2.1 Known objects (force-closure, caging, differ in how the grasp candidates are sampled)
 
	2.2 Familiar objects (Learning)
 
	2.3 Unknown objects (Learning)

3. Control interaction of object-centric grasping (The goal is to keep the stabilty of the grasped object.)
 
	3.1 Dynamics of hand-object system
 
	3.2 Learning to stable grasps
 
	3.3 Robust closed-loop execution

4. Control of Constrained Object Manipulation (The goal is to change the configuration of the grasped object, with respect to the hand frame or base frame.)

	4.1 Pushing

	4.2 External force

	4.3 Trajectory Tracking

5. Discussion and Conclusion

	5.1 Still open problems (Perception, especially object segmentation, planning for partial objects, planning with task constraints)

	5.2 Next place to go
