# 🔬 Predicting Protein-Drug Binding Affinity with Machine Learning

This project explores how machine learning can be used to predict the **binding affinity** between drug-like molecules (ligands) and target proteins — a crucial task in **drug discovery** and **bioinformatics**.

Using publicly available data from the **BindingDB** and **PDBbind** databases, I trained regression models to estimate how strongly a compound binds to a protein, measured by values such as **Kd** or **IC50**.

---

## 🎯 Objectives

- 📊 Clean and process biochemical data of protein-ligand interactions
- 🧪 Extract molecular descriptors from ligand SMILES strings and protein sequences
- 🤖 Train regression models (Random Forest, XGBoost, Linear Regression) to predict binding affinity
- 📈 Evaluate model performance using MAE, RMSE, R²
- 🧬 Interpret biological and chemical relevance of predictions

---

## 🛠️ Tools & Technologies

- **Languages**: Python  
- **Libraries**: pandas, scikit-learn, matplotlib, seaborn, RDKit, BioPython  
- **Models**: Random Forest, XGBoost, Linear Regression  
- **Data Sources**: BindingDB, PDBbind (optional preprocessing)

---

## 📂 Project Structure
drug-binding-affinity/
│
├── data/            # Raw and processed datasets
├── notebooks/       # Jupyter Notebooks for EDA, modeling, etc.
├── src/             # Python scripts (feature extraction, models)
├── results/         # Outputs, model metrics, plots
├── README.md        # Project overview
└── requirements.txt # Python dependencies


---

## 📈 Results Snapshot

> Example:
- **Best Model:**  
- **R² Score:**   
- **RMSE:**   
- **Top Feature Importances:**
- 
---

## 🧠 What I Learned

- How to process bioinformatics data from multiple sources
- Using **RDKit** and **BioPython** to extract chemical and protein features
- Building and tuning regression models with **scikit-learn**
- Importance of domain understanding in feature selection

---

## 🚀 Future Improvements

- Integrate 3D structural data (e.g. docking scores or descriptors from molecular dynamics)
- Experiment with deep learning (e.g. Graph Neural Networks for molecules)
- Deploy a simple prediction tool using Streamlit or Flask

---

## 📫 Contact

Feel free to reach out if you’re interested in this work or want to collaborate:

- 🌐 [LinkedIn](https://www.linkedin.com/in/ecdazevedo)  
- 📧 erikaa.chang@gmail.com

---

_This project is part of my data science portfolio. I'm actively seeking roles in data science, bioinformatics, or ML — especially in the Netherlands, Germany, or Spain._


