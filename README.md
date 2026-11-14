# N2T-Next

> **A modern, interactive way to experience the Nand2Tetris course.**  
> *From a single `NAND` gate to a working computer — reimagined with a visual circuit builder and bite-sized guided lessons.*

🌐 **Live Site:** [n2tnext.lukli.dev](https://n2tnext.lukli.dev)

> [!NOTE]
> **Unofficial Community Project:** `N2T-Next` is an independent, non-commercial interactive remaster and is not affiliated with or endorsed by the official Nand2Tetris creators.

---

## What is N2T-Next?

The original [Nand2Tetris](https://www.nand2tetris.org/) course is one of the best computer science curricula ever made, but its tooling and documentation can feel dense and dated. **N2T-Next** brings it into a modern, interactive workspace:

- **Visual Drag-and-Drop Simulator:** Build logic gates by wiring `NAND` chips on an interactive canvas and watch `0`s and `1`s propagate in real time.
- **Bite-Sized Guided Lessons:** Short, clear, interactive steps instead of 20-page walls of text.
- **Progressive Unlocking:** Every chip you solve (`Not`, `And`, `Or`, `Xor`, `Mux`, `DMux`, ...) is saved and unlocked as a reusable component for the next challenge.
- **Live HDL Sync (Optional):** Peek at the equivalent Nand2Tetris HDL generated from your visual circuit.
- **Instant Verification:** Built-in truth-table test runner — no external Java tools or manual file loading required.

---

## Tech Stack

- **Frontend:** React + TypeScript + Vite
- **Styling:** Tailwind CSS + DaisyUI

---

## Running Locally

```bash
# Install dependencies
npm install

# Start the development server
npm run dev
```

---

## Licensing & Attribution

- **Source Code:** Licensed under the [MIT License](./LICENSE). All simulator and UI code is written from scratch.
- **Course Content & Curriculum:** Adapted from *The Elements of Computing Systems* (Nand2Tetris) by **Noam Nisan and Shimon Schocken** ([nand2tetris.org](https://www.nand2tetris.org/)), shared for non-commercial educational use under the [**CC BY-NC-SA 3.0**](https://creativecommons.org/licenses/by-nc-sa/3.0/) license.
- **No Spoilers:** In accordance with the authors' request, this repository does not include completed chip solutions.