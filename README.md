# BipedalWalker

  This project is based on Neuroevolution of augmenting topologies (NEAT) algorithm. In brief terms, it uses Genetic Algorithm to evolve the Neural Network to find a NN suitable for the task at hand.
  
  
  ![ezgif com-gif-maker](https://user-images.githubusercontent.com/70597091/154683858-4b30eb98-7da4-4edd-99cf-404298ae2cd8.gif)
  
  # Overview
  
  The input the neural network is an array of data given below <br/>
  
    [hull angle 0
     hull_angularVelocity 
     vel_x 
     vel_y 
     hip_joint_1
     hip_joint_1_speed
     knee_joint_1_angle 
     knee_joint_1_speed
     leg_1_ground_contact
     hip_joint_2_angle
     hip_joint_2_speed	
     knee_joint_2_angle 
     knee_joint_2_speed 
     leg_2_ground_contact_flag]	 
     
  Output of neural network is the torque of each motor.
  
    [Hip_1 (Torque / Velocity)
     Knee_1 (Torque / Velocity)
     Hip_2 (Torque / Velocity)
     Knee_2 (Torque / Velocity)]
     
  By some training the Neural Network evolves to move the robot forward.
  
  # Requirements
  
  This code does not require any specialized GPU device rather it runs solely on CPU. 
  
  1. Python
  2. Jupyter Notebook (Optional; Code can be executed using .py file also)
  3. Open AI Gym
  4. Numpy
  5. Neat-python
  
  # Trying Out
  
  If you just want to see the results of the code, run only last cell with ```#TEST``` comment. Otherwise you can also try to evolve the NN yourself using cell with ```run()``` in it. In all cases, please store ```config-feedforward nn``` in main file directory. You can also try to tweak parameters stated in ```config-feedforward nn``` to get different or better result than me.

