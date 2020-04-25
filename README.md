# MSCS18030_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

# Task 1: Load pretrained CNN model and fine-tune FC Layers

### By Using VGG16: 
Code for this experiment is attached named as "covid19_classification_01.ipynb"

    Testing Accuracy: 94%
    
    F1 Score: 0.94
    
    Confusion Matrix on Test Data: 
|               |            | Predicted Values |          |
|:-------------:|:----------:|:----------------:|:--------:|
|               |            |    “infected”    | “normal” |
| Actual Values | “infected” |     TP = 552     |  FN = 63 |
|               |  “normal”  |      FP = 27     | TN = 858 |
		
### By Using RES18: 
Code for this experiment is attached named as "covid19_classification_02.ipynb"

    Testing Accuracy: 96%
    
    F1 Score: 0.97
    
    Confusion Matrix on Test Data: 
|               |            | Predicted Values |          |
|:-------------:|:----------:|:----------------:|:--------:|
|               |            |    “infected”    | “normal” |
| Actual Values | “infected” |     TP = 587     |  FN = 28 |
|               |  “normal”  |      FP = 21     | TN = 864 |

=================================================================

# Task 2: Fine-tune the CNN and FC layers of the network

### By Using VGG16: 
Code for this experiment is attached named as "covid19_classification_05.ipynb"

    Testing Accuracy: 97%
    
    F1 Score: 0.98
    
    Confusion Matrix on Test Data: 
|               |            | Predicted Values |          |
|:-------------:|:----------:|:----------------:|:--------:|
|               |            |    “infected”    | “normal” |
| Actual Values | “infected” |     TP = 594     |  FN = 21 |
|               |  “normal”  |      FP = 14     | TN = 871 |
		
### By Using RES18: 
Code for this experiment is attached named as "covid19_classification_10.ipynb"

    Testing Accuracy: 96%
    
    F1 Score: 0.97
    
    Confusion Matrix on Test Data: 
|               |            | Predicted Values |          |
|:-------------:|:----------:|:----------------:|:--------:|
|               |            |    “infected”    | “normal” |
| Actual Values | “infected” |     TP = 586     |  FN = 29 |
|               |  “normal”  |      FP = 23     | TN = 862 |

=================================================================

#### Note: Other experiments results are reported in attached report named as "Report_A5.pdf"
