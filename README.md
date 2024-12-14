# BC-Survival-MLDL
## Application of machine learning in breast cancer survival prediction using a multimethod approach

This repository presents a multi-method approach using a Deep Neural Network (DNN) and 11 conventional machine learning (ML) methods to predict the 5-year survival of women with breast cancer. Supplying data from two centers comprising a total of 2644 records and incorporating external validation further distinguishes the study. Thirty-four features were selected based on a literature review and common variables in both datasets. Feature selection was also performed using a p-value criterion (< 0.05) and a survey involving oncologists. A total of 108 models were trained. According to external validation, the DNN model trained with the Shiraz dataset, considering all features, exhibited the highest accuracy (85.56%). While the DNN model showed superior accuracy in external validation, it did not consistently achieve the highest performance across all evaluation metrics. Notably, models trained with the Shiraz dataset outperformed those trained with the Tehran dataset, possibly due to the lower number of missing values in the Shiraz dataset.

## Model architecture
<h1 align="center">
 <a href="https://github.com/MehradAria/BC-Survival-MLDL"><img src="https://github.com/MehradAria/BC-Survival-MLDL/blob/main/model.png?raw=true" alt="Application of machine learning in breast cancer survival prediction using a multimethod approach"></a>
</h1>

## Inference
You may use [DNN.py](https://github.com/MehradAria/BC-Survival-MLDL/blob/main/DNN.py) to train and test the DNN model, inference is as simple as:

```shell
# Example
classes = best_model_ak.predict(data)
```

---
### Paper / Data / Pre-trained model availability:
- Due to the policies and guidelines of Shahid Beheshti University of Medical Science, data is not allowed for publication.

- The model is not publicly available at this moment due to Git LFS limitations.

---
### Condition and terms to use any sources of this project (Codes, Datasets, etc.):

1) Please cite the following paper:
```
Hamedi, S. Z., Emami, H., Khayamzadeh, M., Rabiei, R., Aria, M., Akrami, M., & Zangouri, V. (2024). Application of machine learning in breast cancer survival prediction using a multimethod approach. Scientific Reports, 14(1), 30147. DOI: 10.1038/s41598-024-81734-y
```

2) Please do not distribute the database or source codes to others without author authorization.
Authors’ Email: `mehrad.aria[at]outlook.com` (M. Aria).

