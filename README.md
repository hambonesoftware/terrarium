# Terrarium: Worlds Within

A playable procedural 3D terrarium evolution sandbox that runs directly in your browser.

**[Play Terrarium](https://hambonesoftware.github.io/terrarium/)**

## What's inside

- A larger procedurally generated miniature ecosystem, with detailed trees, ferns, grass, mushrooms, stones, a pond, and animated ambient particles.
- Animals appear when habitat conditions become suitable, including species adapted to wetlands, meadows, and other climates.
- Adjustable rainfall, temperature, mutation rate, simulation speed, and pause.
- Populations respond to their habitats, with simplified inheritable traits, changing populations, and possible extinction and re-emergence.
- Orbit and zoom controls (drag/swipe and scroll/pinch), plus a mobile-friendly interface.
- WebGL 3D renderer, with a lighter 2D fallback for devices that cannot create a WebGL context.

## Controls

| Action | Control |
| --- | --- |
| Orbit terrarium | Drag or swipe |
| Zoom | Mouse wheel or pinch |
| Adjust the environment | Rainfall and temperature sliders |
| Change evolutionary pace | Mutation-rate slider |
| Watch more generations | Time button (1×, 4×, 12×) |
| Start over | New World |

## Run locally

Open `index.html` in a modern browser. The game is self-contained: no build step or external JavaScript libraries are required.

## Deployment

Pushing changes to `main` triggers `.github/workflows/deploy-pages.yml`, which publishes the repository to GitHub Pages. If this is the first deployment, enable **GitHub Pages → Build and deployment → Source: GitHub Actions** in the repository settings.

## Project status

This is an evolving prototype, not a scientifically complete evolution simulator. Habitat-based animal appearances and inherited trait adaptation are simplified. Full genetics, speciation, advanced animal behaviors, and civilization emergence are future possibilities.

Source: [hambonesoftware/terrarium](https://github.com/hambonesoftware/terrarium).
