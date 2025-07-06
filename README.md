# Kidney Therapeutic Simulation Platform

A comprehensive Python + HTML-based simulation platform for designing, analyzing, and visualizing kidney-targeted protein therapy using engineered proteins, nanoparticles, and hydrogels. The system models drug pharmacokinetics, therapeutic efficacy, immunogenicity, and safety with interactive and animated visualizations.

---

## 🌟 Features

* **Advanced Simulation Engine (Python)**

  * Therapeutic protein engineering (EC50 reduction, Fc-fusion kinetics)
  * Nanoparticle formation and encapsulation modeling
  * Hydrogel gelation, swelling, and degradation behavior
  * 4-compartment pharmacokinetic (PK) model with kidney targeting
  * Glomerular Filtration Rate (GFR) and fibrosis modeling
  * Immunogenicity and biomarker-based toxicity evaluation
  * Monte Carlo sensitivity analysis & dose-response optimization

* **Interactive Web Interface (HTML/JS + Plotly)**

  * Dynamic controls for all dosing and disease parameters
  * Real-time GFR and fibrosis plots
  * Simulated antibody titers and efficacy output
  * Clean, modern, responsive UI for education or research demos

---

## 📂 File Structure

* `kidney_pharmacokinetics_simulations.py`

  > Full Python backend engine for generating figures and analysis using matplotlib + NumPy + SciPy.

* `kidney_simulation.html`

  > Interactive frontend with sliders, plots (Plotly.js), and simulation logic in JavaScript.

---

## 🚀 Getting Started

### Option 1: Run Python Backend

1. Install requirements:

```bash
pip install numpy scipy matplotlib seaborn pandas
```

2. Run the simulation:

```bash
python kidney_pharmacokinetics_simulations.py
```

This will generate all plots, summary report, and optionally perform sensitivity/dose-response analysis.

---

### Option 2: Use the Interactive HTML

1. Open `kidney_simulation.html` in a modern browser.
2. Adjust dosage, kinetics, disease severity, and observe dynamic GFR/fibrosis outcomes.

> Great for interactive education, demo, or preliminary design testing!

---

## 📊 Outputs

* **Backend**

  * Protein-receptor binding curves
  * Nanoparticle and hydrogel characterization
  * PK/PD simulations and therapeutic profiles
  * Immunogenicity risk plots
  * Radar charts and summary tables

* **Frontend**

  * Real-time GFR, fibrosis, antibody titer plots
  * Custom input sliders for therapy tuning

---

## 📚 Applications

* Preclinical drug development simulations
* Visualization of therapeutic design tradeoffs
* Research presentation graphics
* Educational tools for pharmacology and tissue engineering

---

## 📌 Author

**Joshua Haigler**
Student Researcher @ Cornerstone Academy
Project: Regenerative Therapeutics for Kidney Disease

---

## 🧪 Citation

If using this code for academic or presentation purposes, please cite:

> Haigler, J. (2025). Enhanced Targeted Regenerative Protein Therapy Using Zwitterionic Nanoparticles and Dual-Network PEG-PCL Hydrogels for Reversing Chronic Kidney Disease: An In Silico Study.

---

## 📄 License

This project is released for educational and research use only.

---

## 🧠 Future Improvements

* Integrate backend + frontend via Flask or FastAPI
* Add patient variability models
* Enable export of JSON/CSV results from web UI
* Model combination therapy strategies

---

## ✅ Status

✅ Fully functional Python simulation
✅ Interactive browser-based visualizer
🔄 Backend/frontend integration pending
