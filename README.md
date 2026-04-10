# 🫀 SSMCH-ECG Dataset

> **A Validated Dataset of 12-Lead Paper-Based ECG Images for Cardiac Abnormality Detection**

[![License: Non-Commercial](https://img.shields.io/badge/License-Non--Commercial-blue.svg)](https://physionet.org/)
[![Images: 849](https://img.shields.io/badge/Images-849-green.svg)]()
[![Classes: 3](https://img.shields.io/badge/Classes-3-orange.svg)]()
[![Format: JPG/PNG](https://img.shields.io/badge/Format-JPG%20%7C%20PNG-lightgrey.svg)]()
[![Institution: SSMCH](https://img.shields.io/badge/Institution-SSMCH%2C%20Dhaka-red.svg)]()

---

## 📖 Overview

The **SSMCH-ECG** dataset is a curated collection of real-world, paper-based **12-lead Electrocardiogram (ECG) images** acquired from clinical environments. It is intended to support research in:

- 🔬 Medical image analysis
- 👁️ Computer vision
- 📈 ECG digitization
- 🧠 Deep learning–based cardiac abnormality detection

Unlike digitally generated ECG signals, this dataset consists of **photographs of physical ECG paper records**, reflecting realistic clinical artifacts such as lighting variations, background noise, signal discontinuities, and scanning distortions.

---

## 🏥 Data Source

| Field | Details |
|-------|---------|
| **Institution** | Shaheed Suhrawardy Medical College and Hospital (SSMCH) |
| **Department** | Cardiology |
| **Location** | Dhaka, Bangladesh |
| **Population** | South Asian patients — tertiary-care public hospital |

All ECGs were collected during routine clinical practice and later digitized as image files.

---

## 📊 Dataset Composition

### Total Size

| Property | Value |
|----------|-------|
| Total Images | **849** |
| Format | JPG / PNG |
| ECG Type | Standard 12-lead ECG (paper-based) |

### Class Distribution

| Class | Description | Images | Share |
|-------|------------|--------|-------|
| 🟢 **Normal** | No clinically detected cardiac abnormality | 434 | ~51% |
| 🟡 **Abnormal** | Cardiac abnormalities excluding MI | 344 | ~41% |
| 🔴 **Myocardial Infarction (MI)** | Clinically confirmed MI cases | 71 | ~8% |

---

## 👥 Subject Demographics

| Attribute | Details |
|-----------|---------|
| **Age Range** | 15–86 years |
| **Male** | 40% |
| **Female** | 60% |

> Demographic diversity enhances the dataset's relevance for real-world deployment and population-aware modeling.

---

## ✅ Data Collection & Validation

### Ethical Considerations

- ✔️ Data collection conducted under **institutional ethical approval**
- ✔️ All **personally identifiable information (PII)** removed or anonymized
- ✔️ Complies with **patient privacy and confidentiality standards** for public medical datasets

### Clinical Validation

All ECG images were **manually reviewed and validated** by a qualified clinical expert:

| Field | Details |
|-------|---------|
| **Validator** | Dr. Jannatul Tamanna, MBBS |
| **Affiliation** | Aalok Health Care Ltd, Mirpur, Dhaka, Bangladesh |

Expert verification ensures high-quality ground truth labels for supervised learning and benchmarking.

---

## ⚠️ Dataset Challenges

This dataset reflects **real clinical acquisition conditions**, including:

| Challenge | Description |
|-----------|-------------|
| 💡 Lighting | Non-uniform lighting and shadows |
| 📄 Paper artifacts | Folds and background noise |
| 〰️ Trace quality | Broken or faint ECG traces |
| 📐 Distortion | Perspective and scanning distortion |
| 🔊 Noise | Artifacts introduced during photography |

These characteristics make the dataset especially valuable for evaluating robust preprocessing and diagnostic algorithms.

---

## 🎯 Intended Use

The dataset is suitable for, but not limited to:

- [x] Deep learning–based cardiac abnormality classification from images
- [x] ECG digitization and waveform reconstruction
- [x] Medical OCR and document understanding
- [x] Image preprocessing (denoising, alignment, contrast normalization)
- [x] Telemedicine and remote cardiac monitoring research

---

## 📜 Usage Restrictions

| Type | Policy |
|------|--------|
| ✅ **Permitted** | Non-commercial research and academic purposes |
| ❌ **Prohibited** | Commercial exploitation without explicit permission |

Users are expected to comply with [PhysioNet's data usage policies](https://physionet.org/about/licenses/) and ethical research standards.

---

## 📝 Citation

If you use this dataset in your research, please cite it appropriately. A formal citation entry will be provided upon PhysioNet release.

```bibtex
@dataset{ssmch_ecg,
  title     = {SSMCH-ECG: A Validated Dataset of 12-Lead Paper-Based ECG Images for Cardiac Abnormality Detection},
  author    = {...},
  year      = {2024},
  publisher = {PhysioNet},
  note      = {Forthcoming}
}
` ` `

---

## 🙏 Acknowledgments

- The **patients** who consented to data use
- The **Cardiology Department** of Shaheed Suhrawardy Medical College and Hospital (SSMCH)
- **Clinical expert reviewers** for label validation

---

## 📬 Contact

For questions, clarifications, or collaboration inquiries related to the dataset, please contact the dataset authors through the **[PhysioNet platform](https://physionet.org/)**.

---

<div align="center">

**SSMCH-ECG** aims to contribute toward reproducible, equitable, and clinically relevant AI research in cardiovascular health. 🫀

</div>
```

Just copy this entire block, go to your GitHub repo, click **Add a README** (or edit the existing one), paste it in, and commit. It will render perfectly.
