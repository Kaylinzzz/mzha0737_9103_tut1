# Quiz 8 – Design Research

## Part 1: Imaging Technique Inspiration

### 🦢 Emergent Collective Motion – Boids Algorithm

**Inspiration Source:** *Boids* by Craig Reynolds (1986) and the immersive digital installations of **Universal Everything**.

**Description (≤100 words):**

I am inspired by **Agent-Based Flocking (Boids)**, a technique that simulates the collective behavior of birds or fish. By applying three simple rules—Separation, Alignment, and Cohesion—thousands of individual "agents" create a fluid, organic mass that moves with startling lifelike complexity. For my interactive project, I want to treat the user's cursor as a "predator" or an "attractor," forcing the flock to scatter or coalesce dynamically. This technique is artistically superior to static animation because the visual output is never the same twice, offering a deep sense of "life" and responsiveness within the digital canvas.

---

### 📸 Visual References

**Figure 1 – Flocking Simulation – Complex emergent patterns from simple agents**

![Boids Simulation](https://upload.wikimedia.org/wikipedia/commons/3/3b/Boids_Alignment_Behavior.gif)

*Source: Wikimedia Commons – Visualization of Alignment behavior in a collective system.*

**Figure 2 – Generative Swarm Art – Using agent trails to create abstract "light paintings"**

![Swarm Intelligence Art](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2b/Boids_Cohesion_Behavior.gif/640px-Boids_Cohesion_Behavior.gif)

*Source: Wikimedia Commons – Visualization of Cohesion behavior and flocking density.*

**Figure 3 – Interactive Agent Trails – Particles leaving paths to create complex textures**

![Particle Trails](https://upload.wikimedia.org/wikipedia/commons/a/af/Flocking_boids.gif)

*Source: Wikimedia Commons – Full 2D Boids simulation in motion.*

---

## Part 2: Coding Technique Exploration

### 🧠 Vector Math & Autonomous Agents

**Technique:** Implementing a **Class-based system** in p5.js where each "Boid" object possesses its own `PVector` for position, velocity, and acceleration.

**Description (≤100 words):**

The core coding technique relies on **Vector Math** and object-oriented programming. Each frame, every agent calculates its distance from every other agent to apply steering forces. This is a high-level coding challenge because it requires optimizing loops and understanding force accumulation (`applyForce`). By integrating the `p5.Vector` library, I can calculate a "seek" behavior toward the `mouseX` and `mouseY` coordinates. This turns a mathematical simulation into a highly sensitive interactive instrument, where the user directly manipulates the velocity and flow of a virtual living system.

---

### 📸 Coding Technique Screenshot

**Figure 4 – p5.js Vector logic for flocking behavior**

![p5.js Boids Code Screenshot](https://happycoding.io/tutorials/p5js/images/boids-1.png)

*Source: Happy Coding – "Boids in p5.js", showing the particle interaction logic.*

---

### 🔗 Example Implementation

- **Live Example & Code:** [Boids: Flocking Simulation by Daniel Shiffman – Interactive p5.js Sketch](https://editor.p5js.org/codingtrain/sketches/ry4XZ877-)
- **Technical Tutorial:** [The Coding Train – Coding Challenge #124: Flocking Simulation](https://thecodingtrain.com/challenges/124-flocking-simulation)
- **Original Research:** [Craig Reynolds – Steering Behaviors for Autonomous Characters](http://www.red3d.com/cwr/steer/)
- **Documentation:** [p5.js Official Reference - Vector Class](https://p5js.org/reference/p5/p5.Vector)

---
*Quiz 8 – [Kaylin] – [mzha0737]*