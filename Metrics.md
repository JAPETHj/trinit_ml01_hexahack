P_CURVE:
A plot of precision vs Recall
Recall (Sensitivity): Recall is the ratio of true positive predictions to the total number of actual positives.
It is a measure of how many of the actual positive instances are correctly predicted by the model. 
The precision-recall curve also shows how recall varies with different threshold value.

F1_SCORE:
The F1 score is the harmonic mean of precision and recall and provides a balanced measure of a model's performance.
In the context of object detection or binary classification tasks like those handled by YOLOv5, 
the F1 score is a useful metric to assess both precision and recall simultaneously.

P_CURVE:
This curve visualizes how the precision of a model varies as the confidence threshold for classification is adjusted.
The x-axis represents the confidence threshold, and the y-axis represents precision.
Each point on the curve corresponds to a different threshold value.
As the threshold increases, the model becomes more conservative, resulting in fewer positive predictions but potentially higher precision.

CONFUSION MATRIX:
Confusion matrix is a table that helps evaluate the performance of a classification model by summarizing the results of its predictions on a set of data. 
It provides insights into how well the model is correctly classifying instances and where it might be making mistakes.
>Evaluation Metrics->
 *Accuracy
 *Recall
 *Precision
 *F1_score
>Components->
True Positives (TP):
Instances that are actually positive (belong to the positive class) and are correctly classified as positive by the model.

True Negatives (TN):
Instances that are actually negative (belong to the negative class) and are correctly classified as negative by the model.

False Positives (FP):
Instances that are actually negative but are incorrectly classified as positive by the model. Also known as Type I errors.

False Negatives (FN):
Instances that are actually positive but are incorrectly classified as negative by the model. Also known as Type II errors.

 Basic Representation:
                     Actual Positive      Actual Negative
Predicted Positive        TP                    FP
Predicted Negative        FN                    TN
