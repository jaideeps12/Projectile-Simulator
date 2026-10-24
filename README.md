# Projectile Lab: 3D Physics Simulator

A Python project exploring projectile motion through mathematical modelling and 3D animation.

## About the Project

I originally created a basic projectile trajectory plotter during the summer using Python and Matplotlib. It calculated horizontal distance and vertical height for different launch angles and displayed the resulting trajectories.

I have since updated the project into a 3D animated simulator to explore projectile motion in a more visual and interactive way.

This project is part of my learning journey in programming, computational physics, and scientific visualization.

## Features

- 3D animated projectile trajectories
- Adjustable initial speed, elevation angle, and direction angle
- Calculation of flight time, maximum height, and horizontal range
- Visual trajectory trails and a moving projectile marker
- Live display of time, height, and horizontal distance

## Physics Behind the Simulation

The simulator models projectile motion using the equations of motion under constant gravitational acceleration.

The initial velocity is resolved into three components:

- Horizontal X component
- Horizontal Y component
- Vertical Z component

The model assumes flat ground, equal launch and landing heights, constant gravity, and no air resistance.

## Technologies Used

- Python
- NumPy
- Matplotlib
- Matplotlib Animation and 3D plotting

## Learning and Development

I developed the original version myself during the summer and later used a chatbot as a learning aid to understand the physics, improve the code structure, and explore how to implement 3D visualization and animation.

I am continuing to learn how the mathematical model translates into code and how the simulation can be improved further.

## How to Run

Install the required libraries:

```bash
python -m pip install numpy matplotlib
```

Run the simulator:

```bash
python projectile_lab_3d.py
```

Replace the filename above if your Python file has a different name.

## Future Improvements

- Introduce air resistance into the physics model
- Compare ideal and drag-affected trajectories
- Add interactive controls for simulation parameters
- Validate simulation results against analytical calculations

## Purpose

This project combines my interests in computer science and physics. My goal is to keep improving it while developing a deeper understanding of scientific programming and computational modelling.
