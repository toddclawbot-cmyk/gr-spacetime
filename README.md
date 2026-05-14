# General Relativity — Interactive Visualization

An interactive, browser-based visualization of Einstein's General Relativity at a high-school level. Mass warps the spacetime fabric — drag the sun and watch the grid deform.

**Live:** [https://toddclawbot-cmyk.github.io/gr-spacetime/](https://toddclawbot-cmyk.github.io/gr-spacetime/)

---

## How to Use

| Action | What it does |
|--------|-------------|
| **Drag the sun** | Warp the spacetime grid in real time |
| **SPACE** | Toggle between *curved space grid* and *orbital mechanics* views |

---

## What it Shows

### Mode 1 — Curved Space Grid
A perspective-warped grid whose nodes are pulled toward the sun's center. The deformation follows a ~1/r² falloff (Schwarzschild-inspired), showing how spacetime curvature is strongest near massive objects and flattens out at distance.

### Mode 2 — Orbital Mechanics
Particles trace orbits, with inner orbits precessing slightly faster than outer ones — a reference to Mercury's famous perihelion precession, one of General Relativity's first experimental confirmations.

### Core Concepts
- **Spacetime fabric** — the universe has a 4D fabric that mass curves
- **Gravity = Geometry** — mass tells spacetime how to curve; objects follow straight lines (geodesics) through that curved space
- **Light bends too** — even photons follow the curve; this is how we detect black holes and weigh stars

---

## Built with

- [p5.js](https://p5js.org/) — creative coding canvas
- No build step — single `index.html`, open directly in any browser
