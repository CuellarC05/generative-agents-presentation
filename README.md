# Generative Agents — Interactive Presentation

An interactive, single-file HTML slide deck explaining **"Generative Agents: Interactive Simulacra of Human Behavior"** (Park et al., 2023) — the Stanford paper that pioneered LLM-driven agents with memory, reflection, and planning.

**▶ Live demo:** https://cuellarc05.github.io/generative-agents-presentation/

---

## About this project

This deck was built as a final group presentation (Group 23) for **"An Introduction to Agent-Based Modeling"** by the Santa Fe Institute / Complexity Explorer.

**My contribution:** I built the HTML/CSS/JS deck itself and wrote most of the content — translating the paper's architecture (Memory Stream → Reflection → Planning) and findings into the interactive slides you see here.

## What's in the deck

The presentation walks through:

- **Traditional ABM vs. Generative ABM** — decision trees vs. prompt-driven cognition
- **The Cognitive Flywheel** — how memory, reflection, and planning feed each other
- **The three core modules** — Memory Stream (the diary), Reflection (the inner voice), Planning (the to-do list)
- **Emergent behaviors** — information diffusion, relationship formation, and coordination without instructions (the Valentine's Day party experiment)
- **Ablation results** — what breaks when you remove each module
- **Strengths and limitations** — where the architecture shines and where it struggles

## Tech

- Pure HTML, CSS, and vanilla JS — no build step, no dependencies
- Single file (`index.html`), ~60 KB
- Keyboard navigation (arrow keys) and on-screen controls

## Run locally

Just open `index.html` in any modern browser. No server required.

## Reference

Park, J. S., O'Brien, J. C., Cai, C. J., Morris, M. R., Liang, P., & Bernstein, M. S. (2023). *Generative Agents: Interactive Simulacra of Human Behavior.* arXiv:2304.03442.
