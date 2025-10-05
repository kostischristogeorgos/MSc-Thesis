# MSc-Thesis
**Overview**

This repository contains the code and resources for my thesis project on fraud detection in banking operations. The study focuses on the challenge of **highly imbalanced datasets**, where fraudulent cases represent only a small fraction of transactions. Using real-world credit card transaction data from the European Union, the project investigates **resampling techniques** and **machine learning classifiers** to improve fraud detection.

**Objectives**

- **Analyze** the distribution of features between legitimate and suspicious transactions.  
- **Apply** resampling techniques (**undersampling** and **oversampling**) to handle class imbalance.  
- **Evaluate** three classification models:  
  - **Feed Forward Neural Network**  
  - **Random Forest Classifier**  
  - **Balanced Random Forest Classifier**  
- **Run** a total of 16 experiments combining different resampling and classifier configurations.  
- **Assess** model performance using metrics suitable for imbalanced data (**recall**, **precision**, **F1-score**).  

**Dataset**

- **Source:** Real-world anonymized credit card transaction data from the European Union.  
- **Characteristics:** Strong class imbalance, fraudulent cases represent less than 1% of the dataset.  
- **Link:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

**Methods**

- **Resampling Techniques:**  
  - **Random undersampling**  
  - **Random oversampling**  

- **Classifiers:**  
  - **Feed Forward Neural Network**  
  - **Random Forest**  
  - **Balanced Random Forest**  

- **Evaluation Metrics:**  
  - **Recall, primary metric for the fraudulent class**  
  - **Precision**  
  - **F1-score**  

**Experiments**

- **16 experiments** were carried out by combining:  
  - **2 resampling strategies**  
  - **3 classifiers**  
  - **Different parameter settings**  

Results emphasize the importance of properly addressing **class imbalance** in fraud detection.  

**Results**

- **Balanced Random Forest** achieved the most stable performance across resampling setups.  
- **Feed Forward Neural Network** and **Random Forest** showed improvements under certain resampling strategies.  
 - A particular setting of the **Feed Forward Neural Network** was the best model throughout all the experiments.
