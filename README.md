# AI-Powered Drug Discovery Using Deep Learning

This project implements a novel deep learning approach for predicting molecular bioactivity from SMILES strings. By treating SMILES as sequential data and applying a custom 1D Convolutional Neural Network (CNN), the model classifies compounds as bioactive (active/inactive) without relying on traditional chemical descriptors.


##  Overview

- **Domain**: Drug Discovery / Bioinformatics  
- **Goal**: Predict the bioactivity of molecules using raw SMILES data  
- **Approach**: Deep learning via tokenized SMILES + 1D CNN  
- **Dataset**: Molecule classification dataset targeting EGFR (ChEMBL-based)


##  Key Features

-  Sequence-based SMILES modeling (NLP-style)
-  Custom CNN model with Embedding, Conv1D, Pooling, and Dense layers
- Real-time visualization of training performance (Accuracy, Loss, ROC)
-  Prediction function to classify new SMILES inputs
-  Achieved ~96.2% validation accuracy


##  Model Architecture

- **Input**: Tokenized SMILES strings  
- **Architecture**:  
  - Embedding Layer  
  - 1D Convolutional Layer  
  - Global Max Pooling  
  - Dropout Layer  
  - Dense (ReLU)  
  - Dense (Sigmoid)  
- **Output**: Binary classification (Active / Inactive)


##  Results

- **Validation Accuracy**: 96.2%  
- **Test Prediction Confidence**: 98.3%  
-  **Evaluation Metrics**:  
  - Accuracy / Loss Curves  
  - Confusion Matrix  
  - ROC Curve  
  - Real-time prediction output


##  Novelty Introduced

This project introduces a novel method by treating SMILES strings as character-level sequences and applying deep learning directly to them, rather than relying on hand-crafted molecular descriptors. Inspired by natural language processing (NLP), this approach enables the model to automatically learn chemical patterns from raw data, reducing the dependency on domain-specific feature engineering. The solution is scalable, efficient, and generalizable to other drug targets beyond EGFR.


##  Author

Developed by [**Jasmine Savathallapalli**](https://github.com/jasminesavathallapalli)  

##  License

This project is intended for academic and research use.
