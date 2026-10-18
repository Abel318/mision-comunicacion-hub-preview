# Potted Plant 01 — provenance and web derivative

Author: Rico Cilliers / Poly Haven.
Source: https://polyhaven.com/a/potted_plant_01
License: CC0 1.0 Universal, https://creativecommons.org/publicdomain/zero/1.0/
Evidence: https://polyhaven.com/license
CC0 permits use, modification and redistribution, including commercial use.

Source download: https://api.polyhaven.com/files/potted_plant_01
The 1K glTF, its binary and six 1K maps were downloaded on 2026-10-17.
The separate 1K leaves alpha map was combined into the leaf base-color map.

Derived file: potted-plant-01-web.glb
Size: 1,085,952 bytes. Geometry: 15,318 triangles, four meshes, two materials.
Six embedded WebP textures, maximum 1024 by 1024. No external dependencies.
No animations, lights, cameras or new runtime dependencies.

Conversion: glTF Transform dedup, weld, Meshopt simplify (ratio 0.085,
error 0.01), prune, WebP quality 80, GLB export. Original UVs and PBR
materials retained; alpha masking preserved for the leaf contours.
SHA-256: 1375713fa62d95f53343b500f4ec16fbf5581e9d461632dfbcba6c703fe5d86b

Placement: replaces only plant-front-left, previously plant-fig.glb.
Center X -3.4, base Y -0.02, center Z 3.6; target height 1.32 m;
yaw 0 radians. Uniform scale approximately 0.98813635.
Measured world footprint: 0.580 by 0.626 m, within the unchanged 0.8 m limit.
The center, target height, footprint limit and all other plant slots are unchanged.

The same GLB is supplied in the public hub preview under models/hub/.
