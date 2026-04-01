## 🔗 Live Demo
[View the animation live here](https://emmanuell-dev.github.io/css-3d-cube-animation/)


# Interactive 3D CSS Cube Animation 🧊

A lightweight, high-performance 3D cube animation built entirely with **HTML5** and **CSS3**. This project demonstrates the power of CSS 3D transforms and orchestrated keyframes without the need for JavaScript libraries.

## 🚀 Features
* **Self-Assembling Animation:** Watch the cube faces fly into position from the center of the screen.
* **Pure CSS:** Zero JavaScript dependencies; high performance and low overhead.
* **3D Geometry:** Utilizes `perspective` and `transform-style: preserve-3d` for realistic depth.
* **Infinite Orbit:** A smooth, continuous 360-degree rotation after the initial assembly.
* **Interactive Hover:** Hover over the cube to trigger a fast-spin effect.

---

## 🛠️ Technical Breakdown

### CSS Properties Used:
* **`transform: rotateX() rotateY() translateZ()`**: Used to position each face in a 3D coordinate system.
* **`perspective`**: Set on the container to create a vanishing point and depth perception.
* **`animation-delay`**: Used to stagger the entry of each cube face for a choreographed "building" effect.
* **`linear-gradient`**: Applied to each face for a modern, vibrant aesthetic.

### Project Structure:
* `index.html`: Contains the 3D scene container and the six cube faces (`front`, `back`, `left`, `right`, `top`, `bottom`).
* `style.css`: Contains all the 3D logic, layout, and animation keyframes.

---

## 💻 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/emmanuell-dev/css-3d-cube-animation.git](https://github.com/emmanuell-dev/css-3d-cube-animation.git)
