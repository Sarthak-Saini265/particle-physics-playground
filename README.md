# particle-physics-playground

## Summary

Create an interactive Particle Physics Playground! A beautiful, fun web app where users can:

1. Click anywhere on the screen to create explosive particle effects with random colors
2. Particles should have realistic physics - gravity, velocity, fade out over time
3. Include control sliders for:
   - Gravity strength (0-2)
   - Particle count per explosion (10-200)
   - Particle lifetime (1-5 seconds)
   - Particle size (2-20 pixels)
4. Add preset effect buttons:
   - 🎆 Fireworks (colorful, upward burst)
   - ⭐ Stars (golden, twinkling effect)
   - 💫 Galaxy (spiral pattern, purple/blue)
   - 🌈 Rainbow (all colors, gentle cascade)
   - ❄️ Snow (white/blue, slow falling)
5. Include a 'Clear Canvas' button
6. Show FPS counter in top-right corner
7. Add a dark gradient background (deep blue to black)
8. Display particle count on screen
9. Include keyboard shortcuts:
   - Space: Random explosion at center
   - C: Clear canvas
   - 1-5: Activate preset effects
10. Add smooth animations using requestAnimationFrame
11. Make it visually stunning with glow effects and smooth transitions

The app should feel magical and satisfying to interact with - like playing with digital fireworks!

## Features

This application was automatically generated to meet the following requirements:

- Page uses Bootstrap 5 for UI controls
- Has full-screen canvas element for particle rendering
- Click creates particle explosion at mouse position
- Has gravity slider (0-2 range)
- Has particle count slider (10-200 range)
- Has particle lifetime slider (1-5 seconds)
- Has particle size slider (2-20 pixels)
- Has 5 preset effect buttons (Fireworks, Stars, Galaxy, Rainbow, Snow)
- Has 'Clear Canvas' button
- Shows FPS counter in top-right
- Shows current particle count on screen
- Space key creates explosion at center
- C key clears canvas
- Keys 1-5 activate preset effects
- Particles have physics (velocity, gravity, fade)
- Particles glow and have smooth alpha transitions
- Dark gradient background (blue to black)
- Responsive layout works on all screen sizes
- Sliders update physics in real-time
- Preset effects have distinct visual styles

## Setup

This is a static web application that requires no build process.

### Local Development

1. Clone this repository
2. Open `index.html` in a web browser
3. Or serve with a local server:
   ```bash
   python -m http.server 8000
   ```


## Usage

Simply open the `index.html` file in a modern web browser. The application includes:
- Bootstrap 5 for responsive design
- Inline JavaScript for functionality
- Embedded data for attachments

## Code Explanation

### HTML Structure
- Uses semantic HTML5 elements
- Bootstrap components for UI
- Responsive design that works on all devices

### JavaScript Functionality
- Handles user interactions
- Processes data from attachments
- Updates DOM elements dynamically
- Includes error handling

### Styling
- Bootstrap 5 framework
- Custom CSS for specific requirements
- Mobile-first responsive design

## Deployment

This application is deployed on GitHub Pages and accessible at the URL provided in the repository settings.

## License

MIT License - See LICENSE file for details

## Auto-Generated

This application was automatically generated using AI-powered code generation.
Generated on: particle-physics-playground
