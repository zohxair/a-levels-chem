# 9701 Chemistry Notes

A free, interactive revision website for **Cambridge International AS & A Level Chemistry (9701)**. It covers every topic in the syllabus with detailed notes, worked examples, reaction mechanisms, diagrams, interactive tools and exam-style questions with mark schemes.

The whole site is a single HTML file. There is nothing to install and no build step: open it in a browser, or host it on GitHub Pages.

---

## Features

- **All 37 syllabus topics** in two tabs: AS Level (topics 1–22) and A Level (topics 23–37).
- **141 multiple-choice questions**: Paper 1 style questions for AS, and quick checks for the A Level topics. They mark themselves instantly and explain the answer.
- **62 structured questions** in the style of Papers 2, 4 and 5. Each has a lined answer box and a mark scheme laid out point by point, the way examiners write them (**M1, M2, …**).
- **69 worked examples**: mole calculations, Hess cycles, Born–Haber cycles, *K*<sub>c</sub> and *K*<sub>p</sub>, pH and buffers, *K*<sub>sp</sub>, electrode potentials and the Nernst equation, rate equations, titrations, organic synthesis routes and spectra.
- **Over 120 diagrams**, drawn as sharp SVG that follows the light or dark theme: dot-and-cross diagrams, curly-arrow mechanisms (S<sub>N</sub>1, S<sub>N</sub>2, electrophilic addition and substitution, nucleophilic addition, addition–elimination), energy profiles, Boltzmann distributions, Born–Haber cycles, titration curves, crystal lattices, d-orbital splitting, IR, mass and NMR spectra, and chromatograms.
- **Key equations** tagged **"Learn it"** where they must be memorised.
- **13 interactive tools:**
  | Tool | Topic |
  |---|---|
  | Periodic table with block, electronegativity and ionisation energy views | 1. Atomic structure, 9. Periodicity |
  | Electron configuration builder for atoms and ions (Z = 1 to 36), with orbital boxes | 1. Atomic structure |
  | Molar mass, percentage composition and empirical formula calculator | 2. Stoichiometry |
  | 3D VSEPR shape explorer you can rotate | 3. Chemical bonding |
  | Titration simulator with exact pH curves and indicator choice | 7. Equilibria, 25. Equilibria |
  | Boltzmann distribution with temperature and catalyst | 8. Reaction kinetics |
  | Organic reaction map with a route finder (AS, and AS + A Level) | 21. and 36. Organic synthesis |
  | Chlorine and bromine isotope patterns, and the M+1 carbon count | 22. Analytical techniques |
  | ΔG = ΔH − TΔS explorer | 23. Chemical energetics |
  | Electrochemical cell builder: E<sub>cell</sub>, overall equation, ΔG and the Nernst equation | 24. Electrochemistry |
  | pH calculator that shows its working | 25. Equilibria |
  | Order of reaction explorer (zero, first and second order) | 26. Reaction kinetics |
  | NMR spectrum viewer with n + 1 splitting, ¹³C mode and the D<sub>2</sub>O shake | 37. Analytical techniques |
- **Search** across every topic and section.
- **Progress tracking**: mark topics as revised (saved in your browser only).
- **Light and dark themes**, a layout that works on phones, and keyboard navigation.

## Syllabus coverage

The content follows the Cambridge 9701 syllabus for **2025–2027**. The **2028–2030** syllabus has no significant changes to the subject content, so the site applies to both.

| AS Level | A Level |
|---|---|
| 1. Atomic structure | 23. Chemical energetics |
| 2. Atoms, molecules and stoichiometry | 24. Electrochemistry |
| 3. Chemical bonding | 25. Equilibria |
| 4. States of matter | 26. Reaction kinetics |
| 5. Chemical energetics | 27. Group 2 |
| 6. Electrochemistry | 28. Chemistry of transition elements |
| 7. Equilibria | 29. An introduction to A Level organic chemistry |
| 8. Reaction kinetics | 30. Hydrocarbons |
| 9. The Periodic Table: chemical periodicity | 31. Halogen compounds |
| 10. Group 2 | 32. Hydroxy compounds |
| 11. Group 17 | 33. Carboxylic acids and derivatives |
| 12. Nitrogen and sulfur | 34. Nitrogen compounds |
| 13. An introduction to AS Level organic chemistry | 35. Polymerisation |
| 14. Hydrocarbons | 36. Organic synthesis |
| 15. Halogen compounds | 37. Analytical techniques |
| 16. Hydroxy compounds | |
| 17. Carbonyl compounds | |
| 18. Carboxylic acids and derivatives | |
| 19. Nitrogen compounds | |
| 20. Polymerisation | |
| 21. Organic synthesis | |
| 22. Analytical techniques | |

The overview pages also summarise the papers: Paper 1 (multiple choice), Paper 2 (AS structured questions), Paper 3 (practical skills), Paper 4 (A Level structured questions) and Paper 5 (planning, analysis and evaluation).

## Getting started

### Open it locally

Download `index.html` and double-click it. It opens in any modern browser (Chrome, Edge, Firefox, Safari).

### Host it on GitHub Pages

1. Create a new repository, for example `9701-chemistry-notes`, and upload `index.html` (rename `chemistry-9701.html` to `index.html`) and this `README.md`.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute or two, the site is live at `https://zohxair.github.io/9701-chemistry-notes/` (or `https://<your-username>.github.io/<repository-name>/`).

### Linking to a topic

Every topic and section has its own link, so you can send students straight to it:

```
https://zohxair.github.io/9701-chemistry-notes/#as-14    → AS topic 14, Hydrocarbons
https://zohxair.github.io/9701-chemistry-notes/#a-24     → A Level topic 24, Electrochemistry
https://zohxair.github.io/9701-chemistry-notes/#a-37     → A Level topic 37, Analytical techniques
```

`as-0` and `a-0` are the overview pages for each level.

## How it works

- Everything (content, styles, diagrams and scripts) is in one self-contained HTML file with no frameworks or libraries.
- Chemical formulas, equations and electron configurations are plain HTML, so they display instantly, wrap on small screens and work offline.
- Diagrams are inline SVG and the interactive tools are drawn with the HTML Canvas API; both follow the light or dark theme.
- The titration simulator solves the full charge balance for each mixture, so the curves and equivalence-point pH values are exact rather than sketched.
- Fonts (Fraunces, Source Sans 3 and STIX Two Text) load from Google Fonts. Offline, the page falls back to system fonts and still works.
- Progress, the last topic visited and the theme choice are stored in the browser's `localStorage`. Nothing is sent to a server.

## Accuracy

Numerical answers in the worked examples and mark schemes were checked by recalculation, and the interactive tools were tested against the worked examples (for example pH 2.88 for 0.100 mol dm⁻³ ethanoic acid, E<sub>cell</sub> = +0.23 V for Fe³⁺/I⁻, and *T* = 1110 K for the decomposition of calcium carbonate). Relative atomic masses and standard electrode potentials are given to the precision used in the 9701 Data Booklet.

If you spot an error in the chemistry, an answer or a mark scheme, please [open an issue](../../issues) with the topic and question number.

## Contributing

Contributions are welcome, especially new questions, corrections and translations.

1. Fork the repository and create a branch.
2. Make your change in `index.html`. Each topic is an `<article>` with an id such as `as-7` or `a-28`.
3. Open a pull request describing what you changed and why.

## Disclaimer

This is an independent revision resource. It is **not affiliated with, endorsed by or produced by Cambridge University Press & Assessment**. "Cambridge International" and the syllabus code 9701 are used only to identify the course the notes cover.

The questions are original, written in the style of 9701 examination papers. They are **not** copies of past papers. For official past papers, mark schemes, the Data Booklet and the current syllabus, use the [Cambridge International website](https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-international-as-and-a-level-chemistry-9701/) or ask your teacher.

## License

No license has been chosen yet. Until one is added, all rights are reserved by the repository owner. To let others reuse and adapt the material, add a `LICENSE` file; for example, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) suits educational content.
