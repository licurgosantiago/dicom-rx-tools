# dicom-rx-tools
Ferramentas em Python para manipulação, análise e extração de dados de imagens DICOM para aplicações em radiologia diagnóstica, estadiamento oncológico e suporte à IA.
📊 dicom-rx-tools
Radiology Imaging Tools for DICOM Processing, Analysis, and AI Integration
Author: Dr. Licurgo Santiago, MD, Radiologist | Medical AI Specialist

🩻 Overview
dicom-rx-tools is a Python-based toolkit designed to streamline the handling of DICOM files in diagnostic radiology workflows. It provides utilities for DICOM reading, metadata extraction, image visualization, and basic analysis — with future support for AI-assisted diagnostics and structured reporting.

This project is aligned with ongoing innovation efforts for structured oncology staging, radiological education, and medical AI development.

🚀 Features
Easy DICOM reading (single studies or series)

Metadata extraction (patient data, imaging protocols, technical parameters)

Visualization tools (2D slices, MPR basics)

Conversion to PNG/JPEG for educational or reporting purposes

Quantitative metrics (e.g., HU histograms, volume estimations)

Integration-ready for AI models (classification, segmentation)

Modular and extensible for structured reporting systems (TNM, LI-RADS, O-RADS, BI-RADS)

🛠️ Technologies
Functionality	Libraries
DICOM I/O	pydicom, SimpleITK
Imaging	numpy, scikit-image, opencv-python, matplotlib
AI (future)	torch, monai
Development	pytest, jupyter

📂 Project Structure
dicom-rx-tools/
├── docs/                 # Documentation and examples
├── examples/              # Jupyter Notebooks
├── src/
│   ├── dicom_reader.py    # Read and load DICOM series
│   ├── metadata_utils.py  # Extract and clean metadata
│   ├── image_utils.py     # Visualization and export tools
│   ├── analysis_tools.py  # Basic quantitative analysis
│   └── ai_connector.py    # Placeholder for AI integration
├── tests/                 # Unit tests
├── requirements.txt       # Dependencies
├── README.md              # This file
├── LICENSE                # MIT License (recommended)
└── .gitignore             # Common exclusions
💡 Usage Examples
# Read a DICOM series
from src.dicom_reader import load_dicom_series
images, metadata = load_dicom_series('data/dicom_folder/')

# Visualize an image slice
from src.image_utils import show_slice
show_slice(images, index=25)

# Export images to PNG
from src.image_utils import export_as_png
export_as_png(images, 'output/png/')

# Extract metadata
from src.metadata_utils import extract_basic_info
info = extract_basic_info(metadata)
print(info)
🔮 Future Roadmap
📊 Advanced quantification (HU maps, volumetrics)

🧠 Integration with AI pipelines for structured reporting

🔎 DICOM harmonization tools for dataset standardization

🏥 Educational modules for radiology residents

📑 Direct integration with TNM/LI-RADS/BI-RADS reporting tools
📚 Related Projects
Röntgen: Virtual assistant for radiologists (structured reports, oncology staging, AI clinical reasoning)

Quantum Biomolecular Imaging (QBI): Theoretical next-gen imaging platform under research

👨‍⚕️ About the Author
Dr. Licurgo Santiago
Radiologist | Medical AI Specialist | Structured Reporting Expert

Transforming radiology through structured data, AI, and clinical precision.
📜 License
This project is licensed under the MIT License.
