# ParticleForge

GPU-accelerated particle system designer with physics simulation.

## Overview

ParticleForge is a visual particle system editor running entirely on the GPU. Create complex visual effects with forces, attractors, and collisions, then export to WebGL, Unity, or Unreal Engine.

## Features

- **GPU Computation**: All particle physics on compute shaders
- **Visual Editor**: Real-time parameter adjustment
- **Force Fields**: Gravity, wind, vortex, turbulence
- **Attractors**: Point, line, and plane attractors
- **Collision Detection**: Bounce, stick, and destroy behaviors
- **Export Formats**: WebGL, Unity, Unreal Engine compatible

## Technical Stack

- **WebGL** - GPU-accelerated rendering
- **GLSL** - Custom shader programs
- **Three.js** - 3D scene management
- **TypeScript** - Application logic
- **Compute Shaders** - Parallel particle simulation

## Particle Properties

- Position (x, y, z)
- Velocity (x, y, z)
- Acceleration
- Color (RGBA with interpolation)
- Size (with growth/shrink)
- Lifetime
- Rotation
- Custom attributes

## Force Types

**Global Forces**:
- Gravity
- Wind (directional)
- Drag/Friction

**Local Forces**:
- Point attractor/repeller
- Vortex
- Turbulence (Perlin noise)
- Collision planes

## Performance

- 1M+ particles at 60fps
- Transform feedback for state persistence
- Instanced rendering
- LOD system for distant particles

## Demo

View the live demo at: https://danielminton.github.io/ParticleForge/

## Author

Daniel Minton