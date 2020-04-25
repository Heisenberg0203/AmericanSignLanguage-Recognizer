Different CNN structures for classifying American Hand Signs along with their training and testing accuracies:


|Model|Number of Convolution layers|Augmentation|Batch Normalisation|Dropout|Training Accuracy|Test Accuracy|
|:-----:|:----------------------------:|:------------:|:-------------------:|:-------:|:-----------------:|:-------------:|
|model1|1|yes|yes|no|97.52|97.71|
|model2|2|no|no|no|100|91.06|
|model3|2|no|yes|no|100|95.60|
|model4|2|yes|yes|no|94.58|98.41|
|model5|2|yes|yes|no|99.32|99.71|
|model6|2|yes|yes|no|98.70|99.51|
|model7|2|yes|yes|0.4|94.09|98.42|
|model8|2|yes|yes|0.4,0.4|84.27|91.98|
|model9|3|yes|yes|no|99.23|99.33|
|model10|3|yes|yes|no|91.90|98.1|
|model10|3|yes|yes|0.4|91.90|98.1|
|model11|3|yes|yes|0.2|92.32|97.5|
|model12|4|no|yes|no|100|96.10|
|model13|4|yes|yes|no|99.28|99.83|
|model14 with dynamic learning rate|4|yes|yes|no|99.71|100|




