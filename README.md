# Boid Simulation

An interactive simulation of flocking behavior based on Craig Reynolds's "Boids" algorithm. This project demonstrates emergent behavior by applying a simple set of rules to individual agents, resulting in complex, life-like swarm intelligence. You can control a predator to interact with the flock and manipulate environmental factors like wind.

**Live Demo:** [https://jalpan04.github.io/boid-simulation/](https://www.google.com/search?q=https://jalpan04.github.io/boid-simulation/)

## 🌟 Features

  * **Classic Boids Algorithm**: Simulates three fundamental rules:
      * **Alignment**: Boids steer towards the average heading of their local flockmates.
      * **Cohesion**: Boids steer to move toward the average position of local flockmates.
      * **Separation**: Boids steer to avoid crowding local flockmates.
  * **Interactive Predator**: You control a predator boid to hunt and scatter the flock.
  * **Adjustable Parameters**: Fine-tune the simulation with a settings panel to control the weight of alignment, cohesion, and separation forces.
  * **Wind Simulation**: Introduce a directional wind force that affects the movement of all boids. The wind direction can be easily adjusted with a visual dial.
  * **Debug Visuals**: Toggle visual aids to see the perception radius and the force vectors (alignment, cohesion, separation, flee) for each boid, offering insight into the algorithm's mechanics.
  * **User Controls**:
      * **Arrow Keys**: Control the movement of the predator.
      * **Spacebar**: Pause and resume the simulation.
  * **Responsive Design**: The simulation canvas dynamically adjusts to the browser window size.

## 🚀 How to Use

1.  **Control the Predator**: Use the **Arrow Keys** on your keyboard to move the red predator boid around the canvas. Watch how the flock reacts to your presence.
2.  **Pause the Simulation**: Press the **Spacebar** to pause or resume the simulation at any time.
3.  **Adjust Settings**:
      * Click the **menu button** (hamburger icon) at the top-right corner to open the settings panel.
      * Use the sliders to adjust the **Alignment**, **Cohesion**, and **Separation** forces.
      * Toggle the **Wind** checkbox to enable or disable the wind force.
      * Click and drag the knob on the **Wind Direction** dial to change the wind's direction.
      * Toggle the **Debug Visuals** checkbox to see the forces acting on each boid.

## 🛠️ Technologies Used

  * **HTML5**: For the basic structure of the simulation.
  * **TailwindCSS**: For styling the user interface and controls.
  * **JavaScript (ES6+)**: For the core simulation logic, including vector math and boid behaviors.

## 🖼️ Screenshots

*(You can add screenshots of your simulation here to showcase its features.)*

**Example of the simulation with debug visuals turned on:**

**The settings panel with adjustable parameters:**

## 📂 How to Run Locally

No special setup is required\! Simply clone or download this repository and open the `index.html` file in your favorite web browser.

```bash
git clone https://github.com/jalpan04/boid-simulation.git
cd boid-simulation
# Open index.html in your browser
```
