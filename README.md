# DC Motor Modeling and Simulation

This project focuses on modeling and simulating a **shunt-excited DC motor** using MATLAB/Simulink. It demonstrates the steady-state and transient operations, including starting, braking, loading, and unloading conditions. The project includes MATLAB files, Simulink models, and documentation for a comprehensive understanding of the motor's dynamics.

## Features
- **Electrical and Mechanical Modeling**: Incorporates both electrical and mechanical equations for accurate simulation.
- **Parameter-Based Design**: Uses realistic motor parameters for modeling.
- **Transient and Steady-State Analysis**: Simulates key motor operations such as start-up, load changes, and braking.
- **Clear Documentation**: Includes a detailed explanation of the theory, equations, and implementation.

## Motor Parameters
The following parameters are used for the motor:
- Armature resistance ( \(R_a\)): 0.6 Ω
- Armature inductance ( \(L_a\)): 12 mH
- Field resistance ( \(R_f\)): 240 Ω
- Field inductance ( \(L_f\)): 120 H
- Mutual inductance ( \(L_af\)): 1.8 H
- Input voltage ( \(V_a\)): 240 V
- Rated speed: 1220 RPM
- Rated torque: 29.2 N·m
- Inertia ( \(J_m\)): 1 kg·m²
- Damping coefficient ( \(B_m\)): 0 (ideal case)

## Contents
The repository includes:
- **MATLAB Files**: Functions and scripts for simulating the motor.
- **Simulink Model**: Graphical representation of the motor equations.
- **Documentation**: A PDF detailing the equations, parameters, and simulation results.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dc-motor-model.git
   ```
2. Open MATLAB and navigate to the project folder.
3. Open the Simulink model file (`DC_Motor_Model.slx`).
4. Run the simulation and observe the results.

## Requirements
- MATLAB (R2020a or later)
- Simulink

## How to Cite
If you use this project in your work, please consider citing it:
```
@project{dc_motor_model,
  title={DC Motor Modeling and Simulation},
  author={Your Name},
  year={2025},
  url={https://github.com/your-username/dc-motor-model}
}
```

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

Feel free to contribute to this project by submitting issues or pull requests!
