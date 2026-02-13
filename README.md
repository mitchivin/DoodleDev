# DoodleDev

### [Launch DoodleDev](https://doodledev.app)

**The web shouldn't make your designs look worse.**

DoodleDev is a visual compiler built to bridge the gap between high fidelity design and production engineering. It allows you to build complex front end interfaces and compile them into clean, zero dependency Web Components with every detail intact.

<img width="1704" height="908" alt="Screenshot 2026-02-13 093524" src="https://github.com/user-attachments/assets/1f816a06-742a-43e2-b056-bcaabbd491ec" />

## The Philosophy
Most web tools force you to compromise your vision to fit into a framework. DoodleDev was built on a simple premise: **Figma outputs pictures. DoodleDev outputs code.**

We reject the idea of "vibecoding" or AI guessing. This is a precision instrument that establishes a direct link between visual intent and binary execution. If you can design it, the engine can run it.

<img width="1704" height="909" alt="Screenshot 2026-02-13 093508" src="https://github.com/user-attachments/assets/18d94511-26f7-4019-b983-eccdf0854e60" />

## Features
* **Visual Compiler:** Turns vector designs directly into optimized, production ready HTML/CSS/JS.
* **Zero Dependency Runtime:** Exports stand alone Web Components that require no React, Vue, or external libraries to run.
* **Physics Based Animation:** Includes a custom, lightweight animation engine for sub pixel interpolation and 60fps performance.
* **State Aware:** Built in logic for hover states, click events, and complex transitions without writing code.
* **Vector Precision:** Features a robust boolean shape builder and bezier logic for exact geometry control.

<img width="1706" height="906" alt="Screenshot 2026-02-13 093604" src="https://github.com/user-attachments/assets/487198cf-0690-485b-90fa-c3fe2355edc5" />

## Usage
DoodleDev generates standard Custom Elements that drop into any project with zero friction.

1. Export your component from DoodleDev.
2. Drop the file into your project.
3. Use the tag.

```html
<script type="module" src="./doodle-export.js"></script>

<doodle-component></doodle-component>
