# Brain MRI Classification & Segmentation 🧠🩺

## 🚀 Project Overview

This notebook provides an end-to-end pipeline for two tasks on Brain MRI scans:

- **Classification**: Distinguish between healthy and diseased MRI images using Transfer Learning (ResNet50).
- **Segmentation**: Delineate regions of interest (e.g., tumors) in MRI slices with U-Net architectures.

All code (data loading, EDA, model training, evaluation, and visualization) is contained within a single Jupyter notebook.

---

## 📂 Files

```
├── Brain_MRI_Classification&Segmentation.ipynb   # Comprehensive notebook with code & plots
├── images/                                      # Visualization outputs (PNG files)
├── requirements.txt                             # Python dependencies
└── README.md                                    # Project overview and instructions
```

---

## 🔗 Data Reference

This project uses the [Brain MRI segmentation](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation) dataset on Kaggle.

1. Visit the Kaggle link above.
2. Download and unzip the dataset.

---

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/v4nui/Brain_MRI_Class-Seg.git
   cd brain-mri-analysis
   ```
2. Create & activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # Linux/macOS
   venv\Scripts\activate     # Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🔍 Usage

Open and run the notebook:

```bash
jupyter notebook Brain_MRI_Classification\&Segmentation.ipynb
```

---

## 🤝 Contributing

Contributions and suggestions are welcome! Please open an issue or submit a pull request.

---

## 📬 Contact

For questions or feedback, reach out at [vanuhi@live.com](mailto:vanuhi@live.com).
