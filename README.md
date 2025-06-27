# Task4 Breast Cancer Classification with Logistic Regression
                                                                                                                                                                         
This repository contains a complete implementation of a logistic regression model for classifying breast tumors as malignant or benign using the Breast Cancer Wisconsin dataset. The project demonstrates core machine learning workflows including data preprocessing, model training, evaluation, and interpretation with comprehensive visualizations.                                                                                                                                            

**Key Features:**                                                                                                                                                        
End-to-end ML pipeline from data loading to deployment-ready model.                                                                                                      
Optimal threshold tuning using Youden's J statistic.                                                                                                                     
Detailed mathematical explanation of logistic regression.                                                                                                                
Comprehensive performance metrics and visualizations.                                                                                                                    
Feature importance analysis for model interpretability.                                                                                                                 

**Dataset**                                                                                                                                                          
The Breast Cancer Wisconsin Diagnostic Dataset contains 569 samples with 30 features computed from digitized images of fine needle aspirates (FNA) of breast masses. Features describe characteristics of cell nuclei like:                                                                                                       

radius_mean - Mean distance from center to points on perimeter.                                                                                                       
texture_mean - Standard deviation of gray-scale values.                                                                                                               
concavity_worst - Worst severity of concave portions of contour and 27 other computed features.                                                                      

**Class Distribution:**                                                                                                                                              
Benign (B): 357 samples (62.7%)                                                                                                                                      
Malignant (M): 212 samples (37.3%)                                                                                                                                   

**Installation**                                                                                                                                                     
1.Clone the repository:                                                                                                                                              
git clone https://github.com/yourusername/breast-cancer-classification.git                                                                                               
cd breast-cancer-classification                                                                                                                                       
2.Create and activate virtual environment: 												                                                                                                                                                                                                          
python -m venv venv                                                                                                                                                  
source venv/bin/activate  # Linux/macOS                                                                                                                              
venv\Scripts\activate     # Windows                                                                                                                                     
3.Install dependencies:                                                                                                                                                        
pip install -r requirements.txt                                                                                                                                      

**Usage**                                                                                                                                                            
Run the complete analysis: python breast_cancer_classification.py                                                                                                    

This will:                                                                                                                                                           
1. Download the dataset from GitHub                                                                                                                                      
2. Preprocess and standardize features                                                                                                                                   
3. Train the logistic regression model                                                                                                                                  
4. Generate evaluation metrics and visualizations                                                                                                                       
5. Save all plots in high-resolution PNG format                                                                                                                          

**Workflow Overview**                                                                                                                                                

![image](https://github.com/user-attachments/assets/24444882-5726-4b03-b66e-8e1bc03b363f)                                                                            

**References**                                                                                                                                                       
1. Breast Cancer Wisconsin Dataset: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic                                                                                          
2. Scikit-learn Documentation: https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression                                                         
3.Pedregosa et al. (2011): https://jmlr.org/papers/v12/pedregosa11a.html                                                                                              
