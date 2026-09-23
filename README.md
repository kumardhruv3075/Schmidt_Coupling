# Schmidt_Coupling Mechanism
Schmidt Coupling Mechanism — Design and Analysis

A mechanical design project focused on the 3D modeling, assembly, kinematic simulation, and structural analysis of a Schmidt Coupling using Autodesk Fusion 360. The project demonstrates how a Schmidt Coupling can transmit torque between parallel shafts with variable lateral offset while maintaining constant angular velocity.

📌 Project Overview

A Schmidt Coupling is a flexible shaft coupling designed to transmit torque between two parallel shafts having a variable offset while maintaining a constant angular velocity.

The mechanism uses a three-disk arrangement and linkage system to accommodate lateral shaft offset without introducing speed variation or backlash.

Project Objectives
Design the Schmidt Coupling in Autodesk Fusion 360.
Develop a fully constrained 3D assembly.
Simulate the mechanism's rotational motion.
Validate the constant-velocity transmission.
Perform static stress analysis using FEA.
Evaluate the structural safety of the coupling.
Understand its applications in precision industrial machinery.
🛠️ Software & Tools
Autodesk Fusion 360
3D CAD Modeling
Parametric Design
Assembly & Joints
Motion Study
Finite Element Analysis (FEA)
⚙️ Design Methodology

The coupling was developed using a structured parametric modeling workflow in Fusion 360.

Design Workflow
2D Sketches
     ↓
3D Part Modeling
     ↓
Parametric Features
     ↓
Assembly
     ↓
Joints & Constraints
     ↓
Motion Study
     ↓
Static FEA
     ↓
Design Validation
1. Sketching

2D sketches were created to define the geometry of the disks and linkage components.

2. 3D Modeling

The individual components were converted into 3D solids using extrusion and other modeling features.

3. Assembly

The individual components were assembled using appropriate rigid and revolute constraints.

4. Parametric Design

Parametric constraints and As-Built Joints were used to allow design modifications and accurate motion simulation.

🔩 Mechanism Components

The Schmidt Coupling consists primarily of:

Three-Disk Arrangement

The mechanism contains:

Input disk
Floating intermediate disk
Output disk

The three disks remain parallel during operation.

Linkages & Pins

Four hardened steel pins connect the disks through rigid linkages. These linkages form the parallelogram mechanism responsible for transferring motion.

Needle Bearings

Needle roller bearings are provided at the pin joints to reduce friction and wear during operation.

🔄 Working Principle

The coupling operates using a parallelogram linkage formed by pins and linkages connecting the three disks.

When the input shaft rotates:

The input disk rotates.
The linkage system transfers the motion to the floating disk.
The intermediate disk follows a circular path.
The output disk receives the transmitted motion.
The mechanism accommodates lateral shaft offset.
The input and output shafts maintain the same rotational speed.
Input Shaft
     │
     ▼
Input Disk
     │
     ▼
Linkage + Pins
     │
     ▼
Floating Intermediate Disk
     │
     ▼
Linkage + Pins
     │
     ▼
Output Disk
     │
     ▼
Output Shaft

The project documentation reports that the mechanism maintains a 1:1 speed ratio while accommodating the shaft offset.

📐 Key Design Features
Zero Backlash

Preloaded pin joints are used to minimize clearance and provide accurate motion under reversing torque loads.

High Torque Capacity

The multi-pin arrangement distributes the transmitted load across multiple components.

Compact Design

The axially short configuration allows the coupling to be used in applications where available space is limited.

Constant Velocity

The mechanism is designed to maintain a constant input-to-output speed relationship despite shaft offset.

🧪 Simulation & Analysis

Two major analyses were performed.

1. Motion Study

A 360° rotational drive joint was applied to the input shaft.

The motion study was used to verify:

Rotational motion
Output velocity
Linkage movement
Constant velocity transmission
Positional accuracy

The project documentation reports that the simulation confirmed constant output velocity and no positional error for the modeled mechanism.

2. Static Stress Analysis

Static FEA was performed under the rated torque condition.

The analysis evaluated:

Von Mises stress
Structural strength
Factor of safety
Interference
Binding during offset movement

The documented analysis reports maximum von Mises stress below the yield strength of AISI 1045 steel and a factor of safety greater than 2.0 for the analyzed condition.

🏭 Industrial Applications

The Schmidt Coupling is applicable to machinery where parallel shaft offset and synchronized rotation are required.

Printing Presses

Used for synchronized roller drives where accurate registration and constant speed are important.

Paper Processing

Can connect drive shafts in calendering and coating machinery.

Roll Forming Machines

Can transmit power to forming rolls that may require repositioning.

Textile Machinery

Can be used in looms and winding machines requiring smooth torque transmission at high rotational speeds.
