Tileable surface textures.

Texture Types
=============
Textures are split into multiple maps that can be used in shader materials as needed.

* D: Diffuse color.
* N: Tangent space normal map.
* B: Bump/height map. Can also be used for displacement mapping.
* MSR: Metallic/Specular/Roughness, stored in the RGB channels in that order. Used for physically based rendering (PBR).
* H: Height/displacement map. Basically a modified bump map for mesh displacement.
