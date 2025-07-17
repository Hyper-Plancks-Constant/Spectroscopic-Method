# 📊 Spectroscopic Analysis with `Spectroscopic_Method.ipynb`

> 🇧🇷 This repository was originally written in Portuguese.  
> For the original version, see: [README.pt-br.md](README.pt-br.md)  
> The notebook is also available in Portuguese. See the [`original version`](./Metodo_Espectroscopico.ipynb) in the Portuguese README!  
> This repository is listed as a technical production in the author's [`Lattes Curriculum`](http://lattes.cnpq.br/3150100365693703).  

## 📘 Description

This notebook was designed to be self-explanatory and should be read in conjunction with the associated monograph/paper. The program is specifically designed for nitrogen gas plasmas (N₂), focusing on the Second Positive System of the neutral nitrogen molecule (N₂) and the First Negative System of the molecular ion (N₂⁺). Other electronic transitions or species have not been tested.

## ▶️ How to View

To preview the code and its outputs directly on GitHub, simply click the file below and use GitHub’s native Jupyter Notebook viewer:

🔗 [`Spectroscopic_Method.ipynb`](./Spectroscopic_Method.ipynb)

## 📁 Required Files (for testing purposes)

Make sure the following files are in the same directory as the notebook to ensure correct functionality:

- `100mA.txt` — Spectroscopic data file containing intensity vs. wavelength (nm). You may replace this with other experimental spectra.
- `RxTe.dat` — File containing André Ricard’s plot of Ratio vs. Electron Temperature.  **⚠️ Do not modify this file.**

## ⚙️ Local Execution (optional)

If you wish to run the notebook locally:

1. Make sure Python 3.x is installed.
2. Install the required dependencies by running:

   ```bash
   pip install -r requirements.txt

3. Then, launch the notebook with:

   ```bash
   jupyter notebook Spectroscopic_Method.ipynb

Feel free to explore, adapt, or use this project as a reference for spectroscopic analysis in gas discharges. ✨
