# ImGui + GLFW + Vulkan

### This is a starting point for GLFW and Vulkan using the amazing Dear ImGui C++ library. It requires Microsoft Visual Studio as the .sln file, under source directory, will compile everything needed for this example. You only need to run this file in VS to try this example.

This example has been taken and separated from the main [Dear ImGui repo](https://github.com/ocornut/imgui/tree/master/examples/example_glfw_vulkan) and has been sort of refined so that you can have only the stuff needed, however, it is still an example/starting poin for you to explore. There are many things to be improved, I am a Linux user so I would **emphasize creating a CMake.List file** so you can complile only the files needed in an [*IDE (i.e. Visual Studio) independent way*](https://github.com/dcoldeira/ImGui_single-board_OpenGL). There is also the possibility of using SDL instead of GLFW, ImGui is so flexible that you can do whatever you wantwith it!   

Find all the *Dear ImGui* implementation stuff in the main.cpp file that will show once the .sln file is run.
