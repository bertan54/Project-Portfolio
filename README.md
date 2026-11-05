# Bertan Erman — Mechanical Engineering Portfolio

**Live site:** https://bertan54.github.io/Project-Portfolio/

Portfolio of internships and course projects by **Bertan Erman**, a fourth-year Mechanical Engineering and Economics double major at Koç University (Erasmus semester at the University of Mannheim). I am most interested in the space where design meets manufacturing: process planning, tolerancing, quality and cost, with FEA and CFD as supporting tools.

[LinkedIn](https://www.linkedin.com/in/bertan-erman/) · [CV (PDF)](Bertan_Erman_CV.pdf) · bertanerman54@gmail.com

---

## Internships

| # | Project | What it shows | Tools |
|---|---------|---------------|-------|
| P-10 | **ASELSAN — Mass unbalance in high-speed slip ring systems** (Aug–Sep 2026) | Balance grade selection per ISO 21940, rigid-rotor verification and a nine-source RSS error budget. Key finding: assembly, not machining precision, governs residual unbalance. Also an ergonomic tool holder designed in NX and 3D-printed for the assembly station. | ISO 21940, tolerance analysis, Siemens NX, additive manufacturing |
| P-11 | **Repkon Manufacturing — Shop floor to ERP automation** (Sep 2025) | Following parts from drawing through CAM, 5-axis milling, turning and CMM inspection, then a Python tool that validates and loads routing data into the ERP and a prototype that finds the closest previously machined part. | Process planning, ESPRIT CAM, Python, Pandas, IFS ERP |

## Course projects

| # | Project | Tools |
|---|---------|-------|
| P-01 | Deep-sea pressure hull analysis (carbon fibre / titanium, 2,000–4,500 m) | ANSYS |
| P-02 | Bolted joint FE modelling and bolt sizing | ANSYS |
| P-03 | CFD — flow through a sudden pipe expansion (k-ε vs k-ω) | ANSYS Fluent |
| P-04 | CFD — mixing elbow heat transfer, 2D and 3D | ANSYS Fluent |
| P-05 | Stress concentration factor in a plate with a hole | ANSYS, MATLAB |
| P-06 | Converging nozzle pressure analysis | ANSYS Fluent |
| P-07 | Gasoline generator reverse engineering (111 parts, group project) | Siemens NX, ANSYS |
| P-08 | Rotational-to-linear motion mechanism (built prototype, group project) | Siemens NX, Arduino, MATLAB |
| P-09 | Moving and bouncing balls — collision dynamics | MATLAB |

Reports and presentations for most projects are linked from the project cards on the site.

---

## About this repository

A single-page static site: plain HTML, CSS and a little JavaScript, no build step and no dependencies. It is served with GitHub Pages from the `main` branch.

```
index.html                  the whole site (styles and scripts are inline)
Bertan_Erman_CV.pdf         CV, linked from the site
*.pdf, *.docx, *.pptx       project and internship reports
*.png, *.gif, *.mp4, *.jpg  project images and animations
```

To preview locally, open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

### Analytics

The page is prepared for Google Analytics 4. Set `GA_ID` at the top of `index.html` to your Measurement ID; until then nothing is loaded. Visitors with "Do Not Track" enabled are not tracked. Clicks on the LinkedIn, GitHub and CV links are recorded as events.

---

© Bertan Erman. The reports and project files are shared for portfolio purposes; please contact me before reusing them.
