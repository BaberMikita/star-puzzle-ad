# Playable Ad Prototype: Line Puzzle (Connect the Dots)

## 🎮 Live Demo
[Insert direct link to GitHub Pages here]

## 📝 Overview
An interactive Playable Ad prototype developed with mobile advertising network constraints in mind. 

The core gameplay features a casual puzzle mechanic where the user connects dots in sequence to draw a shape. The experience concludes with an interactive End Card featuring a Call to Action (CTA) button.

## 🛠 Tech Stack
* **Engine:** Phaser 3
* **Language:** JavaScript / TypeScript
* **Build Tool:** Vite + `vite-plugin-singlefile`

## 🚀 Playable Ad Optimizations
This project is strictly optimized to meet the technical requirements of major mobile ad networks (Facebook, Google Ads, Unity Ads, etc.):
* **Single HTML File Output:** All game logic, styles, and markup are compiled into one monolithic `index.html` file.
* **Asset Inlining:** Game graphics and audio (optimized low-bitrate loops) are converted to Base64 and embedded directly into the bundle.
* **Zero Network Requests:** Once the initial HTML loads, the application runs completely offline without any external network calls.
* **Responsive Scaling:** The canvas automatically scales to fit any mobile screen resolution and aspect ratio using `Phaser.Scale.FIT`.
* **Final Build Size:** `[Укажите вес, например: 1.2 MB]` (well within the standard 2-5 MB limit).

## ⚙️ Local Development
Instructions for local setup:

1. Clone the repository: 
   `git clone [repository link]`
2. Install dependencies: 
   `npm install`
3. Run the development server: 
   `npm run dev`

To build the project into a single production file, run:
`npm run build` 
*(The final output file will be generated in the /dist directory).*
