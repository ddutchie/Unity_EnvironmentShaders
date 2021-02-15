Unity_EnvironmentShaders
================================

This Repo contains some of my environments shader experiments in Unity3D



Grass
--------------------------------

Some Grass Shaders

![gif](/Media/Grass_2.gif)


Ivy
--------------------------------

Some Ivy Shaders



![gif](/Media/Ivy.gif)
![gif](/Media/Ivy_2.gif)

My take on an Ivy shader:
- Generate a few geometric copies (hulls)
- Offset based on normal * value.
- Sample Leaves from a base diffuse map.
- Use color ramp to specify depth for clipping cutoff values.
- Alternate UV offsets.

Features:
Forward (Custom lighting) + Deferred (PBR Lighting)




Inspiration:
--------------------------------
- [Keijiro's Standard Geometry Shader](https://github.com/keijiro/StandardGeometryShader)
- [Brute Force's Grass](https://www.bruteforce-games.com/post/grass-shader-devblog-04)
- [Shahriar Shahrabi's Volumetric Grass](https://shahriyarshahrabi.medium.com/volumetric-grass-shader-28ebb9f6860b)


Unity 2018.4
Should work in any project with a GPU that allows Geometry Shaders.
