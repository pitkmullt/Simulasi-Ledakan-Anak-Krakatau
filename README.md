# 🌋 Simulasi Erupsi Anak Krakatau (Physics-Based Projectile Motion)

A web-based interactive simulation modeling volcanic material trajectory (tephra) during the eruption of Mt. Anak Krakatau. Built with HTML5 Canvas, JavaScript, and numerical physics equations to simulate projectile motion under the influence of air resistance (drag force).

🚀 **Live Demo:** [pitkmullt.github.io/Simulasi-Ledakan-Anak-Krakatau]
---

## 📌 Features

* **Real-time Trajectory Simulation:** Visualizes volcanic particle movement dynamically frame-by-frame.
* **Physics Engine:** Incorporates gravity ($g$), initial ejection velocity ($v_0$), launching angle ($\theta$), and aerodynamic drag force ($F_d$).
* **Interactive Parameters:** Adjust environmental and eruption variables (e.g., initial velocity, mass, wind, angle) to observe different simulation outcomes.
* **Data Visualization:** Interactive graphs showing height ($y$), distance ($x$), and time-series physics calculations.
* **Responsive UI:** Clean, modern interface designed for desktop and mobile browsers.

---

## ⚙️ Physics & Mathematical Model

The simulation calculates the motion of volcanic ejecta using second-order differential equations for 2D kinematics with quadratic air resistance:

1. **Velocity Components:**
   $$v_x = v_0 \cdot \cos(\theta)$$
   $$v_y = v_0 \cdot \sin(\theta)$$

2. **Drag Force:**
   $$F_d = \frac{1}{2} C_d \cdot \rho \cdot A \cdot v^2$$

3. **Numerical Integration:**
   Real-time position updates $(x, y)$ calculated per tick step using numerical methods to ensure smooth visual rendering on Canvas.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Graphics & Rendering:** HTML5 Canvas API
* **Deployment:** GitHub Pages

---

## 🚀 Getting Started

To run this project locally:

1. Clone this repository:
   ```bash
   git clone [https://github.com/pitkmullt/Simulasi-Ledakan-Anak-Krakatau.git]
