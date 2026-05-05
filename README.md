# Quiz 8 – Design Research

## Part 1: Imaging Technique Inspiration

### 💨 Computational Fluid Dynamics & Digital Ink Wash

**Inspiration Source:** The immersive installation *Reversible Continuity* by **teamLab** and the digital landscape scroll paintings by artist **Yang Yongliang**.

**Description (≤100 words):**

I am inspired by the application of **Computational Fluid Dynamics (CFD)** to simulate the behavior of smoke and ink. This technique models the natural diffusion, collision, and swirling of particles within a medium. I want to incorporate a "Digital Ink" aesthetic into my interactive project: starting with a minimalist white canvas, the user’s cursor will act as a brush that injects deep black "ink" which swirls and dissipates like real smoke. This technique is beneficial as it combines traditional artistic sensibility with modern algorithmic randomness, creating a deeply immersive and meditative interactive experience.

---

### 📸 Visual References

**Figure 1 – teamLab Fluid Installation – Showcasing the beauty of flow and particle velocity**

![teamLab Fluid Art](https://www.teamlab.art/images/pc-l/11317.jpg)

*Source: teamLab Official – "Continuous Life and Death at the Now of Eternity"*

**Figure 2 – Digital Ink Diffusion – Simulating the delicate texture of ink spreading on paper**

![Digital Ink Wash Texture](https://raw.githubusercontent.com/PavelDoGreat/Fluid-Simulation/master/screenshots/fluid_2.png)

*Source: Fluid Simulation Study – Demonstrating density and velocity fields in a digital space.*

**Figure 3 – Abstract Smoke Patterns – Visualizing the turbulence and organic shapes of fluid motion**

![Smoke Fluid Patterns](https://raw.githubusercontent.com/PavelDoGreat/Fluid-Simulation/master/screenshots/fluid_3.png)

*Source: Generative Art Archive – High-contrast fluid dynamics visualization.*

---

## Part 2: Coding Technique Exploration

### 🌫️ Navier-Stokes Equations & Grid-Based Fluid Solvers

**Technique:** Implementing a simplified **Navier-Stokes solver** in p5.js, specifically utilizing a grid-based system to calculate velocity fields, pressure, and advection.

**Description (≤100 words):**

To achieve this effect, the code must manage a "Velocity Field" where every pixel or cell stores a vector representing flow direction. I will utilize Jos Stam’s stable fluid algorithm to handle the math of fluid viscosity and mass conservation. By mapping the `mouseX` and `mouseY` speed to the "force" injected into the grid, the user can physically "stir" the digital ink. This is a significant technical challenge involving nested loops and mathematical convergence, providing a sophisticated interaction model that feels far more reactive and "alive" than basic particle systems.

---

### 📸 Coding Technique Screenshot

**Figure 4 – Real-time fluid field simulation logic in a JavaScript environment**

![Fluid Simulation Code Screenshot](https://raw.githubusercontent.com/PavelDoGreat/Fluid-Simulation/master/screenshots/fluid.png)

*Source: GitHub – "Fluid Simulation" by PavelDoGreat, demonstrating the underlying interactive solver.*

---

### 🔗 Example Implementation

- **Live Example & Code:** [Web-based Interactive Fluid Simulation – High-fidelity real-time fluid interaction](https://paveldogreat.github.io/Fluid-Simulation/)
- **Technical Tutorial:** [The Coding Train – Coding Challenge #132: Fluid Simulation in p5.js](https://thecodingtrain.com/challenges/132-fluid-simulation)
- **Scientific Reference:** [Jos Stam – Real-Time Fluid Dynamics for Games (Original Paper)](https://www.dgp.toronto.edu/public_user/stam/reality/Research/pdf/GDC03.pdf)
- **Documentation:** [p5.js Official Reference - Using beginShape() for flow visualization](https://p5js.org/reference/p5/beginShape/)

---
*Quiz 8 – [Kaylin] – [mzha0737]*