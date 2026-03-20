---
layout: post
title: FRC 2022 Robot Design – Rapid React
description:  
    Design and development of a competitive FIRST Robotics Competition (FRC) robot for the 2022 Rapid React challenge. 
    The project focused on the integration of intake, indexing, and shooting mechanisms to achieve consistent and efficient game piece handling. 
    The work involved CAD modeling in SolidWorks, iterative prototyping, subsystem integration, and mechanical optimization under real competition constraints such as limited time, weight restrictions, and robustness requirements.
skills: 
  - CAD Design (SolidWorks)
  - Mechanical Design
  - Robotics (FRC)
  - Systems Integration
  - Rapid Prototyping
  - Mechanism Design
  - Problem Solving
  - Design Iteration

main-image: 
---

---
## Overview

This project was developed as part of the FIRST Robotics Competition (FRC) 2022 challenge, Rapid React.  
The main objective was to design a robot capable of efficiently collecting, transporting, and launching game pieces into a high goal with consistency and speed.

The development process required balancing multiple engineering constraints, including weight, structural integrity, manufacturability, and system reliability under dynamic match conditions.

---

## Problem & Design Approach

{% include youtube-video.html id="LgniEjI9cCM" autoplay="false" %}

The primary engineering challenge was achieving a consistent shooting trajectory while maintaining a fast and reliable intake and indexing system.

Key design considerations included:
- Ball compression and energy transfer consistency
- Minimizing jamming throughout the system
- Structural rigidity under impacts and vibrations
- Efficient packaging of subsystems within limited space

An iterative design approach was implemented, combining CAD modeling, rapid prototyping, and real-world testing to refine subsystem performance.

---

## Full Robot CAD

{% include image-gallery.html images="/project_frc2022/cad1.png, /project_frc2022/cad2.png" height="400" %}

The complete robot was designed in SolidWorks, allowing early validation of spatial constraints, subsystem integration, and assembly feasibility.  
This approach reduced manufacturing errors and improved overall system coherence.

---

## Intake Mechanism

{% include image-gallery.html images="/project_frc2022/intake1.png, /project_frc2022/intake2.png" height="350" %}

The intake system was designed to maximize ball acquisition efficiency while maintaining durability during collisions.

Key features:
- Roller-based intake for continuous operation
- Geometry optimized to guide balls inward
- Compact structure to prevent interference with other subsystems

A major challenge was ensuring reliable intake regardless of ball orientation, which was addressed through roller positioning and compression tuning.

---

## Indexing System

{% include image-gallery.html images="/project_frc2022/indexer.png" height="350" %}

The indexing system controlled the movement of game pieces from the intake to the shooter.

Key considerations:
- Preventing jams under continuous operation
- Maintaining consistent spacing between balls
- Synchronization with shooter speed

Multiple design iterations were required due to early jamming issues, leading to improvements in geometry and flow control.

---

## Shooter Mechanism

{% include image-gallery.html images="/project_frc2022/shooter1.png, /project_frc2022/shooter2.png" height="350" %}

The shooter mechanism was designed to achieve repeatable and accurate shots.

Key engineering aspects:
- Wheel speed optimization for consistent launch velocity
- Controlled ball compression for efficient energy transfer
- Angle adjustment to improve trajectory accuracy

Testing revealed that small variations in compression significantly affected shot consistency, leading to design refinements in wheel spacing and alignment.

---

## Results & Performance

{% include youtube-video.html id="VIDEO_MATCH" autoplay="false" %}

The final system demonstrated:
- Reliable intake under match conditions
- Stable indexing with minimal jamming
- Consistent shooting performance

The robot successfully met competition requirements and maintained robust operation during impacts and extended use.

---

## Lessons Learned

- Iterative prototyping is essential in real-world engineering applications
- Small mechanical tolerances can significantly impact system performance
- Integration between subsystems is often more complex than individual component design
- Designing under constraints enhances practical engineering decision-making

Future improvements would include weight optimization and enhanced control over shooting trajectory.

---
