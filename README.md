# Jgomez2424snhu-CS-330-13521-M01-Comp-Graphic-and-Visualization-2026
##This is the Module 8 submission for CS 330

# CS 330: Computational Graphics and Visualization Portfolio

## Project Overview

This repository contains my final project for CS 330, a 3D desk workspace built with C++ and OpenGL. The scene recreates a stock photograph chosen in Milestone One and contains a textured wood desk, a ceramic mug, a roll of washi tape, a stack of books, and a desk lamp. The objects are built from six basic shapes (plane, cylinder, torus, box, sphere, and cone) and are lit by three light sources that use ambient, diffuse, and specular components. The user can navigate with the W, A, S, D, Q, and E keys, look around with the mouse, change the movement speed with the scroll wheel, and switch between perspective and orthographic views with the P and O keys.

**Files in this repository**

- `7-1_FinalProjectMilestones.zip`: the 3D scene, including the Visual Studio project, the source code, the shaders, the textures, and the built executable.
- `Design Decisions Final.docx`: a written explanation of my development choices, the navigation controls, and the custom functions in the program.

## Reflection

### 1. How do I approach designing software?

This project taught me to design a program around the real-world objects it represents. In Milestone One, I chose a photograph and broke each object into basic shapes before writing any code. That plan gave me a clear target, and it showed me that a convincing scene can come from a few simple parts. Later, I applied the same thinking to the code itself. Instead of drawing every shape from one long function, I created a `SceneObject` class that holds the shapes, transformations, textures, and materials for each object. This design made each object a single unit that is easy to read, adjust, and reuse.

My design process followed the course milestones: I proposed the scene, built one complex object, added navigation, applied textures, added lighting, and then combined and refined everything for the final project. Breaking a large goal into stages that each produce something visible is a tactic I can apply to future work. Planning the structure before coding, grouping related data into classes, and replacing repeated numbers and names with constants will help me write software that other developers can understand and maintain.

### 2. How do I approach developing programs?

On this project, I developed in small steps and tested after each one. I added a single feature, ran the program, and checked the result before moving on. When something went wrong, I treated it as information. For example, a lighting step produced a black screen because the shader used different light variable names than I had assumed. Reading the shader file instead of guessing showed me the cause, and I now check the actual files a project depends on before writing code for them.

Iteration was central to my progress. Each milestone built on the one before it, and feedback on earlier milestones guided my final changes. My instructor recommended encapsulating objects in their own class, using constants, shortening long functions, logging camera controls, and checking whether textures load successfully. I applied each suggestion, and the final program prints the controls to the console, warns when a texture fails to load, and draws the whole scene with a short loop. My approach evolved from writing code that simply worked to writing code that is organized, commented, and ready to change.

### 3. How can computer science help me in reaching my goals?

Computational graphics gave me a deeper understanding of how software turns data into something people can see and interact with. For my education, the course strengthened my C++ skills and my understanding of transformations, lighting, cameras, and shader programs. These ideas connect to other areas I plan to study, such as simulation, game development, and user interface design. The object-oriented design I used in this project also applies directly to the other languages and frameworks I am learning.

For my professional path, I am working toward a career as a software developer. Visualization is a valuable skill in that field because many applications depend on presenting information clearly, whether through dashboards, 3D models, training simulations, or interactive tools. Just as importantly, this project showed me how to plan, test, accept feedback, and refine my work until it meets a standard. Those habits will help me succeed on any development team, and this repository gives me a record of that growth to share with future employers.
