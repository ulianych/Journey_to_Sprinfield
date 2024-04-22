# Journey to Sprinfield (image classification)
## Description
In this task you will travel to the world of Springfield, where you can meet all your favorite Simpsons characters.
The main task will be to train a classifier based on convolutional networks to learn how to distinguish all the residents of Springfield.
## Evaluation
The evaluation metric for this competition is the Mean F1-Score. The F1-Score is computed based on precision (p) and recall (r). Precision is the ratio of true positives (tp) to the sum of true positives and false positives (tp + fp). Recall is the ratio of true positives to the sum of true positives and false negatives (tp + fn). The F1-Score is then calculated using the following formula:

F1 = 2 * p * r / (p + r), where p = tp / (tp + fp) and r = tp / (tp + fn)

In summary, the F1-Score is a measure that combines both precision and recall to provide an overall assessment of the model's performance.
## Version 1
In Version 1 of the project, a simple CNN was created to demonstrate the working principles of convolutional networks. This initial version serves as a starting point for the development of more sophisticated models.
## Version 2
In Version 2, a pre-trained model called ResNet50 was utilized to improve the classification performance. By leveraging the knowledge learned from a large dataset, the pre-trained model can capture more complex features and potentially achieve higher accuracy compared to the simple CNN used in Version 1. The integration of ResNet50 demonstrates the exploration of advanced techniques and models to enhance the model's performance in distinguishing the residents of Springfield.
