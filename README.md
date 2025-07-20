# 🩻 dicom-rx-tools

**Advanced Python Toolkit for Medical Imaging, DICOM Processing, and AI Integration in Radiology**  
Author: Dr. Licurgo Santiago | Radiologist | Medical AI Specialist  

---

## 🩺 Project Overview
`dicom-rx-tools` is a modular Python framework designed to streamline the manipulation, analysis, and integration of DICOM imaging data within radiology workflows. It aims to support academic, clinical, and research applications — with a clear roadmap towards AI integration, structured reporting (TNM, FIGO, O-RADS, LI-RADS, BI-RADS), and quantitative imaging.

This project serves as a foundational component for intelligent ecosystems such as **Röntgen**, targeting precision oncology staging, radiomics pipelines, and educational tools for radiology residents.

---

## 🔧 Key Features
- 📥 Efficient DICOM series loading and parsing  
- 🔎 Comprehensive DICOM metadata extraction  
- 📊 Image visualization and export (PNG, NIfTI)  
- 📐 Basic quantitative imaging analysis (volume, HU histogram)  
- 🤖 Ready for AI integration (classification, segmentation, radiomics)  
- 🏥 Modular, educational, and extensible for clinical practice  

---

## 🛠️ Technology Stack
| Purpose        | Libraries            |
|----------------|----------------------|
| DICOM Handling | `pydicom`, `SimpleITK` |
| Imaging        | `numpy`, `opencv-python`, `matplotlib`, `scikit-image` |
| AI Integration | `torch`, `monai` (future) |
| Utilities      | `jupyter`, `pytest`, `tqdm` |

---

## 📂 Project Structure
dicom-rx-tools/
├── docs/ # Documentation and usage guides
├── examples/ # Jupyter Notebooks and practical cases
├── src/ # Core source code
│ ├── dicom_reader.py # Load and parse DICOM datasets
│ ├── metadata_utils.py # Extract and structure metadata
│ ├── image_utils.py # Visualization and export tools
│ ├── analysis_tools.py # Quantitative analysis (volumetrics, HU)
│ └── ai_connector.py # AI/ML future integrations
├── tests/ # Unit tests
├── output/ # Generated outputs (images, reports)
├── requirements.txt # Dependencies list
├── .gitignore # Versioning hygiene
└── README.md # Project description
