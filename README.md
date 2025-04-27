## shallowML_classification
Assessing the performance of a Gaussian Naive Bayes (NB) classifier and a Random Forest (RF) classifier for automated detection of invasive Sargassum seaweed using Sentinel-2 MSI data.

---

## Classification Task

The first two notebooks train, save, and evaluate shallow classification models:
- **ML1:** Gaussian Naive Bayes (NB)
- **ML2:** Random Forest (RF)

The final notebook (**ML3**) uses the trained models to make a side-by-side comparison (NB vs RF).

The classifiers are trained to distinguish between **Water** (n = 220) and **Sargassum** (n = 331) on a per-pixel basis.

Each model is trained on labelled data and tested on unseen Sentinel-2 scenes. These are subsetted to reduce runtime.

---

## Data & Preprocessing Steps

1. **Study Area**: Waters offshore of Barbados.  
2. **Data Source**: Sentinel-2 MSI (Level-1C).  
3. **Atmospheric Correction**: ACOLITE.
4. **Training Labels**: Pixels manually labelled in SNAP.

---

## Tools & Sources

- [ESA Sentinel-2 MSI data – Copernicus Open Access Hub](https://dataspace.copernicus.eu)
- [ACOLITE atmospheric correction tool (RBINS)](https://github.com/acolite/acolite/releases/tag/20250114.0)
- [ESA Sentinel Application Platform (SNAP) v10](https://step.esa.int/main/download/snap-download/)

---

## Status

🚧 This repository is under construction. Additional metrics, visual outputs (e.g. confusion matrix), and model interpretation may be added in future updates.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
