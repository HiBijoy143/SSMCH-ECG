# SSMCH-ECG
SSMCH-ECG: A Validated Dataset of 12-Lead Paper-Based ECG Images for Cardiac Abnormality Detection

\## 1. Overview



The \*\*SSMCH-ECG\*\* dataset is a curated collection of real-world, paper-based \*\*12-lead Electrocardiogram (ECG) images\*\* acquired from clinical environments. The dataset is intended to support research in \*\*medical image analysis\*\*, \*\*computer vision\*\*, \*\*ECG digitization\*\*, and \*\*deep learning–based cardiac abnormality detection\*\*.



Unlike digitally generated ECG signals, this dataset consists of \*\*photographs of physical ECG paper records\*\*, reflecting realistic clinical artifacts such as lighting variations, background noise, signal discontinuities, and scanning distortions. These characteristics make the dataset particularly suitable for evaluating robust preprocessing and diagnostic algorithms.



---



\## 2. Data Source



\- \*\*Institution\*\*: Shaheed Suhrawardy Medical College and Hospital (SSMCH)  

\- \*\*Department\*\*: Cardiology  

\- \*\*Location\*\*: Dhaka, Bangladesh  

\- \*\*Population\*\*: South Asian patients visiting a tertiary-care public hospital  



All ECGs were collected during routine clinical practice and later digitized as image files.



---



\## 3. Dataset Composition



\### 3.1 Total Size

\- \*\*Total Images\*\*: 849  

\- \*\*Format\*\*: JPG / PNG  

\- \*\*ECG Type\*\*: Standard 12-lead ECG (paper-based)



\### 3.2 Class Labels



| Class | Description | Number of Images |

|------|------------|------------------|

| Normal | No clinically detected cardiac abnormality | 434 |

| Abnormal | Cardiac abnormalities excluding MI | 344 |

| Myocardial Infarction (MI) | Clinically confirmed MI cases | 71 |



---



\## 4. Subject Demographics



\- \*\*Age Range\*\*: 15–86 years  

\- \*\*Gender Distribution\*\*:

&nbsp; - Male: 40%

&nbsp; - Female: 60%



Demographic diversity enhances the dataset’s relevance for real-world deployment and population-aware modeling.



---



\## 5. Data Collection and Validation



\### 5.1 Ethical Considerations



\- Data collection was conducted under \*\*institutional ethical approval\*\*.

\- All \*\*personally identifiable information (PII)\*\* was removed or anonymized.

\- The dataset complies with \*\*patient privacy and confidentiality standards\*\* required for public medical datasets.



\### 5.2 Clinical Validation



All ECG images were \*\*manually reviewed and validated\*\* by a qualified clinical expert:



\- \*\*Validator\*\*: Dr. Jannatul Tamanna, MBBS  

\- \*\*Affiliation\*\*: Aalok Health Care Ltd, Mirpur, Dhaka, Bangladesh  



The expert verification ensures high-quality ground truth labels for supervised learning and benchmarking.



---



\## 6. Dataset Characteristics and Challenges



This dataset reflects \*\*real clinical acquisition conditions\*\*, including:



\- Non-uniform lighting and shadows  

\- Paper folds and background artifacts  

\- Broken or faint ECG traces  

\- Perspective distortion  

\- Noise introduced during photography or scanning  



These characteristics make the dataset especially valuable for:

\- Robust preprocessing algorithm development

\- Image-to-signal reconstruction research

\- Evaluation of model generalization in realistic settings



---



\## 7. Intended Use



The dataset is suitable for, but not limited to:



\- Deep learning–based cardiac abnormality classification from images  

\- ECG digitization and waveform reconstruction  

\- Medical OCR and document understanding  

\- Image preprocessing (denoising, alignment, contrast normalization)  

\- Telemedicine and remote cardiac monitoring research  



---



\## 8. Usage Restrictions



\- \*\*Permitted Use\*\*: Non-commercial research and academic purposes only  

\- \*\*Prohibited Use\*\*: Commercial exploitation without explicit permission  



Users are expected to comply with PhysioNet’s data usage policies and ethical research standards.



---



\## 9. Citation



If you use this dataset in your research, please cite it appropriately in your publications.  

A formal citation entry will be provided upon PhysioNet release.



---



\## 10. Acknowledgments



The authors acknowledge:

\- The patients who consented to data use  

\- The Cardiology Department of SSMCH  

\- Clinical expert reviewers for label validation  



---



\## 11. Contact



For questions, clarifications, or collaboration inquiries related to the dataset, please contact the dataset authors through the PhysioNet platform.



---



\*\*SSMCH-ECG\*\* aims to contribute toward reproducible, equitable, and clinically relevant AI research in cardiovascular health.




