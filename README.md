# Coppeliasim-3-DOF-Robot-
This project uses a 3-DOF robot to practice Modern Robotics basics. I am using 3R Robot.ttt file simulation to test Forward Kinematics (FK), Inverse Kinematics (IK), and robot dynamics. Even though the robot design is simple, it is a great starting point for turning mathematical theories into a working simulation.
Language:Python -
Libraries Used: modern_robotics , numpy -
API:ZMQ API (connect vscode with coppeliasim software)

## Forward Kinematics
In 3DOF Robot.ipynb file, forward kinematics is calculated by Product of Exponential Formula (POE) . We need home configuration of robot (M) , Slist (stores information about all 3 joints ) and theta(angles we entered).
### Jacobian
Uses of Jacobian (Singularity Detection by rank ,Yoshikawa manipulability and condition numbers)
