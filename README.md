# Facial Expression Recognition: A Machine Learning Approach with SVM, Random Forest, KNN, and Decision Tree Using Grid Search

## 📄 **Overview**
This project explores facial expression recognition (FER) as a vital interface for bridging human emotions and machine understanding, with applications in healthcare, psychology, and human-computer interaction. It evaluates the performance of machine learning models—**SVM**, **Random Forest**, **KNN**, and **Decision Tree**—on the CK+ dataset using **Grid Search** for hyperparameter optimization. The study highlights the superior performance of SVM for reliable and efficient FER systems.

---

## 📊 **Dataset**
- **Dataset Used:** CK+ (Cohn-Kanade Plus)
- **Description:** A benchmark dataset for FER research containing high-quality images of posed emotions.
- **Preprocessing Techniques:**
  - Grayscale conversion
  - Histogram equalization
- **Feature Extraction:** Histogram of Oriented Gradients (HOG)
- **Data Split:** Cross-validation was performed using k-fold validation.

---

## 🧠 **Algorithms Used**
- **Support Vector Machine (SVM):** Achieved the best performance with a linear kernel.
- **Random Forest:** Robust but slightly less accurate than SVM.
- **K-Nearest Neighbors (KNN):** Performed well on smaller datasets.
- **Decision Tree:** Demonstrated lower accuracy, highlighting interpretability-performance trade-offs.
- **Hyperparameter Optimization:** Grid Search was employed to identify the best parameter configurations for all models.
---
## 📊 **Results**
| Model          | Accuracy (%) | Precision (%) | Recall (%) | F1 Score (%) |
|----------------|-------------|---------------|------------|-------------|
| SVM (Linear)   | 100         | 100           | 100        | 100         |
| Random Forest  | 97          | 98            | 97         | 97          |
| KNN            | 92          | 93            | 92         | 92          |
| Decision Tree  | 79          | 79            | 79         | 78          |

**SVM emerged as the most effective classifier, achieving 100% accuracy when using a linear kernel. Other models demonstrated competitive but slightly lower performances.**

---
## Future Improvements
- Integration of deep learning models (CNNs) for enhanced feature extraction.
- Real-time facial expression recognition deployment.
- Further hyperparameter tuning and optimization.
- Incorporating additional datasets for better generalization.
---

## 👥 **Authors and Co-authors**  

- **Md. Rifat Hossen**  
  Pabna University of Science and Technology, Pabna, Bangladesh
  -Department of Information and Communication Enggineering  
  -E-mail: [rifat.pust.ice14@gmail.com](mailto:rifat.pust.ice14@gmail.com)  
- **Md. Uzzal Mia**  
  Pabna University of Science and Technology, Pabna, Bangladesh
  -Department of Information and Communication Enggineering   
  -E-mail: [uzzal220605.@s.pust.ac.bd](uzzal220605.@s.pust.ac.bd)  
- **Rinku Islam**  
  Pabna University of Science and Technology, Pabna, Bangladesh 

- **Md. Sarwar Hosain**  
  Pabna University of Science and Technology, Pabna, Bangladesh
  -Asscoiate Professor
  -Department of Information and Communication Enggineering   
  E-mail: [sarwar.ice@pust.ac.bd](mailto:sarwar.ice@pust.ac.bd)  

- **Mohammad Kamrul Hasan**  
  National University of Malaysia, Selangor, Malaysia  

- **Tetsuya Shimamura**  
  Saitama University, 255 Shimo-Okubo, Sakura-ku, Saitama 338-8570, Japan

- see the paper [paper](#paper)
