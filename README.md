# MoleBio

**Interactive Biochemistry & Molecular Biology Learning Platform**

MoleBio is a free, browser-based learning platform designed for students studying biochemistry and molecular biology. It features 54 interactive modules covering major metabolic pathways, molecular structures, signal transduction, and lab techniques — with chemically accurate ball-and-stick molecular viewers, pathway animators, real-time calculators, and inline quizzes.

**Live site:** [molebiolab.github.io/MoleBio](https://molebiolab.github.io/MoleBio)

---

## Features

- **54 learning modules** — glycolysis, pyruvate dehydrogenase, TCA cycle, electron transport chain, oxidative phosphorylation, gluconeogenesis, pentose phosphate pathway, β-oxidation, fatty acid synthesis, amino acid catabolism, urea cycle, nucleotide synthesis, ATP synthase, RNA processing, epigenetics, CRISPR-Cas9, signal transduction (GPCR, RTK/MAPK, JAK-STAT, NF-κB), protein folding, enzyme kinetics, lab techniques, and more
- **Chemically accurate molecular viewers** — ball-and-stick SVG renderings for all 20 amino acids, pathway intermediates, nucleotides, and base pairs
- **Pathway animators** — step through each enzyme-catalyzed reaction with molecular structures, energy accounting, and regulation info
- **3D protein viewer** — fetch any structure from RCSB PDB with ribbon, ball-and-stick, and surface rendering via Three.js
- **Real-time calculators** — DNA melting temperature (Tm), protein MW/pI, unit & molarity converter, Michaelis-Menten curve fitter, codon translator
- **Interactive tools** — secondary structure builder, Ramachandran plot explorer, central dogma flow, sequence converter, micropipette viewer, gel electrophoresis, Western blot
- **Inline quizzes** — "Check Your Understanding" questions at the end of every module with immediate feedback
- **Cross-module links** — terms like "TCA cycle," "β-oxidation," and "GPCR" are clickable links between modules
- **Quick Reference cheat sheet** — key numbers, ATP yields, enzyme names, and amino acid classifications for exam review
- **Anki CSV export** — generate flashcard decks from any module
- **Progress tracking** — per-topic progress bars on the homepage
- **Deep-linkable modules** — share direct links to any topic via URL hash routing
- **Keyboard shortcuts** — efficient navigation for power users
- **PWA support** — installable with offline fallback
- **Responsive design** — desktop three-column layout and mobile-optimized panel switching
- **Accessible** — keyboard navigation, 56 ARIA labels, skip-nav link, screen reader support

## Tech Stack

Single-file vanilla HTML/CSS/JavaScript (~11,300 lines) — no build step, no dependencies, no framework. Just open `index.html` in a browser.

- Three.js (r128) for 3D protein rendering
- Canvas API for kinetics plots and Ramachandran plots
- SVG for all molecular structures and pathway diagrams
- Google Analytics for anonymous usage data

## Usage

Visit the live site at [molebiolab.github.io/MoleBio](https://molebiolab.github.io/MoleBio), or clone and open locally:

```bash
git clone https://github.com/MoleBioLab/MoleBio.git
open index.html
```

## Feedback

Found a scientific error? Have a feature suggestion?

- Open an [issue](https://github.com/MoleBioLab/MoleBio/issues) on this repo
- Or reach out via the About page on the live site

## Author

**Dylan S. Blohm** — concept, curation, scientific direction, and design. Coded with Anthropic Claude.

© 2026 Dylan S. Blohm. All rights reserved.
