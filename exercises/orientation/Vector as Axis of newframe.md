## Relative orientation of an axis

If we consider a unit vector **n** it can be seen as any axis of a frame in the space. 

Having a reference frame F0 we can usually express the relative orientation between itself and a generic frame attached to the vector n. 

The rotation R01 must be multiplied by the vector **n** and the solution must be equal a vector 3-by-1 with just one component equal to one (all the others are zero) that select which axis of the frame 1 is the vector **n**.

If the angles of the rotation matrix are unknwon this leads to a inverse kinematics problem, an example of solution is <a href='https://github.com/theroggio/Robotics-1-La-Sapienza/blob/master/exercises/inverse%20kinematics/Ex8.md'> here </a>.
