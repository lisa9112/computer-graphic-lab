Name: Sadia Akter Liza <br>
ID: 0432320005101116 <br>
# Project Overview
This project uses OpenGL 3.3 to render a single triangle. The color of the triangle is not static; it changes over time using a sine/cosine wave and can be overridden by specific keyboard inputs.
# Key Features 
* Shaders: Uses custom Vertex and Fragment shaders.
* Uniforms: Demonstrates glUniform4f to dynamically update the triangle's color.
* Input Handling: Real-time response to keyboard keys (W, R, and L).
* Smooth Animations: Utilizes glfwGetTime() for time-based color shifting.
# Prerequisites
To run this project, you need the following libraries configured in your C++ environment: 
* GLFW: For window creation and input handling.
* GLAD: To load OpenGL function pointers.
* GLM (Optional): Though not explicitly used in this snippet, it is standard for OpenGL mathematics.
# Controls
The application responds to the following keyboard inputs:KeyActionWChanges the triangle color to White while held.RPermanently changes the triangle color to Red (toggles a state).LCloses the application window.DefaultIf no keys are pressed, the color cycles through a Purple/Green/Blue gradient.
