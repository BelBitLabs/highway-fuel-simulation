/# How Markdown Works:
*Custom code = tells the computer what to do
*Comments in said code = tells other programmers/developers how the code is working
*README.md =  tells any reader/viewer (recruiter, teammate, professor, employer) what the whole project is about, 
              what the project matters, how to use this project, and what it accomplishes. 
## README.md = Markdown (the current Github file that we're on now)
*This file is not code, and so its not be compiled or executed like a programming language such as C++ would be. Instead 
 it is written in Markdown, which is a lightweight formatting language that is used specifically for documentation.
*On GitHub, Markdown tells the system how to display text nicely on the repository (repo) page.
## Basic Layout (How to format text in Markdown):
* # = Heading 1 (Biggest, like a title)
* ## = Heading 2 (Slightly smaller, like a subtitle)
* ### = Heading 3 (Even smaller)
### Different Sections: (How to structure text in Markdown to clearly expalin a project or program)
*Project Title = A short, descriptive title for a project
*Overview = Brief summary of what the program does and the problem it solves.
*Features = Tells the viewer the main things your program is capable of doing, listed in short, clear bullet points
*Technologies Used = lists the programming languages, tools, and frameworks you used to build the project 
                    (its lets the reader know which technical skills you were actually able to practice, which is how you made the program,
                     not just what it does)
*How To Run = gives step-by-step instructions to any viewer (like a recruiter, professor, or another developer) 
              on how to download your code and run it on their own computer. It makes your program look actually usable,
              and not just sitting code on GitHub.
              
              A repo = short for “repository” → basically your project folder on GitHub.
              To clone = make a copy of that repo from GitHub onto someone’s computer. (Download a full copy of the project (code, files, history) from GitHub onto your own computer so you can use or edit it.)
              Cloning makes your repo a real, usable project — not just code on a webpage. Employers might not run every project, but they’ll respect that they can.
/(for my personal understanding, so others can ignore)
____________________________________________________________________________________________ Real Markdown Starts Below! Visual Studio Code, Eclipse, IntelliJ, or CLion

# Project Title: 
Highway Fuel Economy Driving Simulation (C++)

## Overview:   
This project simulates highway driving conditions in order to test and analyze vehicle emissions and fuel economy or effeciency.
The program processes input velocity data and applies multiple numerical methods to calculate and compare results, 
which provides insight into vehicle performance under different conditions.
(Lamen Terms: This project analyzes highway driving in order to study and measure the amount of pollution a vehicle transmits and gas that it uses. 
              This program mainly takes in velocity data under different driving conditions by applying several calcualtion/numerical methods, 
              and then finally compares those results under each conditon the car was tested under.)

## Features: 
- Reads in velocity/time data and processes it using C++
- Implements **Forward Difference** and **Central Difference** formulas
- Uses **Simpson’s Rule** and **Trapezoidal Rule** to calculate distance traveled
- Calculates percent difference between methods for accuracy comparison
- Outputs results and plots graphs for visualization

## Technologies Used:
-Languages: C++ 
-IDEs: DEV C++ or Visual Studio
-Tools: GitHub (version control)
-Conceptual/Numerical Methods: Simpson’s Rule, Trapezoidal Rule, Forward Difference, Central Difference

## How To Run:
1. Clone this repo:  
   git clone git@github.com:MPaillant7/Dynamics-Problem-1.1---Project.git
2. Open the project in an IDE (such as DEV C++ or Visual Studio).
3. Compile the program.
4. Run the executable file to see the output.












