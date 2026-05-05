# Quiz 8 – Design Research

## Part 1: Imaging Technique Inspiration

### ⚡ Glitch Art & Kinetic Pixel Sorting

**Inspiration Source:** The experimental digital works of **Kim Asendorf** (creator of the first pixel sorting algorithm) and the interactive installations by **Refik Anadol**.

**Description (≤100 words):**

I am inspired by **Pixel Sorting**, a glitch art technique that reorders the pixels in an image based on specific attributes like brightness, hue, or saturation. Unlike static filters, I want to implement this as a kinetic, interactive process. The visual "melting" effect creates a haunting, ethereal transition between order and chaos. In my project, user movement will act as a "digital brush," dragging and sorting pixels in real-time. This technique is beneficial because it utilizes p5.js’s ability to manipulate the pixel array directly, creating high-level artistic results that feel sophisticated and contemporary.

---

### 📸 Visual References

**Figure 1 – Classic Pixel Sorting – A landscape being "melted" via brightness-based sorting**

![Pixel Sorting Art](https://raw.githubusercontent.com/kimasendorf/ASDFPixelSort/master/example.png)

*Source: Kim Asendorf – ASDF Pixel Sort, the foundational aesthetic for digital glitch art.*

**Figure 2 – Interactive Glitch – Real-time distortion of portraiture using pixel manipulation**

![Interactive Glitch](https://www.seditionart.com/media/00/08/94/r-kim-asendorf-the-original-pixel-sort-1.jpg)

*Source: Sedition Art – "The Original Pixel Sort" by Kim Asendorf.*

**Figure 3 – Kinetic Abstraction – Sorting applied to fluid shapes to create a sense of motion**

![Kinetic Sorting](https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/40960555355603.598160088812c.gif)

*Source: Behance – Generative glitch studies exploring color and drag.*

---

## Part 2: Coding Technique Exploration

### 💻 Image Pixel Array Manipulation

**Technique:** Accessing and modifying the **`pixels[]` array** in p5.js. By loading an image or webcam feed into a buffer, the code iterates through rows or columns and applies a **sorting algorithm** (like `sort()`) to pixel values based on their `brightness()`.

**Description (≤100 words):**

The core coding technique involves manipulating the low-level pixel data of the canvas. By calling `loadPixels()`, we gain access to a 1D array representing every RGBA value on screen. I will use a conditional sorting logic: if a pixel's brightness exceeds a certain threshold, the code will swap its position with neighboring pixels. By linking the "sorting threshold" or "sorting direction" to the `mouseX` and `mouseY` coordinates, the user can interactively "smear" the image, creating a responsive, high-fidelity visual experience that bridges the gap between photography and generative abstraction.

---

### 📸 Coding Technique Screenshot

**Figure 4 – Pixel Sorting algorithm logic visualized in p5.js**

![Pixel Sorting Code Screenshot](https://happycoding.io/tutorials/p5js/images/pixel-sorting-4.png)

*Source: Happy Coding – "Pixel Sorting in p5.js", demonstrating the transition from raw image to sorted pixels.*

---

### 🔗 Example Implementation

- **Live Example & Code:** [Interactive Pixel Sorter on p5.js Web Editor – Drag the mouse to sort pixels](https://editor.p5js.org/Kallirroi/sketches/BJx9GqS_X)
- **Technical Tutorial:** [Happy Coding – Pixel Sorting Tutorial for p5.js](https://happycoding.io/tutorials/p5js/images/pixel-sorting)
- **Reference Repository:** [ASDF Pixel Sort – Original Processing source code by Kim Asendorf](https://github.com/kimasendorf/ASDFPixelSort)
- **Advanced Video Guide:** [The Coding Train – Pixel Array Manipulation and Sorting Patterns](https://thecodingtrain.com/challenges/interactive-images)

---

*Quiz 8 – [Your Name] – [Your Student ID]*