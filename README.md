# Sun-Earth-Moon OpenGL Model (CS 450 Final Project)

## Video Demo Link (with commentary)
https://youtu.be/X0zbDIMpm8A

## Specifications
- 3D model of Sun, Earth, and Moon built with OpenGL library
- Lighting is rendered appropiately to model how the sun's light hits the Earth / Moon
- Supports following viewpoints on planetary system via keyboard shortcuts:
  - "Top down" view on all 3 celestial bodies
  - View from the Earth on the Moon / Sun
  - View from the Moon on the Earth / Moon
- The rotation and revolving time periods of the Sun / Earth / Moon are modeled proportionately to each other when possible, although some artistic liberties had to be taken with some of the radii / orbital radii as explained [here](https://github.com/solderq35/450_final/blob/master/final.cpp#L46)

## Setup Instructions
- Open project (with all source files) in Visual Studio, go to Debug > Build Sample
- See keyboard function definition in source code [here](https://github.com/solderq35/450_final/blob/master/final.cpp#L1119) for keyboard shortcuts to rotate views, pause animations, etc
