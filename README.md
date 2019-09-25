# SMG Better Collada Exporter for Blender

Enhanced Collada exporter for [Blender](https://www.blender.org), making the
format viable for importing meshes into game engines using a libre format.

Forked from original [Godot Engine's "Better" Collada exporter](https://github.com/godotengine/collada-exporter). for Blender.
This version is not intended to create Collada (.dae) files optimized for the Godot Engine, it is more generic.
Some choices will be made in order to standardize the rendering as much as possible in the various 3D software and engines where DAE files will be used.

## Features

Same original features as "Better" Collada exporter with some modifications :

### General features

- Compatible with Blender 2.8+ (Thanks to [Artell's](https://github.com/artellblender/collada-exporter-2.8) work)
- Support Principled BSDF (only)

### Material features

- Emission (color/texture)
- Diffuse/base color (color/texture)
- Specular (value)
- Reflective/metallic (value/texture)
- Transparency/alpha (value)
- Indice of refraction (value)
- Backface culling/double sided (value)
- Normal map (texture)

## Installation

1. Copy the `io_scene_dae` directory the location where Blender stores the
   scripts/addons folder on your system (you should see other io_scene_*
   folders there from other addons). Copy the entire dir and not just its
   contents.
2. Go to the Blender settings and enable the "SMG Better Collada Exporter" plugin.
3. Enjoy full-featured Collada export.

If you find bugs or want to suggest improvements, please open an issue on the
upstream [GitHub repository](https://github.com/Sigmagine/blender-better-collada-exporter).

## License

This Better Collada exporter is distributed under the terms of the GNU General
Public License, version 2 or later. See the [LICENSE.txt](/LICENSE.txt) file
for details.
