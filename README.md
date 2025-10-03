# Open Cluster Analysis – NGC 2360

This project analyzes the open cluster **NGC 2360** using **Gaia DR3 data** and **PARSEC isochrones**.  
It combines data cleaning, color–magnitude diagram (CMD) construction, isochrone fitting, and model comparison.  
The workflow highlights astrophysical insights and demonstrates coding, visualization, and reproducibility skills.

---

## 🚀 Project Workflow

1. **Data Acquisition**  
   - Downloaded Gaia DR3 photometry (G, BP, RP magnitudes, parallaxes, proper motions).  
   - Downloaded PARSEC isochrone files.  

2. **CMD Construction**  
   - Built the Color–Magnitude Diagram (CMD).  
   - Cleaned data by applying parallax and proper motion cuts to remove field stars.  

3. **Isochrone Fitting**  
   - Overlaid PARSEC isochrones on the CMD.  
   - Used **interactive sliders** to adjust distance modulus (μ) and reddening E(B–V).  
   - Tuned parameters to best match the cluster sequence.  

4. **Model Comparison**  
   - Overlaid multiple isochrones with different ages to explore cluster evolution.  
   - Compared fits visually and quantitatively.  

5. **Astrophysical Insights**  
   - Identified the **Main-Sequence Turnoff (MSTO)** and potential **Red Clump** stars.  
   - Estimated cluster **age**, **distance**, and **reddening**.  

---


---

## Results  

- The CMD of NGC 2360 was cleaned using Gaia astrometry (parallax + proper motions), reducing field star contamination.  
- Interactive PARSEC isochrone fitting gave best-fit parameters:  
  - Distance modulus μ ≈ 11.35  
  - Reddening E(B–V) ≈ 0.08  
  - Age ≈ 1.2 Gyr  
- Multiple isochrones (different ages/metallicities) were compared, confirming that 1.2 Gyr with near-solar metallicity provides the best match.  
- Results are consistent with published literature values, validating the workflow.  

📌 A detailed discussion is available in [Results and Observations](Results%20and%20Observations/Results%20and%20Observations.md).  

---

## 🔑 Key Features

- **Field star decontamination** using Gaia parallaxes and proper motions.  
- **Quantitative isochrone fitting** with adjustable μ and E(B–V).  
- **Multiple isochrone overlays** for model comparison.  
- **Interactive visualization** with sliders (μ, E(B–V)).  
- **Astrophysical interpretation**: MSTO, red clump, age, distance.  

---

## 🛠️ Requirements

- Python 3.x  
- `pandas`, `numpy`, `matplotlib`  
- `ipywidgets` (for interactive sliders)  

---

## 📌 Conclusion

This project successfully demonstrates how Gaia data and stellar evolution models can be combined to derive physical properties of an open cluster.  
The methodology is **reproducible, extendable, and visually clear**, making it suitable for research projects, teaching, and further development (e.g., multiple clusters, automated fitting).  

---

## 📜 License

MIT License. Free to use and adapt with proper attribution.

