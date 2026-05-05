# Quiz 8 – Design Research

## Part 1: Imaging Technique Inspiration

### 🕸️ Cellular Tessellation – Voronoi Aesthetics

**Inspiration Source:** The architectural pavilions of **biomorphic design** and the generative "Cellular Forms" series by digital artist **Andy Lomas**.

**Description (≤100 words):**

I am inspired by **Voronoi Tessellation**, a mathematical method of partitioning space into cells based on distance to specific seed points. This creates a striking, organic aesthetic that mirrors structures found in nature, such as leaf veins or cell membranes. For my interactive project, I want to use the user's cursor as a dynamic seed point that "re-carves" the geometry of the canvas in real-time. This technique is beneficial because it moves beyond standard grid layouts, offering a high-level architectural complexity that is both mathematically rigorous and visually mesmerizing for an interactive audience.

---

### 📸 Visual References

**Figure 1 – Voronoi Diagram – The mathematical division of space into organic cells**

![Voronoi Diagram Structure](https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/Euclidean_Voronoi_diagram.svg/1024px-Euclidean_Voronoi_diagram.svg.png)

*Source: Wikimedia Commons – Standard Euclidean Voronoi visualization.*

**Figure 2 – Biomorphic Architecture – Real-world application of Voronoi patterns in design**

![Voronoi Architecture](https://images.adsttc.com/media/images/5013/f73e/28ba/0d44/9200/0175/large_jpg/stringio.jpg?1414440939)

*Source: ArchDaily – Voronoi-based structural pavilion design.*

**Figure 3 – Generative Mesh – High-fidelity geometric abstraction using Voronoi logic**

![Voronoi Mesh Art](https://raw.githubusercontent.com/fogleman/voronoi/master/examples/output.png)

*Source: Michael Fogleman – Computational geometry study of Voronoi meshes.*

---

## Part 2: Coding Technique Exploration

### 📐 Fortune’s Algorithm & Delaunay Triangulation

**Technique:** Implementing a **Delaunay Triangulation** as a dual-graph to generate the Voronoi cells, using the `d3-delaunay` library or native p5.js vertex manipulation.

**Description (≤100 words):**

The core coding challenge lies in the real-time calculation of cell boundaries. By treating the `mouseX` and `mouseY` coordinates as an active "site" in a Delaunay Triangulation, the program must recalculate the circumcenters of triangles to find the Voronoi vertices. This requires efficient array handling and geometric logic. In p5.js, I will use `beginShape()` and `vertex()` to render these cells. This allows for powerful interaction: as the user moves their mouse, the entire "ecosystem" of cells shifts and vibrates, creating a responsive digital fabric that feels alive and physically grounded.

---

### 📸 Coding Technique Screenshot

**Figure 4 – p5.js implementation of interactive Voronoi cells**

![p5.js Voronoi Code](https://openprocessing.org/sketch/519548/screenshot)

*Source: OpenProcessing – "Interactive Voronoi" by Gorilla Sun, demonstrating real-time cell updates.*

---

### 🔗 Example Implementation

- **Live Example & Code:** [Interactive Voronoi on p5.js Web Editor – Mouse interaction dynamically reshapes the grid](https://editor.p5js.org/p5js-examples/sketches/Math__Voronoi_Diagram)
- **Technical Tutorial:** [The Coding Train – Understanding Delaunay and Voronoi Algorithms](https://thecodingtrain.com/challenges/interactive-geometry)
- **Documentation:** [D3-Delaunay Documentation – High-performance spatial partitioning for JavaScript](https://github.com/d3/d3-delaunay)
- **Advanced Code Reference:** [Voronoi Stippling and Centroidal Maps in p5.js](https://openprocessing.org/sketch/1041004)

---
*Quiz 8 – [Kaylin] – [mzha0737]*