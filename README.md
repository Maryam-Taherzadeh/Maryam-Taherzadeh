# 👩‍🔬 Maryam Taherzadeh

Hi there! I'm a Computational Scientist and Machine Learning Researcher based in California, with dual Master's degrees in Computer Science and Physical Chemistry.

I specialize in AI-driven drug discovery, cheminformatics, molecular property prediction, and pharmacokinetic data modeling. My work combines machine learning, computational chemistry, and public biomedical datasets to build practical AI workflows for drug discovery and molecular modeling.

🌐 **Portfolio:** https://maryamtaherzadeh.com

## 🔬 Areas of Expertise

- **AI for Drug Discovery:** Agentic AI, RAG, LLM applications, QSAR/QSPR, molecular property prediction, bioactivity modeling
- **Molecular Modeling & Cheminformatics:** Python, RDKit, DeepChem, ChEMBL, molecular fingerprints, molecular descriptors
- **Bioactivity & Property Prediction:** IC50, pIC50, ESOL, AqSolDB, solubility prediction
- **Pharmacokinetic Modeling:** PK-DB, concentration-time prediction, dose extraction, PK/PD data workflows
- **Machine Learning:** Random Forest, XGBoost, SVR, SVM, neural networks, model evaluation
- **Deep Learning for Molecules:** Graph Neural Networks, ChemBERTa, PyTorch Geometric
- **Generative AI & Retrieval:** Retrieval-Augmented Generation (RAG), semantic search, sentence-transformer embeddings, grounded LLM responses
- **Cloud & Deployment:** Streamlit, Hugging Face Spaces, Docker, GCP

## 🌟 Featured Projects

### 🤖 Agentic AI Drug Discovery: MDM2–p53

End-to-end agentic AI drug discovery workflow for MDM2–p53 inhibitor prioritization.

This project includes ChEMBL bioactivity data processing, RDKit descriptor generation, live pIC50 prediction using an XGBoost regression model, Lipinski drug-likeness evaluation, rule-based candidate recommendation, and a Streamlit app for interactive SMILES-based screening.

**Live Demo:**  
https://huggingface.co/spaces/Maryam-Taherzadeh/agentic-ai-mdm2-p53

---

### 💬 MDM2–p53 RAG Drug Discovery Chatbot

A scientific Retrieval-Augmented Generation (RAG) chatbot for exploring computational evidence from an MDM2–p53 inhibitor discovery workflow.

The application integrates candidate-level results from multiple stages of the drug discovery pipeline, including predicted pIC50, ADMET properties, QED and physicochemical properties, molecular docking, molecular dynamics stability metrics, MM/GBSA binding energies, and final candidate rankings.

The system uses sentence-transformer embeddings and semantic retrieval to identify relevant project evidence, then generates grounded answers using an OpenAI model. The interface is deployed as an interactive Streamlit chatbot.

**Live App:**  
https://mdm2-rag-chatbot-3yl9ntlurwsaseefvjms2k.streamlit.app/

**Technologies:** Python, Streamlit, RAG, OpenAI API, sentence transformers, semantic search, pandas, QSAR, ADMET, molecular docking, molecular dynamics, MM/GBSA

---

### ☕ Caffeine PK Modeling with Public PK-DB Data

Machine learning workflow for caffeine pharmacokinetic concentration-time prediction using public PK-DB data.

The project extracts and standardizes caffeine concentration-time records, converts concentration units to ng/mL, extracts caffeine dose from intervention metadata, and benchmarks regression models for concentration prediction.

The current dataset includes 504 caffeine concentration-time records across 5 public PK-DB studies, with 193 rows containing extractable caffeine dose information. Adding dose as a structured feature improved Gradient Boosting performance to approximately R² = 0.90 on the dose-available subset.

**GitHub:**  
https://github.com/Maryam-Taherzadeh/Caffeine-Pk-Modeling-PKPD

---

### 🧬 Computational Drug Discovery: MDM2–p53 Inhibitors

Bioactivity prediction workflow for MDM2–p53 inhibitors using ChEMBL IC50 data, RDKit descriptors, molecular fingerprints, Random Forest, XGBoost, SVR, and hyperparameter tuning for pIC50 prediction.

**GitHub:**  
https://github.com/Maryam-Taherzadeh/Computational-Drug-Discovery

---

### 🧪 Solubility Prediction App using Graph Neural Networks

Streamlit app for predicting aqueous solubility of small molecules using Graph Neural Networks, RDKit, PyTorch Geometric, and the AqSolDB dataset.

**Live App:**  
https://predictsolubilitygnn.streamlit.app/

---

### 📊 QSPR using Machine Learning

Feature selection and SVM/ANN-based QSPR modeling for molecular property prediction.

---

### 📈 Time Series Forecasting

Daily sales forecasting using Facebook Prophet and time series analysis.

## 🛠️ Technical Skills

**Programming:** Python, SQL, R, HTML/CSS  
**Machine Learning:** scikit-learn, XGBoost, SVR, Random Forest, neural networks  
**Deep Learning:** PyTorch, PyTorch Geometric, TensorFlow/Keras  
**Generative AI:** RAG, LLM applications, semantic retrieval, sentence-transformer embeddings, OpenAI API  
**Cheminformatics:** RDKit, DeepChem, ChEMBL, molecular fingerprints, SMILES processing  
**Computational Chemistry:** Molecular docking, molecular dynamics, MM/GBSA, ADMET analysis  
**Visualization:** Matplotlib, Seaborn, Tableau  
**Deployment:** Streamlit, Hugging Face Spaces, Docker, GCP  
**Scientific Domains:** Computational drug discovery, QSAR/QSPR, PK/PD modeling, molecular property prediction

## 📫 Connect with Me

🌐 **Portfolio:**  
https://maryamtaherzadeh.com

**LinkedIn:**  
https://www.linkedin.com/in/maryam-taherzadeh/

**GitHub:**  
https://github.com/Maryam-Taherzadeh
