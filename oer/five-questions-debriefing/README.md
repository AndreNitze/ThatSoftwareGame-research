# Five Questions for Debriefing Simulation Games

**Status:** Version 1.0 — German and English editions with publication-ready three-page PDF layouts.

This directory contains the source files for a compact open educational resource (OER) on debriefing simulation games. The guide is intended for higher education, professional training, and other facilitated learning settings. It is deliberately generic: the method can be used with digital serious games, business simulations, board-based simulations, role-based games, and comparable experiential formats.

## Purpose

The guide adapts the **Five Questions** facilitation model described by Micah Jacobson and Mari Ruddy in the second edition of *Open to Outcome* (2015) to simulation-game debriefing. The OER does not claim that the Five Questions model is empirically superior to other debriefing frameworks. Instead, it combines the model's practical facilitation logic with research showing that structured debriefing can substantially improve effectiveness and that post-experience reflection is central to learning from simulations.

The German version consistently uses the formal **Sie** form.

## Contents

The guide has three main sections:

1. Why debrief simulation games?
2. The Five Questions model, including facilitator guidance and optional follow-up questions.
3. Two worked examples: a short-notice project requirement and the Beer Distribution Game.

Both language editions render as three-page A4 PDFs.

## Files

- `de/five-questions-debriefing.qmd` — German source
- `en/five-questions-debriefing.qmd` — English source
- `debriefing-theme.typ` — German Typst layout
- `debriefing-theme-en.typ` — English Typst layout
- `references.bib` — shared bibliography
- `_quarto.yml` — Quarto/Typst build configuration

Generated PDFs and DOCX files are intentionally excluded from Git. Publication artifacts should be attached to a release and deposited with the final OER version in Zenodo.

## Build

Requirements:

- Quarto with Typst support

From this directory:

```bash
quarto render
```

The configured output directory is `_output/`.

## Source and attribution

The Five Questions structure is adapted from:

> Jacobson, M., & Ruddy, M. (2015). *Open to Outcome: A Practical Guide for Facilitating & Teaching Experiential Reflection* (2nd ed.). Wood N Barnes Publishing.

The German and English guides are attributed, simulation-game-oriented adaptations of the sequence and facilitation logic described in the second edition, with original explanatory text and examples.

## License

Original text, examples, structure of this OER, and source files created for this project are licensed under **CC BY 4.0**, subject to the repository's root `LICENSE` file.

Third-party publications, names, models, trademarks, and any quoted material remain subject to their respective rights and are not relicensed under CC BY 4.0.

## Author

**André Nitze**  
Technische Hochschule Brandenburg  
ORCID: https://orcid.org/0000-0003-0752-917X  
Project: https://thatsoftwaregame.com/
