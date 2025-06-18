# Handwritten-signature-Verification

This project implements a Siamese Neural Network to verify whether two handwritten signatures belong to the same person. It uses the **CEDAR Signature Dataset** and deep learning techniques to compare signature images.
---

## 🧠 Objective
To build a model that can determine if a given signature is genuine or forged by comparing it with a known reference signature.

---

## 📁 Project Structure

handwritten_signature_verification/
├── notebook/
│ └── signature_verification_cleaned.ipynb # Main notebook
├── requirements.txt # Required packages
└── README.md # Project documentation

yaml
Copy code

---

## 📊 Dataset

- **Dataset Used:** CEDAR Handwritten Signature Dataset  
- **Source:** [CEDAR Signature Dataset](https://www.kaggle.com/datasets/shreelakshmigp/cedardataset)  
- The dataset includes genuine and forged signatures from 55 individuals.
---

## ⚙️ How to Run

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/handwritten_signature_verification.git
cd handwritten_signature_verification
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the notebook:
Open signature_verification_cleaned.ipynb using Jupyter Notebook or VS Code and run all cells.
