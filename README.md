# The Differential Market Impact of ECB Narrative Tone Across Communication Channels

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Python](https://img.shields.io/badge/python-3.10+-blue)

**Author:** Shreyas Urgunde  
**Institution:** Warwick Business School  
**Supervisor:** Philippe Mueller  
**Date:** September 2025

**📄 Paper:**  
👉 [View the dissertation](https://shreyasxi.github.io/ecb-narrative-tone-market-impact-thesis/) 

---

## 📌 Overview

The objective of this thesis is to quantify how the tone of European Central Bank communications influences euro-area markets across policy statements, press conferences, Monetary Policy Accounts, and Executive Board speeches.

It primarily constitues: 
- **Channel-specific tone & Comparison:** Using ECB-specific lexicons to build sentence-level hawk–dove scores and assess whether tone adds incremental information beyond policy news across press releases, Q&A, Accounts, and speeches.
- **Event timing & high-frequency identification:** Intraday reactions are measured in tightly defined windows taken from the EA-MPD and EA-CED datasets to precisely time announcements, use high-frequency returns to isolate immediate market moves, and extract policy-news factors via PCA.
- **Isolating pure tone effects:** Separate narrative tone from contemporaneous policy surprises (Target/FG/QE) to recover the tone-only impact.
- **Daily persistence:** Building on intraday analysis using EA-MPD and EA-CED, I re-estimate on daily changes to test whether tone effects persist beyond the announcement window and survive broader market noise.
- **State dependence:** Interact tone with the ECB Composite Indicator of Systemic Stress (CISS) to assess whether effects amplify in calm periods and dampen under stress; report marginal effects across stress regimes.

---

## Key findings 
- **Channel heterogeneity:** Tone in policy statements and accounts has stronger and more consistent effects than speeches; Q&A can amplify effects.  
- **Asset sensitivity:** Short-rate proxies and sovereign spreads respond more than broad equity/FX in daily data.  
- **State dependence:** Effects are **larger under high financial stress** (CISS interactions).  
- **Interpretation:** Narrative tone contains incremental information beyond standard policy-news factors at the daily horizon.

