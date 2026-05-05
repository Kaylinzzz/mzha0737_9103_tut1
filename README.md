# Quiz 8 – Design Research

## Part 1: Imaging Technique Inspiration

### 🎨 Algorithmic Action Painting

**Inspiration Source:** *Autumn Rhythm (Number 30)* by Jackson Pollock (1950), emphasizing the "Drip Technique."

**Description (≤100 words):**
I want to incorporate Pollock's **dynamic fluid distribution**, specifically the spontaneous "splatter" effect created by his drip technique. Instead of a static imitation, I aim to represent the fluid energy of his layered lines through interactive code. This technique is beneficial because it allows me to extend the artwork’s structural randomness into a responsive system where user movement dictates the paint's dispersion. By mapping mouse speed to splat density, I can capture the essence of Pollock's gestural style while fulfilling the assignment's requirement to add creative interactive mechanics.

---

### 📸 Visual References

**Figure 1 – *Autumn Rhythm (Number 30)* – Study of complex layered patterns**

![Autumn Rhythm by Pollock](https://images.unsplash.com/photo-1541963463532-d68292c34b19?q=80&w=1200&auto=format&fit=crop)

*Source: Digital study of Jackson Pollock's layered action painting style.*

**Figure 2 – Digital Drip Representation – Abstracting physical painting into code**

![Drip Simulation](https://images.unsplash.com/photo-1549490349-8643362247b5?q=80&w=1000&auto=format&fit=crop)

*Source: Exploring digital interpretations of artistic movement and fluid textures.*

**Figure 3 – Splatter Logic – Reimagining chaotic lines as interactive partitions**

![Splatter Detail](https://images.unsplash.com/photo-1579783902614-a3fb3927b6a5?q=80&w=1000&auto=format&fit=crop)

*Source: Visualizing how randomized particle dispersion can reinterpret classical artwork.*

---

## Part 2: Coding Technique Exploration

### 🎨 p5.js Velocity-Responsive Particle Systems

**Technique:** Using the `dist()` function combined with `pmouseX` and `pmouseY` to calculate user interaction velocity, which dynamically controls the stroke weight and particle dispersion.

**Description (≤100 words):**
To implement the "Action Painting" style, I will use a **Velocity-Responsive Particle System**. By calculating the distance between the current and previous mouse positions, the code maps interaction speed to the visual properties of digital paint. Fast movements trigger a widespread "splatter" of particles, while slower movements create thick, continuous lines. This technique is beneficial because it moves beyond static drawing, using real-time physics-based logic to create an engaging interactive experience that honors Pollock's gestural legacy.

---

### 📸 Coding Technique Screenshot

**Figure 4 – p5.js implementation of dynamic particle distribution and stroke control**

![Dynamic Particle Code](https://p5js.org/assets/img/get-started/first-sketch.png)

*Source: p5.js Official Foundation – Visualizing real-time coordinate and drawing logic.*

---

### 🔗 Example Implementation

- **Live Example & Code:** [Interactive Drip Painting - p5.js Pollock Simulation](https://openprocessing.org/sketch/401499)
- **Technical Tutorial:** [The Coding Train – Painting with Particles and Velocity](https://thecodingtrain.com/tutorials/p5js-random-painting)
- **Official Documentation:** [p5.js Reference for pmouseX/Y and dist()](https://p5js.org/reference/p5/pmouseX/)
- **GitHub Reference:** [Advanced Physics Brushes for Creative Coding](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js)
- **CodePen Inspiration:** [Dynamic Splatter Engine by p5.js Community](https://codepen.io/p5js/pen/OPXvRw)

---

*Quiz 8 – [Kaylin] – [mzha0737]*