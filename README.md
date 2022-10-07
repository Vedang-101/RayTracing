# RayTracing
Creating a CPU based raytracing renderer

Raytracing is the process of simulating light bounces and getting shadows/colors on the screen. It is the key process to achieve photo realistic renders.
Raytracing series covers the math that goes when rendering the scene. The math includes:
- Ray-Sphere intersection
- Ray bouncing
- Accumulating resultant lights

The raytracing/pathtracing begins by shooting rays from camera each corresponding to the pixel on the screen. These rays intersect the spehere/objects in the scene and bounce back, the intensity of the ray decreases here based on sphere material's roughness and color. All this calculations are done in per pexel to achive the final image.

The project includes a sample scene with 800 sphere with different material properties: shinny, rough, color etc. Each affecting how the light bounces and reaches the camera. The output for which is below:
![image](https://user-images.githubusercontent.com/45897291/194643959-8b33b8e4-867f-4689-920a-f1162b00c58c.jpg)
