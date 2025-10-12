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
- **State dependence:** Interact tone with the ECB CISS to gauge how tone’s impact varies with financial stress.
- **Robustness & reproducibility:** Verify results with alternative tone dictionaries, orthogonalized (“policy-free”) tone, and subsample analysis (pre/post-COVID).

---

<h2>💡Key findings</h2>
<table>
  <thead>
    <tr>
      <th>Topic</th>
      <th>Finding</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Channel heterogeneity</strong></td>
      <td>Strongest incremental effects in <strong>policy statements</strong> and <strong>Accounts</strong>; <strong>press-conference Q&amp;A</strong> shows a selective <strong>equity</strong> response.</td>
    </tr>
    <tr>
      <td><strong>Asset sensitivity</strong></td>
      <td><strong>Rates &amp; sovereign spreads</strong> react more than <strong>equities/FX</strong>; equity/FX effects are smaller and less persistent.</td>
    </tr>
    <tr>
      <td><strong>Intraday vs daily</strong></td>
      <td>Effects peak <strong>around announcements</strong>; by the <strong>daily close</strong> most attenuate, with <strong>Accounts/speeches</strong> showing the most persistence.</td>
    </tr>
    <tr>
      <td><strong>State dependence (CISS)</strong></td>
      <td>Tone’s impact <strong>dampens as stress rises</strong> and <strong>strengthens in calmer regimes</strong>.</td>
    </tr>
    <tr>
      <td><strong>Policy news vs tone</strong></td>
      <td><strong>Target / FG / QE</strong> shocks explain most variation; tone adds <strong>incrementally</strong> by clarifying policy intent.</td>
    </tr>
  </tbody>
</table>

---




