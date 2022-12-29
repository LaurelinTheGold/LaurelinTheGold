<!-- - 👋 Hi, I’m @LaurelinTheGold
- 👀 I’m interested in Computer Graphics, Computer Vision, and Computer Systems. 
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ... -->

<!---
LaurelinTheGold/LaurelinTheGold is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


# Hello there #
<!-- ![](hellothere.jpg) -->

<img src="./demo_imgs/hellothere.jpg" width=512>

## About Me ##

I'm @LaurelinTheGold. I am currently a Masters Student at the University of Pennsylvania, where I am studying Robotics ('23). I also studied at Penn for undergrad, where I majored in Computer Engineering ('22).

I like code that: interacts with the real world[^1], uses cool math[^2] to solve problems[^3], runs fast in software[^4] or hardware[^5], and is correct[^6]

RISC-V Fan

[^1]: robotics, embedded systems

[^2]: Linear Algebra, Calculus, Complex Analysis, etc

[^3]: computer graphics, computer vision, deep learning, robotics

[^4]: Rust, C, C++, maybe even assembly

[^5]: GPUs, ~~FPGAs~~ jk, friendship ended with FPGAs. I would like to learn more about DSPs and OpenCL 

[^6]: 🥰 strong type systems my beloved 🥰, ❤️ Rust and Haskell ❤️

## Skills ##
### Programming Languages ###
`C++` `C` `Python` `Rust` `Haskell` `Objective-C` `Verilog`
### Graphics and GPU ###
`CUDA` `OpenGL` `Metal` `Vulkan` `cuDNN`
### Other ###
`LaTeX`

## Projects ##

### [cuFLAVR](https://github.com/adityahota/CIS565-Final-Project-SlowMo): ###
A Video Frame Interpolation Neural Network implemented using C++, CUDA, and cuDNN <br/>
`C++` `CUDA` `cuDNN` `Python` `PyTorch` <br/>
| **Original (30 FPS)** | **2x interpolated (30 FPS)** |
| --------------------- | ---------------------------- |
| <img src="https://github.com/adityahota/CIS565-Final-Project-SlowMo/raw/master/visuals/squirrel.gif" height="180" /> | <img src="https://github.com/adityahota/CIS565-Final-Project-SlowMo/raw/master/visuals/squirrel_2x.gif" height="180" /> |

### [GPU Wavefront Pathtracer](https://github.com/LaurelinTheGold/Project3-CUDA-Path-Tracer): ###
Wavefront Path Tracer that also supports [A-trous Denoising](https://github.com/LaurelinTheGold/Project4-CUDA-Denoiser/tree/denoiser) <br/>
`C++` `CUDA` <br/>
<img src="https://github.com/LaurelinTheGold/Project3-CUDA-Path-Tracer/raw/main/finalRenders/ebon_final.png" width="480" />

### [Fill In The Gaps](): ###
Object Localization using Event Based Cameras <br/>
`PyTorch` `Python` `Computer Vision` `U-Net` `Deep Learning` <br/>
<img src="./demo_imgs/visual_samples.png" width="240" />

### [Vulkan Grass Renderer](https://github.com/LaurelinTheGold/Project5-Vulkan-Grass-Rendering): ### 
Physics-based grass simulation using tessellation shaders <br/>
`C++` `Vulkan` <br/>
<img src="./demo_imgs/vulkan_grass_ezgif.com-gif-maker.gif" width="480" />

### [CUDA Flocking Boids](https://github.com/LaurelinTheGold/Project1-CUDA-Flocking): ###
Flocking Boids <br/>
`C++` `CUDA` <br/>
<img src="https://raw.githubusercontent.com/LaurelinTheGold/Project1-CUDA-Flocking/main/images/recording2.gif" width="480" />

### [Mini-Minecraft](): ###
Minecraft-like voxel sandbox game, [Demo](https://www.youtube.com/watch?v=d-_nEmR7Yp4) <br/>
`C++` `OpenGL` `GLSL` `Qt Creator` <br/>
<img src="./demo_imgs/image_2021-04-28_02-04-24.png" width="480" />

### [MicroMaya Half Edge Mesh Editor](): ###
Half-Edge Mesh editor <br/>
`C++` `OpenGL` `Qt Creator` `GLSL` <br/>
| Catmull-Clark Subdivision | Skeleton/Joint Binding | Linear Blend Skinning |
|---------------------------|-------------------------------------|-----------------------|
| <img src="./demo_imgs/159842490_804116646845135_3086751840735921174_n.png" height="180" /> | <img src="./demo_imgs/162232470_5255659964475862_8966000904798328284_n.png" height="180" /> | <img src="./demo_imgs/163107793_264296075238540_2445317366563914140_n.png" height="180" /> |

### [JCompiler](): ###
A compiler for the J language[^JC] that targets LC4[^LC4] assembly <br/>
`C` <br/>
Towers of Hanoi demo, written in J, compiled to LC4, then run in a simulator <br/>
<img src="./demo_imgs/ezgif.com-gif-maker.gif" width="480" />

### [CPU Pathtracer](https://github.com/LaurelinTheGold/RTIOW_rust): ###
CPU Pathtracer following the Ray Tracing in One Weekend [RTIOW](https://raytracing.github.io/books/RayTracingInOneWeekend.html) tutorial <br/>
`Rust` <br/>
<img src="https://raw.githubusercontent.com/LaurelinTheGold/RTIOW_rust/main/images/image_balls_1920_1200.png" width="480" />

### [Block Picking Competition](): ###
Franka Emika Panda Robot Arm Picking and Placing Blocks <br/>
`ROS` `Python` <br/>
<img src="./demo_imgs/dynamic_blocks.jpg" width="240" />

### [Data Unlimited Compile for FPGAs](): ###
Easier FPGA prototyping with more RAM and faster compile times <br/>
`FPGA` `RISC-V` `HLS C` <br/>
<img src="./demo_imgs/sen_des.png" width="480" />

## TODO ##
<!-- * [Rasterizer and Scene Graph?] -->



### [Superscalar Pipelined LC4 CPU](): ###
Dual-Issue, In-Order, Pipelined LC4[^LC4] CPU implemented in Verilog

### [PennOS](): ###
Unix-like OS with kernel and filesystem

### [PennShell](): ###
Shell with piping and builtins

### [Lu Syntax Checker]():  ###
Adding a type system, syntax checking, and language server to a subset of Lua using Haskell Monad Transformers

### [SRAM Design](): ###
16 Nibble SRAM and driver circuitry <br/>
`GNU Electric` `Ngspice` <br/>
<img src="./demo_imgs/full_sram2.png" width="480" />

### [Concurrent Event Timeline](): ###
Gantt chart generated from XML file

### [Gameul8](): ###
Chip8 Emulator built using C

<!-- ### Some Exposure ProgLangs###
`OCaml` `bash` `java` `Matlab/Simulink` `RISC-V`
### Some Exposure Other ###
`Control Theory` `Forward and Inverse Kinematics` `Networking` `Signal Processing`
### Operating Systems ###
`Linux` `MacOS` `Windows` -->

[^LC4]: RISC ISA designed for education based on Little Computer 3 (LC-3) from Patt and Patel

[^JC]: Stack-based language loosely based on Forth, not to be confused with [J Programming Language](https://en.wikipedia.org/wiki/J_(programming_language))


### [Traffic Manager](): ###
Schedule traffic at intersection <br/>
<img src="./demo_imgs/uppaal.jpg" width="240" />
