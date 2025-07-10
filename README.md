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
| `uvColor.osl`         | Outputs a linear gradient color based on the UV coordinate's U and V values. Useful for testing UV mapping or generating procedural gradients. |
| `uvToColor.osl`       | Converts UV coordinates into color by mapping them into RGB space. Helpful for debugging UV layouts or creating simple color patterns.         |
| `uvToColorCircle.osl` | Generates a circular color gradient centered in UV space. Ideal for effects like procedural iris, halos, or radial masks.                      |
| `uvToColorCross.osl`  | Outputs a cross pattern based on the UV coordinates. Can be used for stylized shading or texture alignment guides.                             |
| `uvToColorDonut.osl`  | Creates a donut or ring-shaped pattern from UVs, suitable for procedural stylized looks or scientific material effects.                        |
| `SimpleColor.osl`     | Outputs a solid color defined by the user. Simple starting point for custom shading or to isolate objects by color.                            |
| `stToColor.osl`       | Similar to `uvColor.osl`, maps surface `s` and `t` parameters (UV) to RGB color. Used as a basic test of parameter-space shading.              |
| `simple_remap.osl`    | Remaps a value from one range to another, typically used to adjust or compress UV or texture inputs. Useful in pipeline control.               |
| `simple_Edge.osl`     | Generates edges or borders by detecting transitions in UV space, useful for creating outlines, masks, or cut-paper looks.                      |



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
