# Module-14-Challenge

## 3 Months Baseline

| Precision | Recall | F1-Score | Support |
|-----------|--------|----------|---------|
| -1.0      | 1.00   | 0.06     | 49      |
| 1.0       | 0.63   | 1.00     | 79      |

| Accuracy  |        |          | 0.64    |
| Macro Avg | 0.82   | 0.53     | 0.44    |
| Weighted Avg | 0.77 | 0.64     | 0.52    |

## 6 Months

| Precision | Recall | F1-Score | Support |
|-----------|--------|----------|---------|
| -1.0      | 0.59   | 0.20     | 122     |
| 1.0       | 0.58   | 0.89     | 154     |

| Accuracy  |        |          | 0.58    |
| Macro Avg | 0.58   | 0.54     | 0.50    |
| Weighted Avg | 0.58 | 0.58     | 0.52    |

## 2 Months

| Precision | Recall | F1-Score | Support |
|-----------|--------|----------|---------|
| -1.0      | 0.80   | 0.40     | 30      |
| 1.0       | 0.72   | 0.94     | 49      |

| Accuracy  |        |          | 0.73    |
| Macro Avg | 0.76   | 0.67     | 0.67    |
| Weighted Avg | 0.75 | 0.73     | 0.71    |

## Logistic Regression Model Results

**Logistic Regression Classification Report**

| Precision | Recall | F1-Score | Support |
|-----------|--------|----------|---------|
| -1.0      | 0.00   | 0.00     | 112     |
| 1.0       | 0.58   | 1.00     | 157     |

| Accuracy  |        |          | 0.58    |
| Macro Avg | 0.29   | 0.50     | 0.37    |
| Weighted Avg | 0.34 | 0.58     | 0.43    |

The model has reasonable performance on class 1.0, yet it fails to correctly identify any instances of class -1.0, resulting in an F1-score of 0 for this class. This logistic model demonstrates an imbalance in its performance. In summary, while the model performs reasonably well for class 1.0, it requires significant improvement to effectively handle class -1.0.









