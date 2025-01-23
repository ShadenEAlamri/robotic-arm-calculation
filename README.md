# robotic-arm-calculation
To calculate the required torque for each motor in a robot arm, you follow these steps:

### 1. Determine the Torque Required at Each Joint:
- Total weight = 1 kg
- Arm Dimensions:
  - Upper arm: 10 cm
  - Lower arm: 15 cm
  - Distance from joint to center of weight = 4 cm

# Torque Equation:
tau = r x F
where:
- tau is the torque.
- r is the distance (lever arm).
- F is the force due to weight.

# Calculate Force:
F = m x g 
where:
- m = 1  kg (weight).
- g = 9.81 m/s² (acceleration due to gravity).

# 2. Calculate Torque for Each Joint:

- Joint 1 (Upper Arm):
  - r = 10 cm = 0.1 m
  - F = 1 x 9.81 = 9.81 Newtons
  - tau_1 = 0.1 x 9.81 = 0.981 Newton.m

- Joint 2 (Lower Arm):
  -  r = 15  cm = 0.15 m
  -  F = 1 x 9.81 = 9.81 Newtons
  - tau_2 = 0.15 x 9.81 = 1.4715 Newton.m

# 3. Select Suitable Servo Motors:

To select a servo motor the torque must exceeds the required torque:

- For Joint 1: The motor torque should be greater than 0.981 Newton.m.(ranging from 1-2 Newton.m.)
- For Joint 2: The motor torque should be greater than 1.4715 Newton.m.(ranging from 2-3 Newton.m.)



