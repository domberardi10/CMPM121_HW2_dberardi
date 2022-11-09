# CMPM121_HW2_dberardi

Unity project for UCSC CMPM 121, Homework 2. Adding lighting, particles, and post-processing/rendering to HW1 scene.

NEO LONE-STRAND ISLE by Dominic Berardi

In this project, I wanted to add post-processing effects, particle effects, and a day/night cycle
to make the scene a bit more realistic and alive, while also adding some fun and unrealistic lights and particles.

---------------------------------------------------------------------------------

LIST OF LIGHTS

Directional Lights:
- DirectionalLightSun (acts as main/sun light, moves in accordance to day/night cycle)

Point Lights:
- PointLightFire (one of two lights originating from fire)
- PointLightShelter (illuminates inside of shelter)
- PointLightCrab (illuminates area around crab)
- PointLightFireParticles (attached to fire particles)
- PointLightChestParticles (attached to chest particles)

Spot Lights:
- SpotLightFish (above the splashing fish)
- SpotLightShark (pointed at shark for intimidating effect)
- SpotLightBoat (slightly illuminates wrecked boat, from shark POV)

Emissive Materials:
- Chest Gold (pile of gold glows yellow)
- Shark Eyes (each shark eye glows purple)

---------------------------------------------------------------------------------

LIST OF PARTICLES

2D texture emitters:
- ChestParticles (sparkles from chest gold)
- Fire_B (prefab containing fire, embers, and smoke; NOT made by me, credit below)
- SplashParticles (fish splashes, contains child splash emitter under it)
- WaterEdgeParticles (to make edge of terrain appear like waves)
- SandParticles (sand kicked up from crab)

3D mesh emitters:
- TreeLeavesParticles (3 total, leaves falling from trees; NOT made by me, credit below)
- CoconutParticles (3 total, coconuts falling from trees)

---------------------------------------------------------------------------------

LIGHTING TRANSITION

- Day/night cycle (Creating by rotating directional light around scene and editing skybox exposure;
uses 2 scripts to accomplish this task)

---------------------------------------------------------------------------------

POST-PROCESSING EFFECTS

All contained within global volume.

- Bloom (helps emissive glows appear)
- Film Grain (slight, enough to make it more "abandoned isle" like)
- Vignette (emulates necessity of shadows under harsh sun)
- Color Adjustments (changes to hue, contrast, and saturation to make less cartoony)

---------------------------------------------------------------------------------

RESOURCES

- A few particles effects and prefabs: https://assetstore.unity.com/packages/vfx/particles/effect-textures-and-prefabs-109031
- For a list of resources that are from the original HW1 version of the scene, see link:
https://github.com/domberardi10/CMPM121_HW1_dberardi 
