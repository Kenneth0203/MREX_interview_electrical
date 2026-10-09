hihi 
# Wallaby — MREx electrical interview presentation

An interactive response to Electrical Question 1, prepared for Kenneth Lai.

## Website

Open `index.html` in a browser, or visit the GitHub Pages deployment:
https://Kenneth0203.github.io/MREX_interview_electrical/

- Three fault hypotheses, each with mechanism, checks and evidence.
- Illustrative voltage-drop and wiring-loss calculator.
- Interactive traction circuit, protective bonding and communication diagram.
- Downloadable SVG diagram and printable design review.
- EMC controls and verification plan.

## Local preview

Run `python3 -m http.server 8765` in this directory and open http://localhost:8765.

The site uses plain HTML, CSS and JavaScript with no installation or build step.
GitHub Pages publishes the root of the `main` branch. `.nojekyll` bypasses Jekyll.

## Technical basis

Primary source: *2026 Semester 2 Interview Technical Questions.docx*, Electrical Question 1.
The original source document and personal handwritten image are not distributed.
Design additions are explicitly labelled proposals. Component ratings, grounding,
communication protocol and acceptance criteria require confirmation with MREx.
The proposed floating DC architecture is an interview concept, not an approved
construction drawing or a claim about Wallaby's existing electrical system.

## Editing

- `index.html`: content and functional SVG architecture.
- `style.css`: responsive styling, print layout and presentation mode.
- `app.js`: fault tabs, calculator, layer controls, download, EMC controls.

Existing Java source and IDE files are retained independently of the website.
