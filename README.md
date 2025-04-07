# Advanced Orbital Simulator

A realistic N-body gravitational simulation with spacecraft maneuvers in a web browser environment.


![Screenshot 2025-04-07 224818](https://github.com/user-attachments/assets/098a27a9-adad-4764-bd14-1b9cef99e159)
![Screenshot 2025-04-07 224811](https://github.com/user-attachments/assets/8f8255e7-beff-4b4c-ac22-49070aeae419)





## Overview

This web application provides an interactive orbital mechanics simulator that allows users to:
- Simulate gravitational interactions between celestial bodies
- Launch spacecraft with customizable parameters
- Perform orbital maneuvers with realistic physics
- Observe orbital mechanics principles in action

## Features

### Simulation Capabilities
- N-body gravitational physics with Verlet numerical integration
- Multiple pre-configured celestial systems:
  - Sun-Earth system
  - Sun-Earth-Moon system
  - Binary star system
  - Custom system options
- Adjustable simulation speed and gravitational constant
- Pause and reset functionality

### Spacecraft Controls
- Launch new spacecraft with configurable:
  - Initial velocity
  - Launch angle
  - Trail visualization length
- Apply orbital maneuvers with:
  - Delta-V magnitude control
  - Directional control (0-360°)
- Vector visualization for velocity and acceleration

### User Interface
- Interactive canvas with spacecraft selection
- Real-time information overlay
- Tooltips for celestial body and spacecraft data
- Contextual maneuver planning panel
- Responsive design for different screen sizes

## Physics Implementation

The simulation uses:
- Newton's law of universal gravitation: F = G × (m₁ × m₂) / r²
- Verlet integration for accurate orbital calculations
- Realistic orbital mechanics equations:
  - Circular orbit velocity: v = √(GM/r)
  - Orbital period: T = 2π × √(a³/GM)
  - Specific orbital energy: ε = v²/2 - GM/r

## Usage Instructions

1. Select a celestial system from the dropdown menu
2. Adjust simulation settings as desired
3. Click "Launch New Craft" to add a spacecraft to the simulation
4. Select a spacecraft by clicking on it
5. Use "Add Maneuver" to plan orbital burns
6. Adjust maneuver parameters and click "Apply Burn" to execute

## Technical Details

The application is built with:
- HTML5 Canvas for rendering
- Vanilla JavaScript for simulation logic
- CSS for styling with responsive design considerations
- No external libraries or dependencies required

## Browser Compatibility

Works with all modern browsers that support HTML5 Canvas:
- Chrome
- Firefox
- Safari
- Edge

## Future Development Plans

Potential enhancements:
- Additional celestial system presets
- Advanced spacecraft types with different properties
- Mission objectives and challenges
- Improved visualization options
- Transfer orbit planning tools
- Data export functionality

## Credits

Developed as an educational tool for understanding orbital mechanics and gravitational physics in an interactive environment.
