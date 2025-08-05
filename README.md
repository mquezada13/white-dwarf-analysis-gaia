# 🌌 White Dwarf Analysis using Gaia DR3

This project explores a subset of white dwarfs from the Gaia DR3 catalogue using Python tools for astronomical data analysis. The notebook includes data loading, filtering, and basic visualizations, laying the groundwork for future stellar population modeling.

---

## 🔍 Project Summary

We focus on isolated, non-magnetic DA-type white dwarfs within 50 parsecs of the Sun and with masses above 0.8 M☉. The selection and filtering are based on published physical criteria relevant to compact object studies.

---

## 📦 Workflow

- Load `.fits` white dwarf catalogue using `astropy`
- Convert data to `pandas` for analysis
- Filter based on physical constraints:
  - Distance < 50 pc
  - Spectral type = DA
  - Mass > 0.8 M☉
- Explore column distributions
- Visualize:
  - Histogram of masses and effective temperatures
  - HR diagram (absolute magnitude vs color)

---

## 🧰 Tools & Libraries

- `astropy`, `pandas`, `numpy`, `matplotlib`
- Custom Python modules: `constants`, `cooling_curves`, `plot_styles`

---

## 📁 Files Included

- `WD_catalog.ipynb`: Main notebook (data load, filtering, plots)
- `.gitignore`: Prevents large `.fits` files from being committed

---

## 🛰️ Data Access

⚠️ The full `.fits` file is **not included** due to GitHub size limits. You can download it from:

🔗 [Gentile Fusillo et al. (2021) White Dwarf Catalog (Gaia DR3)](https://warwick.ac.uk/fac/sci/physics/research/astro/research/catalogues/)

---

## 🎯 Outcome

A filtered sample of high-mass, nearby DA white dwarfs suitable for further astrophysical analysis — such as cooling models, binary population studies, or dark matter interaction investigations.
