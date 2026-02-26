<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                  dmhenke · GitHub Profile README              -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- ── HEADER ─────────────────────────────────────────────────── -->
<h1 align="center">Hello 👋, I'm David Henke</h1>
<h3 align="center">Computational biologist</h3>
<h3 align="center">Converting fuzzy numbers into fuzzy insights</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=dmhenke&label=Profile%20views&color=0e75b6&style=flat" alt="dmhenke" /> </p>

- ⚡ Fun fact **This landing page will be a workin progress for a *while*.**
🚀 Featured Project
<div align="center">
BioPrimeLASSO
Bio-Primed LASSO for Biomarker Discovery
[![DOI](https://img.shields.io/badge/DOI-10.1038%2Fs41698--025--00825--9-B31B1B?style=for-the-badge&logo=doi&logoColor=white)](https://www.nature.com/articles/s41698-025-00825-9)
[![GitHub Stars](https://img.shields.io/github/stars/dmhenke/BioPrimeLASSO?style=for-the-badge&color=f4d03f&logo=github)](https://github.com/dmhenke/BioPrimeLASSO/stargazers)
[![License: GPL-3](https://img.shields.io/badge/License-GPL%20v3-blue?style=for-the-badge)](https://github.com/dmhenke/BioPrimeLASSO/blob/main/LICENSE)

</div>

Standard LASSO is statistically elegant but biologically blind — in collinear omics data, it will happily select a gene simply because it lives next door to the real driver. **BioPrimeLASSO** seeks to circumvent this false positive by incorporating exterior information, protein–protein interaction (PPI) network scores, directly into the LASSO regularization penalty.  Furthermore, we introduce a tunable parameter Φ that controls how strongly biological prior knowledge steers feature selection.
```r
# Install
devtools::install_github("dmhenke/BioPrimeLASSO")

# Core usage
scores  <- get_scores(gene = "EGFR", network = ppi)
results <- bplasso(scale(X), y, scores,
                   n_folds    = 10,
                   phi_range  = seq(0, 1, length = 30))
```

📄 **Published:** Henke et al. (2025). *Bio-primed machine learning to enhance discovery of relevant biomarkers.* **npj Precision Oncology**, 9, 39. [→ Read the paper](https://www.nature.com/articles/s41698-025-00825-9)

---

## 🔬 Research Interests

| Domain | Details |
|--------|---------|
| **Regularized Regression** | Biologically-informed LASSO, adaptive penalties, penalty weighting with network priors |
| **Functional Genomics** | DepMap CRISPR/RNAi dependency screens, DEMETER2, Chronos |
| **Network Biology** | PPI integration (STRING DB), co-dependency analysis, synthetic lethality |
| **Precision Oncology** | Biomarker discovery, copy number variation, gene dependency, drug sensitivity prediction |
| **High-Dimensional Statistics** | Feature selection in *p* >> *n* regimes, collinearity, reproducible analysis pipelines |

---

## 📊 GitHub Stats

<div align="center">
## Stats and development activity 
![David's GitHub status](https://github-readme-stats.vercel.app/api?username=dmhenke&show_icons=true&theme=onedark)
  
<img height="160" src="https://github-readme-stats.vercel.app/api?username=dmhenke&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true" />
&nbsp;&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dmhenke&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />

</div>

---


<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/henke_tweets" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="henke_tweets" height="30" width="40" /></a>
<a href="https://linkedin.com/in/henkedavid" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="henkedavid" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> </p>

</div>

---

<div align="center">
<sub>
Learn to appreciate the mountain on which you’re already standing
<br><br>
<img src="https://komarev.com/ghpvc/?username=dmhenke&style=flat-square&color=003087" alt="Profile views" />
</sub>
</div>
