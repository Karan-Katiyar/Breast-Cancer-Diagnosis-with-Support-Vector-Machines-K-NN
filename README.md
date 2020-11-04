# Breast-Cancer-Diagnosis-with-Support-Vector-Machines-K-NN

## Breast-Cancer-Diagnosis-with-Support-Vector-Machines
we will use the Wisconsin Breast Cancer data set, which has already been pre-processed and partitioned into training, validation and test sets. Numpy's loadtxt command can be used to load CSV files.

We use scikit-learn's SVC function to learn SVM models with radial-basis kernels for each combination of  𝐶∈{10−2,10−1,1,101,⋯104}  and  𝛾∈{10−3,10−210−1,1,10,102} . Print the tables corresponding to the training and validation errors.

Final Model Selection: Use the validation set to select the best the classifier corresponding to the best parameter values,  𝐶𝑏𝑒𝑠𝑡  and  𝛾𝑏𝑒𝑠𝑡 . Report the accuracy on the test set for this selected best SVM model. Note: You should report a single number, your final test set accuracy on the model corresponding to  𝐶𝑏𝑒𝑠𝑡  and  𝛾𝑏𝑒𝑠𝑡 .

## Breast-Cancer-Diagnosis-with-K-NN
Use scikit-learn's k-nearest neighbor classifier to learn models for Breast Cancer Diagnosis with  𝑘∈{1,5,11,15,21} , with the kd-tree algorithm.

Plot: For each classifier, compute both the training error and the validation error. Plot them together, making sure to label the axes and each curve clearly.

Final Model Selection: Use the validation set to select the best the classifier corresponding to the best parameter value,  𝑘𝑏𝑒𝑠𝑡 . Report the accuracy on the test set for this selected best kNN model. Note: You should report a single number, your final test set accuracy on the model corresponding to  𝑘𝑏𝑒𝑠𝑡 .

## Conclusion
We can see from the accuracy that SVC (SVM model) performs better than KNN for our dataset as the accuracy of SVC was 96.5217%

Whereas accuracy of KNN is 83.3333333334%.

Another argument is that it is not possible to determine which classification technique does better just by using accuracy.

Since we have the cancer detection dataset, if we classify everything as Non-cancerous, we would probably have an accuracy of over 95%

Thus we need to use further techniques such as confusion matrix to find which algorithm does better.

But without getting into the complexities, on the hindsight SVC classifier does a better job as SVMs can have a non linear

Boundary line and does better with large amounts of data over the simple and intuitive KNN classifier.
