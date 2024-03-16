# Raytracing using CUDA
This project implements a simple ray tracing renderer using CUDA (Compute Unified Device Architecture), a parallel computing platform and programming model developed by NVIDIA. It utilizes the GPU for accelerating the rendering process, allowing for real-time rendering of complex scenes.
<img src="./Raytracer-CUDA/rendered_image.ppm" width="400px" alt="picture">

## Overview
The ray tracing algorithm simulates the behavior of light rays in a scene, allowing for realistic rendering of reflections, refractions, shadows, and other optical effects. This implementation follows the tutorial Raytracing in weekend using CUDA by Roger Allen and QuantitativeBytes, providing a practical example of GPU-accelerated ray tracing.

## Features
- CUDA Acceleration: Utilizes the power of NVIDIA GPUs for parallel computation, significantly speeding up rendering times.
- Sphere Rendering: Demonstrates rendering of spheres with different materials, including Lambertian, metal, and dielectric materials.
- Multiple Samples per Pixel: Implements multiple samples per pixel to reduce aliasing and improve the visual quality of the rendered image.
- SDL Integration: Renders the final image using SDL (Simple DirectMedia Layer), allowing for real-time visualization of the rendered scene in a window.

## Requirements
- Ensure you have an NVIDIA GPU with CUDA support.
- Install the necessary dependencies, including CUDA Toolkit and SDL library.
