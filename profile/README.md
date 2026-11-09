<div align="center">
  <img src="https://feascript.com/assets/feascript-banner.svg" width="100%" alt="FEAScript: A JavaScript finite element library, for the web." />
</div>

### What is FEAScript?

<img src="https://feascript.com/assets/cold-plate-logo-results-and-mesh.gif" align="right" width="260" alt="Heat conduction results and mesh around the FEAScript logo">

<img src="https://feascript.com/assets/favicon.ico" alt="FEAScript Icon" width="18" height="18"> **[FEAScript](https://feascript.com/) is a finite element simulation library developed in JavaScript.** It runs engineering simulations in the browser or in Node.js, with no desktop software to install.

🎯 **Our goal is a powerful JavaScript API for FEM**, so that developers can build professional-grade simulation tools that work on any device, anywhere.

⚙️ **What it solves:** heat conduction, creeping (Stokes) flow, Euler–Bernoulli beams, front propagation and general-form PDEs (linear and nonlinear), with Gmsh mesh import, CPU/WebGPU solvers and web worker support.

> 🚧 FEAScript is under active development, so its API may change between releases.

### Get started

🚀 Use it in a browser page with a single import, or install it from [npm](https://www.npmjs.com/package/feascript) with `npm install feascript`:

```html
<script type="module">
  import { FEAScriptModel } from "https://cdn.jsdelivr.net/gh/FEAScript/FEAScript-core/dist/feascript.esm.js";
</script>
```

### The FEAScript ecosystem

- The main library, [FEAScript core](https://github.com/FEAScript/FEAScript-core), distributed under the MIT license, with [unit, verification and regression tests](https://github.com/FEAScript/FEAScript-core/tree/main/tests) to check numerical accuracy.
- The [documentation](https://docs.feascript.com) ([source](https://github.com/FEAScript/FEAScript-documentation)), covering the API, usage guides and theory, under CC BY 4.0.
- The examples, provided in multiple formats:
  - [Node.js implementations](https://github.com/FEAScript/FEAScript-core/tree/main/examples), showcasing direct API usage.
  - [Pens](https://codepen.io/FEAScript) on CodePen, for live, editable demos in the browser.
  - [Notebooks](https://github.com/FEAScript/FEAScript-Scribbler-examples) on [Scribbler](https://scribbler.live/), an interactive JavaScript notebook tool.
- The [benchmarks](https://github.com/FEAScript/FEAScript-benchmark), comparing FEAScript with established finite element software on accuracy, run time and memory, and tracking its speed-up across versions, under the MIT license.
- The [website](https://feascript.com) ([source](https://github.com/FEAScript/FEAScript-website)) and [blog](https://blog.feascript.com) ([source](https://github.com/FEAScript/FEAScript-blog)), both licensed under CC BY 4.0, with tutorials, updates and various resources.
- [Tri's Lab by FEAScript](https://lab.feascript.com) ([source](https://github.com/FEAScript/FEAScript-tris-lab)), a playful place for students and beginners to discover the finite element method through a pixel-art game and block-based missions, with code under the MIT license and writing and art under CC BY 4.0.

### Get involved

💬 Join the conversation on [Discord](https://discord.gg/3DVjNcuW4f) or follow us on [LinkedIn](https://www.linkedin.com/company/feascript/) and [Bluesky](https://bsky.app/profile/feascript.com).
<br>🛠️ Contributions are welcome! See the [contributing guide](https://github.com/FEAScript/FEAScript-core/blob/main/CONTRIBUTING.md) to get started.
<br>📨 Join the [mailing list](https://mailchi.mp/e29600955ffe/join-the-mailing-list) to receive project updates and news.
<br>❤️ Support the project via [GitHub Sponsors](https://github.com/sponsors/FEAScript) or [Liberapay](https://liberapay.com/FEAScript/donate).
