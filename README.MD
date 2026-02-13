# DoodleDev



### [Launch DoodleDev](https://doodledev.app)

**The web shouldn't make your designs look worse.**

DoodleDev is a visual compiler built to bridge the gap between high fidelity design and production engineering. It allows you to build complex front end interfaces and compile them into clean, zero dependency Web Components with every detail intact.

## The Philosophy
Most web tools force you to compromise your vision to fit into a framework. DoodleDev was built on a simple premise: **Figma outputs pictures. DoodleDev outputs software.**

We reject the idea of "vibecoding" or AI guessing. This is a precision instrument that establishes a direct link between visual intent and binary execution. If you can design it, the engine can run it.

## Features
* **Visual Compiler:** Turns vector designs directly into optimized, production ready HTML/CSS/JS.
* **Zero Dependency Runtime:** Exports stand alone Web Components that require no React, Vue, or external libraries to run.
* **Physics Based Animation:** Includes a custom, lightweight animation engine for sub pixel interpolation and 60fps performance.
* **State Aware:** Built in logic for hover states, click events, and complex transitions without writing code.
* **Vector Precision:** Features a robust boolean shape builder and bezier logic for exact geometry control.

## Usage
DoodleDev generates standard Custom Elements that drop into any project with zero friction.

1. Export your component from DoodleDev.
2. Drop the file into your project.
3. Use the tag.

```html
<script type="module" src="./doodle-export.js"></script>

<doodle-component></doodle-component>
