SCAi-Detect — Sickle Cell Anemia Detection

SCAi-Detect is a deep learning-based medical image classification
project developed for the detection of Sickle Cell Anemia (SCA)
from blood cell images.

The project uses the **SCAi-SCAResNet** model and evaluates its
performance using multiple classification metrics.


Dataset

The dataset contains a total of **12,000 images**.

| Dataset Split | Number of Images |
|---|---:|
| Training | 9,600 |
| Validation | 1,200 |
| Testing | 1,200 |
| **Total** | **12,000** |

The complete dataset is not included in this GitHub repository
because of its large size.

### Dataset Source

The original dataset can be accessed from:

**[Dataset Link](https://www.kaggle.com/datasets/jocelyndumlao/anerbc-anemia-diagnosis-using-rbc-images)**

To reproduce the project, download the dataset from the original
source and provide the appropriate dataset path in the notebook.

Model

SCAi-SCAResNet

The project uses **SCAi-SCAResNet** as the deep learning model
for Sickle Cell Anemia image classification.

The model was trained using the training dataset and evaluated
using separate validation and test datasets.


Final Results

The final model produced the following results on the test dataset:

| Metric | Result |
|---|---:|
| Test Accuracy | **90.58%** |
| Precision | **90.79%** |
| Recall | **90.33%** |
| F1-Score | **90.56%** |
| ROC-AUC | **97.98%** |
| Best Validation Accuracy | **92.83%** |

### Performance Summary

- **Test Accuracy:** 90.58%
- **Precision:** 90.79%
- **Recall:** 90.33%
- **F1-Score:** 90.56%
- **ROC-AUC:** 97.98%
- **Best Validation Accuracy:** 92.83%


 
Dataset Distribution

The dataset was divided into:

- **80% Training:** 9,600 images
- **10% Validation:** 1,200 images
- **10% Testing:** 1,200 images

This resulted in a total of **12,000 images** used in the project.



Project Structure

```text
SCAi-Detect/
│
├── notebook/
│   └── SCAi_SCAResNet.ipynb
│
├── results/
│   └── SCAi_final_results.json
│
├── README.md
│
└── requirements.txt
