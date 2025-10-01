## Project Title:
# Highway Fuel Economy Driving Simulation (C++)

---
## 📑 Table of Contents:
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run-follow-the-listed-steps-in-chronological-order)
  - [Option 1: Using an IDE](#-option-1-using-an-ide-most-common-for-windows-users)
  - [Option 2: Using the Command Line](#-option-2-using-the-command-line-g-compiler)
- [Credits](#credits)

---
## Overview:
This project simulates highway driving conditions in order to test and analyze vehicle emissions and fuel economy or efficiency. The program processes input velocity data 
and applies multiple numerical methods to calculate and compare results, which provides insight into vehicle performance under different conditions.  

**Simplified Version:**  
This project analyzes highway driving in order to study and measure the amount of pollution a vehicle transmits and gas that it uses. This program analyzes changes in velocity data 
under different driving conditions by applying several calculations/numerical methods, and then finally compares those results under each condition the car was tested under.  

---
## Features:
- Reads in velocity/time data and processes it using C++  
- Implements *Forward Difference* and *Central Difference* formulas  
- Uses *Simpson’s Rule* and *Trapezoidal Rule* to calculate distance traveled  
- Calculates percent difference between methods for accuracy comparison  
- Outputs results and plots graphs for visualization  

---
## Technologies Used:
- **Language**: C++  
- **IDEs**: DEV C++ or Visual Studio  
- **Numerical Methods**: Simple math formulas to estimate acceleration and distance (Forward/Central Difference, Simpson’s Rule, Trapezoidal Rule) 
- **Computational Methods**: C++ implementation, loops & array processing, simple data handling to do calcualtions and plot graphs
- **Conceptual Methods**: Kinematics (velocity–time–acceleration), error analysis, comparison of numerical approaches.
- **Tools/Libraries**: GitHub (version control)  

---
## How to Run: Follow the listed steps in chronological order:  
You can run this C++ program in two different ways:  

---
### 🔹 Option 1: Using an IDE (Most Common for Windows Users):
1.  Clone this repo:  
   ```bash
      git clone git@github.com:MPaillant7/Dynamics-Problem-1.1---Project.git
   ```
  2. Open the repo folder in an IDE (such as DEV C++ or Visual Studio).
  3. Build/compile the program (usually a ▶️ Run or Build button).
  4. Run the program directly from the IDE to see the output in the console and graphs.

---
### 🔹 Option 2: Using the Command Line Interface (CLI) - g++ compiler:
If you have g++ installed (via MinGW, Linux, or macOS t:erminal)...

1. Clone this Repo:
   ```bash
      git clone git@github.com:MPaillant7/Dynamics-Problem-1.1---Project.git
   ```
2. Go into the repo folder:
    ```bash
      cd Dynamics-Problem-1.1---Project
    ```
3. Compile the program:
   ```bash
      g++ Dynamics_Problem_1.cpp -o dynamics
   ```
4. Run the program:
   ```bash
     ./dynamics
   ```
---
## Credits:
This porject was developed as part of Engineering coursework (Spring 2021).

---



   














