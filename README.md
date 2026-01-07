## Exploring SM Anomaly Patterns

A mini-project exploring whether Standard Model anomalies cluster by shared BSM explanations.

## The Question

There are about 10 well-known precision measurements in particle physics that deviate from Standard Model predictions: muon g-2, W mass, B-decay anomalies, proton radius, and others.

Usually, people fit each anomaly individually to different BSM models.

My question: Do these anomalies form a pattern? Do some of them point to the same new physics?

## What I Did

1. Compiled 10 anomalies across leptonic, electroweak, flavour, and nuclear sectors
2. Listed 6 BSM models commonly discussed in the literature (Z', leptoquark, SUSY, dark photon, composite Higgs, 2HDM)
3. Built a score matrix: scored each anomaly-model pair 0-3 based on how naturally that model could explain it
4. Analyzed for patterns: which anomalies share BSM explanations? Which models coexist naturally?

## Key Findings

Anomalies are not random. They cluster in model-space.

EW and Flavour cluster: W mass and B-physics anomalies (RK, R(D), B→K*) are explained by the same models (Z', leptoquark). This suggests a unified new-physics origin.

Leptonic cluster: Muon and electron g-2 point toward Z', SUSY, and dark photon.

Isolated anomalies: Proton radius and CKM unitarity don't fit the above patterns. Likely measurement issues or separate physics.

Minimal new physics: Z' boson (TeV) plus dark photon (sub-GeV). Z' handles EW+flavour cluster. Dark photon handles leptonic precision. Orthogonal sectors, no conflict.

## Files

analysis.ipynb — Jupyter notebook with code, data, analysis, and figures

writeup.md — 2-page summary

writeup.pdf — PDF version

figures/ — Key plots:
  Figure_1_heatmap.png (model × anomaly scores)
  Figure_2_clustering.png (anomaly clustering network)


## Notes

Semi-quantitative: Scores based on literature, not rigorous fits. Goal was patterns, not precision.

Limited scope: 10 anomalies, 6 models. Core clustering is robust.

## What This Shows

Literature synthesis across subfields. Python data analysis. Pattern-matching as research.

Tech: Python (pandas, numpy, matplotlib, networkx), Jupyter, LaTeX.
