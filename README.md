# Visual Vibrance

A shaderpack for [Iris](https://irisshaders.dev/) that recreates Mojang's **Vibrant Visuals** look on Minecraft: Java Edition — directional shadows, volumetric fog and light, colored block lighting, and reflective water — while keeping Minecraft's blocky, pixelated charm.

Originally forked from [Glimmer](https://modrinth.com/shader/glimmer-shaders).

## Features

- **Colored blocklight** — light sources emit their actual color (warm torches, cool soul lanterns, etc.) and it spreads through the world.
- **Directional shadows** — soft shadows that follow the sun's arc, with distance, resolution, softness and sample-count controls.
- **Volumetric fog & godrays** — light shafts through fog (volumetric and screen-space modes), plus cloud shadows and morning/rain fog.
- **Reflective water** — screen-space reflections, refraction, Snell's window, caustics and three wave-normal modes (plus an optional infinite ocean).
- **Sky & clouds** — procedural sun disc, a custom cloud layer with cloud shadows, and atmospheric fog.
- **PBR** — LabPBR 1.3 normal maps, roughness, metalness, porosity and emissives.
- **Post processing** — bloom, FXAA, optional temporal filtering and several tone-mapping operators.
- **Extras** — parallax occlusion mapping with self-shadowing, waving plants, rain puddles and emissive entities.
- **Performance profiles** — Potato, Toaster, iGPU and dGPU presets are built in.

## Compatibility

- Iris **1.7+** (OptiFine is _not_ supported).
- OpenGL **4.3+** — most modern GPUs work; macOS and Raspberry Pi are _not_ supported.

## Mod support

- **[Distant Horizons](https://modrinth.com/mod/distanthorizons)** — distant terrain is lit, fogged and water-shaded, with optional ambient occlusion and SSR.
- **Iris block/entity properties** — `block.properties` and `entity.properties` map blocks and entities to material IDs; modded content can be added by namespace (see `scripts/block_properties.py`).

## Installation

Drop the repository (or a release zip) into your Minecraft `shaderpacks` folder and select **Visual Vibrance** in Iris.

## Development

See [`DEVELOPMENT.md`](DEVELOPMENT.md) for the buffer and pass layout.

This is an alpha — expect bugs. Please report them in [my Discord server](https://discord.gg/4U3nPxTznF) or `#jbritains-shaderpacks` in the [shaderLABS Discord](https://discord.gg/RpzWN9S).
