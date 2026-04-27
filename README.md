# 🧠 NEUROFORGE

> Year-long structured roadmap from backend engineering into Computer Vision applied to psychiatric neuroimaging.
> **Public learning log · May 2026 → April 2027**

![Phase](https://img.shields.io/badge/Phase-I_Foundations-orange?style=flat-square)
![Streak](https://img.shields.io/badge/🔥_Streak-1d-red?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Made with](https://img.shields.io/badge/Made_with-Python_+_NumPy-3776AB?style=flat-square&logo=python&logoColor=white)

---

## 🇪🇸 Sobre este repositorio

NEUROFORGE es mi plan estructurado de **un año** para pivotar de **backend engineer** (Java/Spring Boot, C#, Python · 4 años de producción) a **investigador en Computer Vision aplicada a neuroimagen psiquiátrica**.

**Objetivo final**: trabajar en un laboratorio español investigando esquizofrenia con MRI/fMRI — CIBERSAM, IDIBAPS, BBRC, FIDMAG, Hospital Clínic, Hospital del Mar o Gregorio Marañón.

Aquí publico todos los notebooks, ejercicios, proyectos boss-fight y documentación bilingüe (ES/EN) generados durante el viaje. Es deliberadamente público para mantener accountability y para que otros que hagan el mismo pivote puedan seguir el camino.

## 🇬🇧 About

NEUROFORGE is a structured one-year plan to pivot from **backend engineering** (Java/Spring/C#/Python · 4 yrs production) into **Computer Vision research applied to psychiatric neuroimaging**.

**Endgame**: research-engineer or PhD position at a Spanish lab investigating schizophrenia with MRI/fMRI — CIBERSAM, IDIBAPS, BBRC, FIDMAG, Hospital Clínic, Hospital del Mar, or Gregorio Marañón.

All notebooks, exercises, boss-fight projects, and bilingual documentation produced during the journey live here. Intentionally public for accountability and to help others making the same pivot.

---

## 🗺️ Roadmap

| Phase | Window | Theme | Boss Fight |
|------:|--------|-------|------------|
| **I** | May–Jun 2026 | Foundations · NumPy · Linear Algebra · Statistics | SVD Image Compressor + PCA Face Eigenspace (LFW) |
| **II** | Jul–Aug 2026 | Image Processing · OpenCV · scikit-image | Skin Lesion Pre-screening (HAM10000, classical CV only) |
| **III** | Sep–Oct 2026 | Deep Learning · PyTorch Lightning · MLOps | Chest X-ray Pathology Classifier (full stack: W&B, Docker, FastAPI) |
| **IV** | Nov 26–Jan 27 | Medical Imaging · DICOM · BIDS · MONAI · nnU-Net | BIDS-compliant 3D U-Net Hippocampal Segmentation (OASIS-3) |
| **V** | Feb–Apr 2027 | Neuroimaging Research · fMRIPrep · BrainNetCNN · Statistics | **Schizophrenia vs Controls Classifier on COBRE** — full pipeline + preprint write-up |

---

## 📓 Phase I notebooks · Foundations

| Wk | Topic | Notebook | Status |
|----|-------|----------|--------|
| 1  | NumPy fluency · 5 vectorised image ops | [`wk01_numpy.ipynb`](./wk01_numpy.ipynb) | ✅ |
| 2  | Linear Algebra I · SVD compression | _coming soon_ | 🔒 |
| 3  | Linear Algebra II · PCA from scratch | _coming soon_ | 🔒 |
| 4  | Calculus refresh · gradient descent | _coming soon_ | 🔒 |
| 5  | Probability · Naive Bayes | _coming soon_ | 🔒 |
| 6  | Statistics for science | _coming soon_ | 🔒 |
| 7  | Sci-stack · OASIS-1 EDA | _coming soon_ | 🔒 |
| 8  | **Boss Fight** · SVD compressor + PCA face eigenspace | _coming soon_ | 🔒 |

---

## 🎯 Final Boss · Apr 2027

**Schizophrenia vs Controls Classifier on COBRE**
- Full BIDS pipeline (download → fMRIPrep → FC matrices)
- BrainNetCNN / Graph Neural Network classifier
- Bootstrap CIs + permutation tests for honest statistics
- Reproducible repo + bilingual ES/EN README
- 6-page preprint-style write-up + 5-min lightning talk video

---

## 🛠️ Stack across phases

```
Phase I    :  NumPy · Pandas · Matplotlib · SciPy · Jupyter
Phase II   :  OpenCV · scikit-image · PIL · ImageJ
Phase III  :  PyTorch · PyTorch Lightning · timm · W&B · Hydra · Docker
Phase IV   :  pydicom · NiBabel · SimpleITK · MONAI · nnU-Net · 3D Slicer · BIDS
Phase V    :  nilearn · nipype · fMRIPrep · MRIQC · FreeSurfer · BrainNetCNN · NetworkX
```

---

## 🚀 Local setup

```bash
git clone https://github.com/nacho995/neuroforge.git
cd neuroforge
uv sync                    # installs deps from pyproject.toml + uv.lock
uv run jupyter lab         # or open notebooks in Positron / VS Code / Cursor
```

---

## 🧭 Why public

Doing this in the open serves three goals:
1. **Accountability** — public commits force consistency.
2. **Help others** — engineers pivoting into CV/medical imaging can fork this and follow the same structure.
3. **Visibility** — Spanish PIs and research-engineering recruiters can see actual work, not just a CV.

If you're on a similar path, **fork it, adapt it, and tell me how it goes** — issues and discussions welcome.

---

## 📜 License

MIT. Use, fork, adapt freely.

---

**Author**: Ignacio Dalesio · Madrid, Spain
[LinkedIn](https://www.linkedin.com/in/ignaciodalesio/) · [GitHub](https://github.com/nacho995) · [Email](mailto:ignaciodalesio1995@gmail.com)
