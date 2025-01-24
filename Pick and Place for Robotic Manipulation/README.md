# CS549 - Fall 2024 Project

**TAMP For Sequential Robotic Manipulation in Table Cleaning Enviroment**

This repository contains the implementation of tasks as part of the CS549 Fall 2024 Project. The project includes code for High-Level Symbolic Planning and Low-Level Motion Planning using Bi-RRT, RRT* and PsBi-RRT. 
**Group Members**:

- Kousar Kousar
- Aqsa Shabbir
- Kerem Bayramoğlu

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [High-Level Planning with PDDL](#High-LevelPlanningwithPDDL)
  - [Motion Planning with Bi-RRT](#MotionPlanningwithBi-RRT)
  - [Motion Planning with RRT*](#MotionPlanningwithRRT*)
  - [Motion Planning with PsBi-RRT](#MotionPlanningwithPsBi-RRT)
- [Enviroment](#Enviroment)
  - [Table Cleanning Enviroment](#Table_Cleanning_Enviroment)

## Installation

To set up the environment, install the necessary dependencies as specified below:

```bash
pip3 install robotic unified-planning numpy matplotlib
```

## Usage

### High-Level Planning with PDDL

The high-level task planning module implements the table-cleaning task using PDDL. The steps to run the symbolic planner are as follows:

Steps:

1. Ensure the environment file task.g is in the specified path.
2. Run the PDDL planning code to generate a high-level plan for the task.

The planner will generate a sequential plan for pick-and-place operations and table cleaning based on the defined goals and initial state.
<!--

````bash
# Apply
python3 High Level Symbolic Plan.ipynb
``` -->

### Motion Planning with Bi-RRT, RRT*, PsBi-RRT
The low-level motion planning module implements Bi-RRT, RRT* and PsBi-RRT for path planning and trajectory execution. It ensures collision-free movements for pick-and-place tasks in a table-cleaning environment.

Steps:

1. Run the motion planning code.
2. The code integrates PPDL for sequential robotic manipulation and uses Bi-RRT, RRT* and PsBi-RRT to validate and refine the paths.
<!--

````bash
# Apply
python3 TAMP Implementation using RRT_Star.ipynb
``` -->

### Enviroment

Table Cleaning Enviroment is designed in task.g file. 
