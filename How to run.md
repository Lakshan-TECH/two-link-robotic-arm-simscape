# Two-Link Planar Robotic Arm: SolidWorks + Simscape Multibody

A two-link planar robotic arm designed in SolidWorks, exported to
MATLAB Simscape Multibody, and simulated in Simulink with PID control.

## Contents
- Assem1.slx: Simulink model (desired trajectory, inverse kinematics,
  PID controllers, forward kinematics)
- Assem1_DataFile.m, Assem1.xml, Part*.STEP: files exported from SolidWorks
- Robotic_Arm_Paper.pdf: project report

## How to run
1. Open MATLAB and set this folder as the current folder.
2. Run Assem1_DataFile.m
3. Open Assem1.slx and click Run (stop time 10.0)

## Credits
The SolidWorks-to-Simscape workflow follows the tutorial by MT Engineering:
https://youtu.be/pDiwAA1cnb0

Author: Luckshan S.M., University of Moratuwa
