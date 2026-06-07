# Staatliches Bauhaus — Interactive Landing Page

A high-fidelity, standalone interactive landing page celebrating the history, principles, and aesthetic of the **Staatliches Bauhaus** (1919–1933). This project synthesizes modern web technologies with the movement's "Form Follows Function" philosophy.

## 🎨 Overview

This project is contained entirely within `v1.html`. It uses a "standalone" architecture, loading React, Tailwind CSS, and Babel via CDN to provide a rich, interactive experience without a complex build pipeline.

## 🚀 Key Features

### 1. The Core Grid (Hero Section)
- **Interactive Parallax**: A mouse-tracked 3D composition panel featuring the primary Bauhaus geometries (Red Square, Blue Circle, Yellow Triangle).
- **Responsive Navigation**: A dual-navigation system featuring a desktop sidebar "rail" and a mobile-optimized header.

### 2. The Manifesto
- **Dynamic Typography**: Large-scale scrolling "crawler" rows inspired by modernist editorial design.
- **Historical Timeline**: An interactive explorer covering the three major eras of the Bauhaus: Weimar, Dessau, and Berlin.
- **Core Principles**: Cards detailing the four foundational tenets of the movement.

### 3. Geometries Sandbox
- **Red Square (Subdivision)**: A tactile grid that allows users to subdivide and rotate segments, exploring modularity.
- **Blue Circle (Kandinsky Synth)**: A **Web Audio API** powered synthesizer. Translates the "bassy" nature of the blue circle into sine wave frequencies with visual ripple feedback.
- **Yellow Triangle (Transform)**: A playground for testing vector shears, rotations, and scaling.

### 4. The Exhibition & Masters Guild
- **Artifact Gallery**: Reconstructions of iconic works by Kandinsky, Gropius, Bayer, and Klee with hover-driven spatial effects.
- **Master Profiles**: Detailed biographies and workshop histories of the movement's most influential figures.

### 5. Design Laboratory (Workshop)
- **Poster Engine**: A drag-and-drop composition engine where users can spawn, style, layer, and position Bauhaus shapes to create custom posters.
- **Archive Registration**: A functional form to "commit" designs to the academy register.

## 🛠 Technology Stack

- **React 18**: Component-based UI architecture.
- **Tailwind CSS**: Utility-first styling with a custom Bauhaus color palette.
- **Babel Standalone**: On-the-fly JSX transpilation.
- **Web Audio API**: Real-time sound synthesis for the interactive components.
- **SVG Architecture**: Custom-built icons and shapes to eliminate external asset dependencies and ensure crisp scaling.

## 📖 How to Run

Since the project is a standalone HTML file, no installation is required:

1. Open `v1.html` in any modern web browser.
2. Ensure you have an internet connection to load the CDNs (React, Tailwind, Google Fonts).
3. For the best experience, use a desktop browser to interact with the parallax and workshop features.

---
*Crafted for the latest modern paradigms.*
