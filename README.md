# OSL_Shader_Projects
[OSL Pattern Demo](./osl_pattern_demo.mp4)

[OSL Pattern Preview](./preview_osl_pattern.jpg) 

[Butterfly Texture Preview](./preview_butterfly.jpg)

This is a collection of OSL shaders and stylized material studies created with Pixar's RenderMan during my coursework at SCAD, under the instruction of Professor Malcolm Kesson.

The goal was to explore the power of OSL in generating procedural textures, animated shaders, and unique visual effects for look development.

## File Overview

- Custom OSL code (see [`osl/`](./osl))
- Maya scene files demonstrating shader use
- Preview renders and one demo animation

## OSL Files
📄 [uvColor.osl](./osl/uvColor.osl) – Outputs the UV color as RGB, often used to visualize or debug UV layouts.

📄 [uvToColor.osl](./osl/uvToColor.osl) – Similar to uvColor, but mapped to HSV or circular hue shifts, color visualization based on UV.

📄 [stToColor.osl](./osl/stToColor.osl) – Converts surface coordinates (s, t) parameters (UV) to RGB color, used as a basic test of parameter-space shading. 

📄 [uvToColorCircle.osl](./osl/uvToColorCircle.osl) – Generates a circular pattern based on UV coordinates, useful for stylized materials.

📄 [uvToColorCross.osl](./osl/uvToColorCross.osl) – Generates a cross pattern based on UV coordinates, useful for stylized materials.

📄 [uvToColorDonut.osl](./osl/uvToColorDonut.osl) – Generates a donut-shaped pattern based on UV coordinates, useful for stylized materials.

📄 [SimpleColor.osl](./osl/SimpleColor.osl) – Outputs a single flat color. Useful as a base shader to test pipeline.

📄 [simple_remap.osl](./osl/simple_remap.osl) – Remaps input color or UV values from one range to another, good for fine-tuning gradients or intensity curves.

📄 [simple_Edge.osl](./osl/simple_Edge.osl) – Adds soft edge detection based on UV or custom threshold. Can be used to fake outlines.

📄 [helix.osl](./osl/helix.osl) – Generates a procedural helix shape, useful in animated shader effects or stylized overlays.

📄 [SEM_Direction.osl](./osl/SEM_Direction.osl) –	Adds directional line patterns that simulate SEM-style shading or lighting.

📄 [SEM_Edge.osl](./osl/SEM_Edge.osl) –	Creates an edge highlight effect for emphasizing structural boundaries in SEM renders.

📄 [SEM_Noise.osl](./osl/SEM_Noise.osl) –	Applies subtle random noise to the surface, mimicking electronic grain or natural material roughness.

📄 [SEM_Radial.osl](./osl/SEM_Radial.osl) –	Generates radial distortion or light-based concentric highlights, great for focusing viewer attention.

## Tools Used

- **Pixar RenderMan** – for high-quality rendering and shader evaluation
- **Autodesk Maya** – for scene assembly, shader testing, and animation
- **Cutter** – a custom local development tool used at SCAD, I use it to write an local HTML pages for project preview, demo, submission, and feedback
- **Open Shading Language (OSL)** – for writing procedural shaders

## Learning Outcomes

- Developed custom procedural shaders using OSL
- Gained experience translating math into visual output
- Explored stylized shading approaches without textures
- Practiced integrating shaders into Maya + RenderMan pipeline

## Contact / Portfolio
Author: Arrow Lyu 
Email: jcrane@gmail.com
GitHub: [[Arrow's profile]](https://github.com/ArrowAlrakis)
