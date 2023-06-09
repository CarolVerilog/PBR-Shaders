# Physically-Based Rendering Shaders

## Related Rendering Techniques

- Subsurface Scattering BRDF: Lambertian BRDF
- Specular BRDF:
  - Normal Distribution: GGX Normal Distribution
  - Geometry Function: Height-Correlated Smith Maksing and Shadowing Function
- Transparency: Order Independent Transparency via Per-Pixel Linked-List
  - As there's few information in model files about whether a mesh needs to be alpha blended, all meshes will be rendered as opaque.
- Shadows: Cascaded Shadow Map
  - Shadows are generated by one main light source. Other light sources have no contribution to it.

## Samples

One main diretional white light and four axis-aligned light yellow point lights take part in the rendering.

![THao65.png](https://i3.lensdump.com/i/THao65.png)

![THauzz.png](https://i.lensdump.com/i/THauzz.png)

![THaDwT.png](https://i3.lensdump.com/i/THaDwT.png)

![THaPtb.png](https://i2.lensdump.com/i/THaPtb.png)