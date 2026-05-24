# Frankenstein Camera Simulator 3D 📷⚙️

**A web-based 3D simulator for calculating and visualizing custom DIY medium and large format cameras.**

Created by **Dragan Bojovic** License: **GNU General Public License v3.0 (GPLv3)**

https://draganito.github.io/lens_sim/



---

## 📖 About the Project

This simulator was originally developed as an engineering tool during the creation of the **Miluka** – a custom medium-format camera utilizing M65 helicoids and Graflok 23 standard backs (compatible with Mamiya RB67 6x8, 6x9, or sheet film). 

Building "Frankenstein" cameras (combining vintage lenses with custom 3D-printed/CNC bodies) often involves heavy trial-and-error, especially regarding mechanical clearance, flange focal distance (FFD), and unexpected vignetting. This tool solves those issues by simulating the optical and physical realities directly in your browser.

## ✨ Key Features

* **Real-time 3D Visualization:** See exactly how the light cone interacts with the lens barrel and helicoid using the built-in Three.js engine.
* **Mechanical Collision Detection:** Warns you if your specific lens's rear element (e.g., oversized elements like the Super Angulon 90mm f/8) won't fit through standard helicoids (e.g., 61mm inner diameter).
* **Advanced Vignetting Analysis:** * Calculates and visually renders **mechanical vignetting** on the film plane.
  * Calculates natural lens falloff (Cos⁴ law).
  * Shows exact coverage percentages for formats like 6x6, 6x7, 6x8, 6x9, and 4x5".
* **Independent Lens Offset:** Define the physical position of the rear element independently from the Flange Focal Distance (FFD), crucial for symmetrical wide-angle lens designs.
* **Optical Math Engine:** Automatically computes Depth of Field (DoF), Circle of Confusion (CoC), and diffraction limits based on focus distance and working aperture.
* **URL State Saving:** All parameters are saved in the URL, making it easy to bookmark or share specific camera builds with the community.

## 🚀 How to Use

The simulator is entirely client-side and requires no backend or installation.

1. Clone this repository or download the source code.
2. Open the `index.html` file in any modern web browser.
3. Input your target lens parameters (Focal Length, Max Aperture, Physical Rear Diameter).
4. Set your desired camera body constraints (Flange distance, Helicoid size).
5. Use the **"Optimize Flange & Helicoid for 100% Light"** button to find the ideal structural distances for your custom build.

## 🛠️ Built With

* HTML5 / CSS3 / Vanilla JavaScript
* [Three.js](https://threejs.org/) (for 3D rendering)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! If you are designing your own DIY camera and find a bug or need a specific format added, feel free to open an issue or submit a pull request.

## 📝 License

This project is open-source and released under the **GNU General Public License v3.0**. 

You may copy, distribute, and modify the software as long as you track changes/dates in source files. Any modifications to or software including (via compiler) GPL-licensed code must also be made available under the GPL along with build & install instructions.

---
*Happy building and prototyping!* 🛠️📷

