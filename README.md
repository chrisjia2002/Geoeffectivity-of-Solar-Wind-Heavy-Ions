# Geoeffectivity of Solar Wind Heavy Ions: Jupyter Notebook Analysis

This repository contains the Jupyter Notebook used in the analysis presented in the manuscript titled **"Geoeffectivity of Solar Wind Heavy Ions"** submitted to *Geophysical Research Letters*. The analysis investigates the role of heavy ions in the solar wind during interplanetary coronal mass ejection (ICME) events, their influence on Earth's magnetosphere, and correlations with geomagnetic indices (Dst and AE).

## Overview

The primary objective of this project is to explore the contribution of heavy ions (e.g., helium, oxygen, carbon, iron) to the solar wind dynamic pressure and its effects on geomagnetic activity. By leveraging data from the **Solar Wind Ion Composition Spectrometer (SWICS)** aboard the **Advanced Composition Explorer (ACE)** spacecraft, this project studies ICME events from 1999 to 2005.

Key findings:
- Heavy ion dynamic pressure fraction increases significantly during ICME events, contributing up to 50% of total pressure.
- Including heavy ions in dynamic pressure calculations reduces Earth's magnetopause distance by 3.57% during ICME disturbances.
- Heavy ions (excluding helium) show strong correlations with geomagnetic indices (Dst: r = -0.57, AE: r = 0.60).

## Repository Contents

- `Final Figures.ipynb`: The Jupyter Notebook used to generate the figures and perform the analyses presented in the manuscript.
- `environment.yml`: A conda environment file listing all the dependencies required to run the notebook.
- `README.md`: Project description and usage instructions.
- `LICENSE`: Open-source license for this project.
- `CITATION.cff`: Citation file format for referencing this repository.

## Data Sources

- **Solar Wind Data**: Data used in this analysis comes from the ACE SWICS 1.1 Level 2 dataset (1999-2005), which provides detailed measurements of solar wind ion composition. The dataset is available at: [ACE SWICS Data](https://izw1.caltech.edu/ACE/ASC/level2/lvl2DATA_SWICS-SWIMS.html).
- **Geomagnetic Indices**: The Dst and AE indices are sourced from the World Data Center for Geomagnetism, Kyoto. The dataset can be accessed at: [Kyoto WDC](https://wdc.kugi.kyoto-u.ac.jp/wdc/Sec3.html).
- **ICME Event Catalog**: The event catalog used in this study was compiled by Richardson and Cane (2010) and is accessible online: [ICME Catalog](https://izw1.caltech.edu/ACE/ASC/DATA/level3/icmetable2.html).

## Citation

If you use this notebook or data in your research, please cite it as follows:

```
Jia, C. (2024). Geoeffectivity of Solar Wind Heavy Ions: Jupyter Notebook Analysis (Version 1.0). Zenodo. https://doi.org/xxxxx
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any questions or inquiries, please contact the corresponding author:  
**Chris Jia**  
Email: [chris.jia2002@utexas.edu](mailto:chris.jia2002@utexas.edu)

---
