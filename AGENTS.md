# Project Guidelines — N2T-Next

## Overview
An unofficial, non-commercial, modern interactive remaster of the Nand2Tetris course, hosted at `n2tnext.lukli.dev`.
Features a visual drag-and-drop logic gate simulator, bite-sized guided lessons, and optional live HDL preview.
The current plan features only part 1 of the course, with part 2 planned for future development.

## Tech Stack
- React + TypeScript + Vite
- Tailwind CSS + DaisyUI
- Lucide React (for crisp UI icons)

## UI & Design Rules
- **General UI design principles:** Emphasize simplicity, clarity, and consistency. UI should be intuitive, accessible, and visually appealing, whilst keeping a clean and modern aesthetic.
- **No extensive use of clichés:** No purple/cyan gradients, no glassmorphism (`backdrop-blur`), no heavy drop shadows, no floating blob backgrounds, and no emoji icons in the UI.
- **Restrained dark palette:** Use crisp zinc/neutral surfaces (`#09090b` canvas, `#111113` panels) separated by `1px` hairline borders (`#27272a`) rather than shadows.
- **Color with purpose:** Reserve bright colors strictly for hardware state — e.g., `#22c55e` (emerald) *only* for active `1` signals/wires and passing tests, and `#ef4444` *only* for errors/failing truth-table rows.
- **Workspace-first layout:** The interactive circuit canvas should dominate the viewport (~75–80% of screen space) with slim toolbars and a compact collapsible lesson/HDL panel—never a bloated marketing landing page.
- **Typography:** Clean sans-serif UI text paired with monospace (`JetBrains Mono` / `monospace`) for pin names, truth tables, and HDL.

## Rules & Licensing
- **Code:** Original implementation (MIT). Do not copy/port GPL code from the official Nand2Tetris Java/web tools.
- **Content:** Adapted curriculum is non-commercial under **CC BY-NC-SA 3.0** (credit Noam Nisan & Shimon Schocken, link to `nand2tetris.org`).
- **No Spoilers:** Never hardcode, bundle, or expose completed Nand2Tetris chip solutions in the repo. Verify user circuits dynamically using truth tables / test cases.

## Code & Git Conventions
- Keep components modular: separate simulator engine (`src/simulator/`), lesson data (`src/lessons/`), and UI (`src/components/`).
- Use Conventional Commits (`feat:`, `fix:`, `style:`, `chore:`, `docs:`).