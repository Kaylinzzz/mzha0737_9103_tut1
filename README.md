# Quiz 8 – Design Research

## Part 1: Imaging Technique Inspiration

### ⬛ Piet Mondrian – *De Stijl & Neoplasticism* (1930s)

**Inspiration Source:** *Composition II in Red, Blue, and Yellow* by Piet Mondrian (1930), oil on canvas, Kunsthaus Zürich.

**Description (≤100 words):**

The aspect I most want to incorporate is Mondrian’s **asymmetrical, minimalist grid partitioning**. His rigid yet harmonious division of space using heavy industrial lines creates a striking visual balance. For my project, I want to evolve this static grid into a dynamic interactive layout that fractures based on user input, utilizing clean lines and a matte, monochrome palette. This is beneficial because it allows me to explore algorithmic structural generation and precise, grid-based visual layouts, matching the assignment’s goal to create engaging, highly structured interactive media with strong architectural aesthetics.

---

### 📸 Visual References

**Figure 1 – *Composition II in Red, Blue, and Yellow* (1930) – Mondrian's iconic asymmetrical grid layout**

![Composition II in Red, Blue, and Yellow by Mondrian](https://upload.wikimedia.org/wikipedia/commons/a/a4/Piet_Mondriaan%2C_1930_-_Mondrian_Composition_II_in_Red%2C_Blue%2C_and_Yellow.jpg)

*Source: Wikimedia Commons – Piet Mondrian, Composition II in Red, Blue, and Yellow (1930), public domain*

**Figure 2 – *Composition with Grid 9* (1919) – A denser structural exploration of geometric spatial division**

![Composition with Grid 9](https://upload.wikimedia.org/wikipedia/commons/3/36/Piet_Mondriaan_-_Composition_with_Grid_9_-_Google_Art_Project.jpg)

*Source: Wikimedia Commons – Piet Mondrian, Composition with Grid 9 (1919), public domain*

---

## Part 2: Coding Technique Exploration

### 🌳 Quadtree Spatial Partitioning Algorithm

**Technique:** Implementing a **Quadtree data structure** to recursively subdivide a 2D canvas into four smaller quadrants (nodes) based on a data capacity limit, such as cursor proximity or interactive particle density.

**Description (≤100 words):**

The Quadtree algorithm recursively subdivides space, providing a highly technical method to generate Mondrian-esque geometric subdivisions programmatically. By rendering the boundaries of each Quadtree node, the canvas dynamically fractures into smaller, perfect rectangles wherever the user interacts. This technique is brilliant for achieving clean, architectural grid structures without relying on unpredictable randomness or noise. It allows for the real-time exploration of minimalist spatial layouts, offering both a mathematically rigorous coding challenge and a sophisticated, highly artistic visual output.

---

### 📸 Coding Technique Screenshot

**Figure 3 – A Quadtree algorithm dynamically dividing space based on coordinate density**

![Quadtree Visualization in p5.js](https://img.youtube.com/vi/OJxEcs0w_kE/maxresdefault.jpg)

*Source: The Coding Train – "Coding Challenge #98.1: Quadtree", showing the recursive grid boundaries drawn in p5.js*

---

### 🔗 Example Implementation

- **Live Example & Code:** [Interactive Quadtree Sketch on p5.js Web Editor by Daniel Shiffman – mouse interaction dynamically subdivides the grid](https://editor.p5js.org/codingtrain/sketches/g7LnKQ4cg)
- **Video Tutorial:** [The Coding Train – Coding Challenge #98.1: Quadtree Part 1](https://thecodingtrain.com/challenges/98-quadtree)
- **Algorithm Documentation:** [Wikipedia – Quadtree Data Structures](https://en.wikipedia.org/wiki/Quadtree)
- **Advanced Application Example:** [Quadtree Image Compression Simulation by Michael Chang](https://openprocessing.org/sketch/394741)

---

*Quiz 8 – [Kaylin] – [mzha0737]*