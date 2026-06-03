#  RPCI Herding Measure
## Open Notebook

- ▶️ Open in Google Colab:  
  https://colab.research.google.com/github/mariazafran/RPCI-Herding-Measure/blob/main/RPCI_computation.ipynb

- 📖 View in nbviewer (read-only):  
  https://nbviewer.org/github/mariazafran/RPCI-Herding-Measure/blob/main/RPCI_computation.ipynb

- 📂 GitHub Repository:  
  https://github.com/mariazafran/RPCI-Herding-Measure


This project introduces a new measure of herding behaviour in financial markets:  
**Relative Performance Convergence Index (RPCI)**.

Unlike traditional models such as CSAD, which define herding as reduced dispersion,  
this project models herding as:

 **performance-driven convergence toward outperforming assets**

---

##  Analysis Pipeline

rpci_flowchart.png

1. Price data → log returns  
2. Rolling performance  
3. Performance gap (leaders vs laggards)  
4. Future adjustment  
5. RPCI index  

---

##  Herding Mechanism

- Outperformers attract investors  
- Capital flows toward winners  
- Laggards improve  
- Performance gaps shrink  

This convergence is interpreted as **herding**

---

## Key Results

### Full sample
- RPCI ≈ 0  
→ No persistent herding  

###  Crisis period (Feb 2020 – Jan 2021)

- Mean RPCI: **0.37 – 0.42**  
- t-stat: **> 2.5**  

Statistically significant herding  

---

## ⚖️ RPCI vs CSAD

| Feature | CSAD | RPCI |
|--------|------|------|
| Measures | Dispersion | Convergence |
| Behaviour captured | ❌ | ✅ |
| Directional | ❌ | ✅ |
| Crisis detection | ❌ | ✅ |

 Even after controlling for volatility, CSAD finds no herding,  
while RPCI detects **crisis-driven convergence**

---

##  Key Insight

> Herding is not constant.  
> It is a **time-varying, state-dependent phenomenon**.

Markets appear independent in normal periods  
but become **behaviourally coordinated during crises**

---

##  How to Cite

If you use this work, please cite:

**APA style:**

Bibi, M. (2026). *RPCI: Relative Performance Convergence Index for detecting herding behaviour*.  
GitHub repository: https://github.com/mariazafran/RPCI-Herding-Measure

---
##  References

- Banerjee, A. (1992). *A simple model of herd behavior*  
- Bikhchandani, S. et al. (1992). *Informational cascades*  
- Christie, W. & Huang, R. (1995). *CSSD model*  
- Chang, E. et al. (2000). *CSAD model*  
- Hwang, S. & Salmon, M. (2004). *Market stress and herding*

**BibTeX:**

```bibtex
@misc{bibi2026rpci,
  author = {Bibi, Maria},
  title = {RPCI: Relative Performance Convergence Index for detecting herding behaviour},
  year = {2026},
  publisher = {GitHub},
  howpublished = {\\url{https://github.com/mariazafran/RPCI-Herding-Measure}}
}

