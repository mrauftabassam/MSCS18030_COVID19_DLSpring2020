# MSCS18030_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.
==========================================================
Task 1: Load pretrained CNN model and fine-tune FC Layers
==========================================================
By Using VGG16: 

    Testing Accuracy: 94%
    
    F1 Score: 0.94
    
    Confusion Matrix on Test Data: 
|               |            | Predicted Values |          |
|:-------------:|:----------:|:----------------:|:--------:|
|               |            |    “infected”    | “normal” |
| Actual Values | “infected” |     TP = 552     |  FN = 63 |
|               |  “normal”  |      FP = 27     | TN = 858 |
		
By Using RES18: 

    Testing Accuracy: 96%
    
    F1 Score: 0.97
    
    Confusion Matrix on Test Data: 
|               |            | Predicted Values |          |
|:-------------:|:----------:|:----------------:|:--------:|
|               |            |    “infected”    | “normal” |
| Actual Values | “infected” |     TP = 587     |  FN = 28 |
|               |  “normal”  |      FP = 21     | TN = 864 |

=================================================================
