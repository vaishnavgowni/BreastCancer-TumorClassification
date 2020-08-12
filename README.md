# BreastCancer-TumorClassification
## Breast Cancer Detection - Tumor Classification

### Business Understanding:
Breast Cancer is the most common cancer among Women worldwide accounting 25% of all the Cancer cases. Early diagnosis
significantly increases the chances of survival as it can promote timely clinical treatment to patients. On the other hand, accurate
classification of benign tumors (non-cancerous) can prevent patients undergoing unnecessary treatments. Breast cancer is a
type of cancer that begins in the breast. Cancer begins when cells start to develop out of control. Breast cancer cells usually
form a tumor that can often be seen on an x-ray or felt as a lump. It is critical to comprehend that most breast lumps are benign
and not malignant. Here, benign infers non-cancerous tumor and malignant suggests cancer. Non-cancerous breast tumors are
strange developments, yet they do not spread outside of the breast. They are not dangerous; however, a few kinds of benign
breast lumps can build a woman's danger of getting breast cancer. Any breast lump or change should be checked by a health
care professional to decide whether it is benign or malignant (cancer) and on the off chance that it may influence your future
cancer hazard. 

**Goal:** To classify the tumor:

1. Benign (non-cancerous)
2. Malignant (cancerous)

**Dataset:** The dataset consists of features extracted from a digitized image of a fine needle aspirate (FNA) of a breast mass. These features describe characteristics of the cell nuclei present in the image.

**Example:**

        - radius (mean of distances from center to points on the perimeter)
        - texture (standard deviation of gray-scale values)
        - perimeter
        - area
        - smoothness (local variation in radius lengths)
        - compactness (perimeter^2 / area - 1.0)
        - concavity (severity of concave portions of the contour)
        - concave points (number of concave portions of the contour)
        - symmetry 
        - fractal dimension ("coastline approximation" - 1)

**Notes:**

1. Datasets are linearly separable using all 30 input features
2. Number of Instances: 569
3. Class Distribution: 212 Malignant, 357 Benign
4. Target class:
         - Malignant
         - Benign

### Data Source

https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

## Table of Contents

     1. Business Understanding
     2. Data Acquisition
     3. Exploratory Data Analysis
     4. Modelling
     5. Model Evaluation
     6. Deployment
     
https://www.vaishnavgowni.com/
