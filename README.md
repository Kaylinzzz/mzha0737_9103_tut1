# Quiz 8 – Design Research

## Part 1: Imaging Technique Inspiration

### 🎨 Algorithmic Action Painting

**Inspiration Source:** *Autumn Rhythm (Number 30)* by Jackson Pollock (1950), emphasizing the "Drip Technique."

**Description (≤100 words):**
I want to incorporate Pollock's **dynamic fluid distribution**, specifically the spontaneous "splatter" effect created by his drip technique[cite: 2]. Instead of a static imitation, I aim to represent the fluid energy of his layered lines through interactive code[cite: 2]. This technique is beneficial because it allows me to extend the artwork’s structural randomness into a responsive system where user movement dictates the paint's dispersion[cite: 2]. By mapping mouse speed to splat density, I can capture the essence of Pollock's gestural style while fulfilling the assignment's requirement to add creative interactive mechanics[cite: 2].

---

### 📸 Visual References

**Figure 1 – *Autumn Rhythm (Number 30)* – Original Masterpiece Study**

![Autumn Rhythm by Pollock](https://images.unsplash.com/photo-1541701494587-cb58502866ab?auto=format&fit=crop&q=80&w=1000)

*Source: Public Domain Masterpiece Study - Jackson Pollock (1950).*

**Figure 2 – Digital Drip Representation – Abstracting physical painting into code**

![Drip Simulation](https://images.unsplash.com/photo-1549490349-8643362247b5?auto=format&fit=crop&q=80&w=1000)

*Source: Study of digital fluid dynamics and randomized artistic textures.*

**Figure 3 – Splatter Logic – Reimagining chaotic lines as interactive partitions**

![Splatter Detail](https://images.unsplash.com/photo-1579783902614-a3fb3927b6a5?auto=format&fit=crop&q=80&w=1000)

*Source: Visualizing how randomized particle dispersion can reinterpret classical artwork.*

---

## Part 2: Coding Technique Exploration

### 🎨 p5.js Velocity-Responsive Particle Systems

**Technique:** Using the `dist()` function combined with `pmouseX` and `pmouseY` to calculate user interaction velocity, which dynamically controls the stroke weight and particle dispersion[cite: 1, 2].

**Description (≤100 words):**
To implement the "Action Painting" style, I will use a **Velocity-Responsive Particle System**[cite: 2]. By calculating the distance between the current and previous mouse positions, the code maps interaction speed to the visual properties of digital paint[cite: 2]. Fast movements trigger a widespread "splatter" of particles, while slower movements create thick, continuous lines[cite: 1]. This technique is beneficial because it moves beyond static drawing, using real-time physics-based logic to create an engaging interactive experience that honors Pollock's gestural legacy[cite: 2].

---

### 📸 Coding Technique Screenshot

**Figure 4 – p5.js implementation of dynamic interactive logic**

![Dynamic Particle Code](https://happycoding.io/tutorials/p5js/images/creating-classes/6.png)

*Source: Visualizing real-time coordinate and drawing logic via Happy Coding.*

---

### 🔗 Example Implementation

- **Live Example & Code:** [Jackson Pollock Drip Art - Professional p5.js Simulation](https://openprocessing.org/sketch/837834)
- **Technical Tutorial:** [The Coding Train – Coding Challenge #155: Drawing with Particles](https://www.youtube.com/watch?v=UcdigVaIYAk)
- **Official Documentation:** [p5.js Reference for pmouseX/Y and dist()](https://p5js.org/reference/p5/pmouseX/)
- **GitHub Reference:** [Advanced Physics Brushes for Creative Coding](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js)
- **Community Resource:** [p5.js Interactivity Guide - Tracking Mouse Speed](https://p5js.org/learn/interactivity.html)

---

*Quiz 8 – [Kaylin] – [mzha0737]*