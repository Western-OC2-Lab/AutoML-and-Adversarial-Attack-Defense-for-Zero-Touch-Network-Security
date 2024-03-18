# AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security
This repository includes code for the AutoML-based IDS and adversarial attack defense case studies presented in the paper "[Enabling AutoML for Zero-Touch Network Security: Use-Case Driven Analysis](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10472316)" published in IEEE Transactions on Network and Service Management.

The paper is publicly available on Techrxiv: [Enabling AutoML for Zero-Touch Network Security: Use-Case Driven Analysis](https://www.techrxiv.org/users/692878/articles/682818-diving-into-zero-touch-network-security-use-case-driven-analysis)

- This code is an extension of the comprehensive **Automated Machine Learning (AutoML)** tutorial code can be found in: [AutoML-Implementation-for-Static-and-Dynamic-Data-Analytics](https://github.com/Western-OC2-Lab/AutoML-Implementation-for-Static-and-Dynamic-Data-Analytics)  
   * Including **automated data pre-processing, automated feature engineering, automated model selection, hyperparameter optimization, and automated model updating** (concept drift adaptation).
   * For cybersecurity and intrusion detection system development in both static and dynamic networking environments.

## AutoML Pipeline and Procedures
1. Automated Data Pre-Processing
2. Automated Feature Engineering
3. Automated Model Selection
4. Hyper-Parameter Optimization
5. Automated Model Updating (for addressing concept drift, and only for online learning and data stream analytics)

<p align="center">
<img src="https://github.com/Western-OC2-Lab/AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security/blob/main/Figures/AutoML.jpg" width="800" />
</p>

## Adversarial Machine Learning (AML) Attack and Defense

<p align="center">
<img src="https://github.com/Western-OC2-Lab/AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security/blob/main/Figures/AML.jpg" width="600" />
</p>

## Implementation
* The offline AutoML-based IDS implementation for **static/batch data analytics** can be found in [AutoML-based_IDS_Batch_Learning_Dataset_1.ipynb](https://github.com/Western-OC2-Lab/AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security/blob/main/AutoML-based_IDS_Batch_Learning_Dataset_1.ipynb) and [AutoML-based_IDS_Batch_Learning_Dataset_2.ipynb](https://github.com/Western-OC2-Lab/AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security/blob/main/AutoML-based_IDS_Batch_Learning_Dataset_2.ipynb)

* The online AutoML-based IDS implementation for **dynamic/online data stream analytics** can be found in [AutoML-based_IDS_Online_Learning_Dataset_1.ipynb](https://github.com/Western-OC2-Lab/AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security/blob/main/AutoML-based_IDS_Online_Learning_Dataset_1.ipynb) and [AutoML-based_IDS_Online_Learning_Dataset_2.ipynb](https://github.com/Western-OC2-Lab/AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security/blob/main/AutoML-based_IDS_Online_Learning_Dataset_2.ipynb)

* The AML attack and defense implementation can be found in [AML_Attack_and_Defense_Dataset_1.ipynb](https://github.com/Western-OC2-Lab/AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security/blob/main/AML_Attack_and_Defense_Dataset_1.ipynb) and [AML_Attack_and_Defense_Dataset_2.ipynb](https://github.com/Western-OC2-Lab/AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security/blob/main/AML_Attack_and_Defense_Dataset_2.ipynb)

### Static Machine Learning & Deep Learning Algorithms  
* Random forest (RF)
* LightGBM  
* K-nearest neighbor (KNN)  
* Artificial Neural Networks (ANN)

### Dynamic/Online Learning Algorithms  
* Hoeffding Tree (HT)
* K Nearest Neighbors-Adaptive Windowing (KNN-ADWIN)
* Adaptive Random Forest (ARF) 
* Streaming Random Patches (SRP)

### Optimization/AutoML Algorithms  
* Grid search
* Bayesian Optimization with Tree-structured Parzen Estimator (BO-TPE)
* Particle Swarm Optimization (PSO)

### AML Attacks 
* Decision Tree Attack (DTA)
* Fast Gradient Sign Method (FGSM)
* Basic Iterative Method (BIM)

### AML Defense Methods
* Adversarial Sample Detection
* Adversarial Sample Filtering/Removal

### Datasets 
1. CICIDS2017 dataset, a popular network traffic dataset for intrusion detection problems
   * Publicly available at: https://www.unb.ca/cic/datasets/ids-2017.html  
   
2. 5G-NIDD dataset, a state-of-the-art 5G network security dataset
   * Publicly available at: https://ieee-dataport.org/documents/5g-nidd-comprehensive-network-intrusion-detection-dataset-generated-over-5g-wireless

### Requirements  
* Python 3.6+ 
* [Keras](https://keras.io/) 
* [scikit-learn](https://scikit-learn.org/stable/)  
* [hyperopt](https://github.com/hyperopt/hyperopt)  
* [optunity](https://github.com/claesenm/optunity)
* [LightGBM](https://lightgbm.readthedocs.io/en/latest/)  
* [River](https://riverml.xyz/dev/)
* [Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox)


## Contact-Info
Please feel free to contact me for any questions or cooperation opportunities. I'd be happy to help.
* Email: [liyanghart@gmail.com](mailto:liyanghart@gmail.com)
* GitHub: [LiYangHart](https://github.com/LiYangHart) and [Western OC2 Lab](https://github.com/Western-OC2-Lab/)
* LinkedIn: [Li Yang](https://www.linkedin.com/in/li-yang-phd-65a190176/)  
* Google Scholar: [Li Yang](https://scholar.google.com.eg/citations?user=XEfM7bIAAAAJ&hl=en)

## Citation
If you find this repository useful in your research, please cite this article as:  

L. Yang, M. E. Rajab, A. Shami, and S. Muhaidat, "Enabling AutoML for Zero-Touch Network Security: Use-Case Driven Analysis," IEEE Transactions on Network and Service Management, pp. 1-28, 2024, doi: 10.1109/TNSM.2024.3376631.

```
@article{10472316,
title = "Enabling AutoML for Zero-Touch Network Security: Use-Case Driven Analysis",
author = "Li Yang, Mirna El Rajab, Abdallah Shami, and Sami Muhaidat",
journal = "IEEE Transactions on Network and Service Management",
volume = {},
pages = {1-28},
year = "2024",
doi = "https://doi.org/10.1109/TNSM.2024.3376631",
url = "https://ieeexplore.ieee.org/document/10472316"
}
```

