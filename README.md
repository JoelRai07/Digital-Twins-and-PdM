# Digital Twins for Predictive Maintenance in Automotive Aftersales

This repository contains the full LaTeX source of an IEEE-style academic paper on how digital-twin-based predictive maintenance can change automotive aftersales in the German passenger-car market.

## Quick Access

- Read the paper PDF: `paper/paper.pdf`
- Main manuscript source: `paper/paper.tex`

## Abstract

The paper investigates the business effect of moving from interval-based maintenance to a proactive, data-driven target state enabled by Digital Twins (DT) and Predictive Maintenance (PdM). It applies a model-based gap analysis and an explicit assumption framework to compare current and target customer journeys, then translates this gap into economic KPIs.

Main quantified outcome (under conservative assumptions):
- Repair capture rate increases from 40% to 70%.
- Gross profit increases by about EUR 53 per vehicle per year.
- For a 5,000-vehicle dealer fleet, this scales to about EUR 263,000 additional gross profit per year.
- Customer touchpoints can increase by up to 1.1 per year (from 1.6 to about 2.7).

## Research Question

What effect does the proactive use of digital twins and predictive maintenance have on the automotive aftersales domain?

## Paper Scope

- Domain: Automotive aftersales (Germany)
- Focus: Wear-part maintenance and repair capture
- Method: Model-based gap analysis + sensitivity analysis
- Deliverable: Transparent and contestable business potential model

## Repository Structure

- `paper/paper.tex`: Main LaTeX manuscript
- `paper/references.bib`: Bibliography database
- `paper/IEEEtran.cls`, `paper/IEEEtran.bst`: IEEE template files
- `pictures/`: Figures used by the paper
- `_referenz/`: Reference/template material

## For Readers vs. For Editors

- If you only want to read or showcase the work, the PDF is enough.
- LaTeX tools are only needed if you want to edit and recompile the manuscript.

## Optional: Rebuild the PDF

If you edit the paper source, compile from the `paper/` directory:

```bash
latexmk -pdf paper.tex
```

Alternative (without latexmk):

```bash
pdflatex paper.tex
bibtex paper
pdflatex paper.tex
pdflatex paper.tex
```

## Authors

- Maksim Bogachenkov
- Oliver Yanjie Feng
- Joel Yerai Martinez Campo

## Notes

- The manuscript includes a transparent assumptions section and sensitivity analysis to make the model interpretable and reproducible.
- The dominant practical adoption barrier identified is non-technical: telemetry access via customer consent and OEM provisioning.

## License

No license file is currently included in this repository. Add a license if you plan to allow reuse.
