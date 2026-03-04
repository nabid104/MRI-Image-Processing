# 🧠 Parkinson Disease MRI Analysis Project

## 📌 Project Overview
This project focuses on analyzing brain MRI data to study **Parkinson's Disease (PD)**. Parkinson's disease is a neurodegenerative disorder that primarily affects movement and motor control due to the loss of dopamine-producing neurons.

The aim of this project is to process MRI/fMRI data, analyze brain regions associated with Parkinson's disease, and organize the workflow, datasets, and results for research and analysis.

---

# 🎯 Project Objectives

- Preprocess structural MRI and fMRI data
- Normalize brain images to **MNI152 standard space**
- Extract **Region of Interest (ROI)** signals from motor-related brain regions
- Analyze functional activity related to **Parkinson’s Disease**
- Build a **reproducible neuroimaging processing pipeline**
- Document the full computational workflow

---

# 🧠 Brain Regions of Interest (ROI)

The analysis focuses on several important brain regions involved in motor control and Parkinson's disease pathology.

### Substantia Nigra (SN)
The Substantia Nigra is responsible for producing dopamine. Degeneration of neurons in this region is one of the main causes of Parkinson's disease.

### Putamen
The Putamen is part of the basal ganglia and is involved in regulating movement and motor control.

### Primary Motor Cortex (M1)
This region controls voluntary muscle movement and motor execution.

### Supplementary Motor Area (SMA)
The SMA is responsible for planning and coordinating complex movements.

---

# 📂 Project Structure
```
Parkinson_Disease_Project
│
├── Code
│   └── Scripts for MRI processing and analysis
│
├── Dataset
│   └── Patient and control subject data
│
├── Figures
│   └── Brain visualizations and analysis figures
│
├── Workflow
│   └── Processing steps and methodology
│
├── Results
│   └── Output files and experiment results
│
├── Reports
│   └── Research documentation and summaries
│
└── Presentation_Slides
    └── Project presentations
```

---

# 🔬 Workflow

The workflow of this project includes:

1. MRI/fMRI data collection
2. Brain atlas and region identification
3. Extraction of regions of interest (ROI)
4. Surface visualization of brain structures
5. Data analysis and comparison
6. Result visualization and reporting

---

# 📊 Dataset Information

The dataset includes:

- Healthy control subjects
- Parkinson's disease patients
- Clinical information such as:
  - Age
  - Sex
  - Treatment information
  - UPDRS motor scores
  - Disease severity stages

---

# 🛠 Tools and Technologies

### Neuroimaging Software
- **FSL**
  - BET
  - FLIRT
  - FNIRT
  - applywarp
  - epi_reg

### Python Libraries
- Python
- NumPy
- Pandas
- NiBabel
- Nilearn

### Brain Atlas
- **AAL3 Atlas**

### Environment
- Linux / WSL
- Git / GitHub

---

# 📈 Outputs Generated

The pipeline produces:

- Normalized functional MRI images
- Structural-to-MNI deformation fields
- ROI time-series signals
- Processed datasets for statistical analysis

---

# 🔁 Reproducibility

The project pipeline is designed to be:

✔ modular  
✔ automated  
✔ reproducible  

## 👨‍🏫 Instructor / Supervisor

**Instructor:** Dr. Yushuf Sharker
Parkinson Disease MRI Analysis Project  
Neuroimaging Research Study

# 👨‍💻 Author
Md. Raiyan Hasan Nabid
Parkinson Disease MRI Analysis Project  
Neuroimaging Research Study
