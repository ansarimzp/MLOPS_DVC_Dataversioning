# MLOPS_DVC_Dataversioning

This repository provides a complete, step-by-step tutorial on **Data Versioning using DVC (Data Version Control)** in the context of MLOps. It demonstrates how to version datasets, use Git and DVC together, and track changes across multiple iterations of data.

---

## 📌 Project Objective

To teach and demonstrate the integration of Git and DVC for version-controlling datasets and ML code in an efficient, scalable, and reproducible manner.

---

## 🛠️ Tech Stack

- **Python**
- **Git**
- **DVC**

---

## 📁 Project Structure
MLOPS_DVC_Dataversioning/
├── .dvc/ # DVC internal files
├── s3/files/md5/ # Simulated DVC remote storage
├── .dvcignore # DVC ignore rules
├── .gitignore # Git ignore rules
├── data.dvc # Metadata file for DVC-tracked dataset
├── LICENSE # MIT License
├── README.md # Project documentation
├── content.txt # Versioned data file
├── mycode.py # Python script generating/modifying data
└── (data/) # Folder originally used for raw data


---

## 📚 Step-by-Step Implementation

### ✅ Initial Setup

1. **Create a Git repository** and clone it locally.
2. Create `mycode.py` to generate and save a CSV or TXT file into a `data/` directory.
3. Run the script to generate data.
4. Add and push files to Git:

```bash
git add .
git commit -m "Initial code and dataset added"
git push origin main

