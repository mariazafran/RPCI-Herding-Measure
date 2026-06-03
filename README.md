# RPCI-Herding-Measure
Performance-based measure of herding behaviour using RPCI
# 📊 RPCI Herding Measure

This project introduces a new measure of herding behaviour:  
**Relative Performance Convergence Index (RPCI)**.

Traditional models such as CSAD define herding as reduced dispersion.  
This project instead models herding as:

👉 **performance-driven convergence toward outperforming assets**


## 📌 How to Cite

If you use this work, please cite:

**APA style:**

Bibi, M. (2026). *RPCI: Relative Performance Convergence Index for detecting herding behaviour*. GitHub repository. [Yo]

**BibTeX:**

```bibtex
@misc{https://github.com/mariazafran/RPCI-Herding-Measure}

  author = {Bibi, Maria},
  title = {RPCI: Relative Performance Convergence Index for detecting herding behaviour},
  year = {2026},
  publisher = {GitHub},
  howpublished = {\\url{https://github.com/yourusername/RPCI-Herding-Measure}}
}

---

## 🔬 Analysis Pipeline

rpci_flowchart.png

1. Price data → log returns  
2. Rolling performance  
3. Performance gap (leaders vs laggards)  
4. Future adjustment  
5. RPCI index  

---

## 🧠 Herding Mechanism

- Outperformers attract investors  
- Capital flows toward winners  
- Laggards improve  
- Performance gaps shrink  

👉 This convergence is interpreted as **herding**

---

## 📉 Key Results

### Full sample
- RPCI ≈ 0  
→ No persistent herding  

### 🔥 Crisis period (Feb 2020 – Jan 2021)

- Mean RPCI: **0.37 – 0.42**  
- t-stat: **> 2.5**  

✅ Statistically significant herding  

---

## ⚖️ RPCI vs CSAD

| Feature | CSAD | RPCI |
|--------|------|------|
| Measures | Dispersion | Convergence |
| Behaviour captured | ❌ | ✅ |
| Directional | ❌ | ✅ |
| Crisis herd detection | ❌ | ✅ |

👉 Even with volatility controls, CSAD shows no herding,  
while RPCI detects **crisis-driven convergence**

---

## 🏆 Key Insight

> Herding is not constant.  
> It is a **time-varying, state-dependent phenomenon**.

Markets appear independent in normal periods  
but become **behaviourally coordinated during crises**.

---

## 📚 References

- Banerjee, A. (1992). *A simple model of herd behavior*  
- Bikhchandani, S. et al. (1992). *Informational cascades*  
- Christie, W. & Huang, R. (1995). *CSSD model*  
- Chang, E. et al. (2000). *CSAD model*  
- Hwang, S. & Salmon, M. (2004). *Market stress and herding*
