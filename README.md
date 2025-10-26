# Particol

Particol is an emergent particle simulation where complex patterns and behaviors arise naturally from simple physics rules. Watch as different particle types interact, react, and evolve through attraction, repulsion, and chemical reactions - all without hardcoded behaviors.

## Live Demo
[View Live Demo](https://tflannagan.github.io/Particol/)

## Features

* **Emergent Behavior System** - Complex patterns emerge from simple physics rules without scripted behaviors
* **Dynamic Particle Types** - Multiple particle types with unique properties (mass, charge, stability, reactivity)
* **Chemical Reactions** - Particles can transform, merge to create new types, or split into multiple particles
* **Energy Conservation** - Momentum and energy are preserved throughout all interactions and reactions
* **Synthwave/Cyberpunk Theme** - Vibrant neon colors (pinks, purples, blues, cyans) with glowing particle effects
* **Light/Dark Mode Toggle** - Seamless theme switching with localStorage persistence
* **Interactive Canvas** - Draw particles directly onto the canvas with mouse or touch
* **Responsive Design** - Mobile-first design that adapts to any screen size
* **Real-time Statistics** - Track particle count, types, momentum, and reaction count
* **Control Panel** - Clear, scatter, and pause simulation controls

## How It Works

The simulation creates truly emergent behavior through:

1. **Force-Based Physics** - Particles attract or repel each other based on their type affinities and charges
2. **Collision Detection** - Spatial grid optimization enables efficient particle interaction calculations
3. **Reaction System** - When particles collide with sufficient energy, they can:
   - Transform into different types
   - Merge to create new hybrid types with inherited properties
   - Split into multiple particles with conserved momentum
4. **Natural Selection** - New particle types emerge with randomized but inherited properties from parent particles

## How to Use

1. **Select a particle type** by clicking one of the colored circle buttons
2. **Draw particles** by clicking and dragging on the canvas
3. **Watch** as particles interact, form structures, and react with each other
4. **Toggle theme** with the sun/moon button for light or dark mode
5. **Scatter** random particles across the canvas
6. **Clear** to reset the simulation
7. **Pause/Resume** to freeze or continue the simulation

## Technical Details

* Built with pure HTML5, CSS3, and JavaScript (no frameworks)
* Canvas API for rendering and particle visualization
* CSS Variables for dynamic theming
* Spatial grid partitioning for O(n) collision detection
* Physics simulation with velocity Verlet integration
* LocalStorage for theme preference persistence
* Touch and mouse event support for mobile and desktop
