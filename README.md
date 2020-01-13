# Diagnostic Tool for mental health

### Inputs
1. EEG signals
2. Peripheral hysiological signals
3. Battery test
   
### Outputs
1. Emotional Profiling of the subject
2. Recommendation

### Task Assigned

1. Learn about EEG related characteristic from other EEG data 
    * Arithematic tasks
    * Visual Tasks
    * Motor tasks
2. Learned machine will then be used for Emotional Profiling.
3. Hence, fine tuned machine by using ***transfer learning*** will be used to give ***muli-labelling output***.

### tasks

#### Week1:

1. Understood the project and learned basics of machine learning and what transfer learning is.
2. Understood what MNIST database is and how to implement it.
3. Implemented MNIST database using KNN.
4. Changed parameters of the model to analyise the change in output
 
#### Week2:

1. Explored more about EEG related data/signals are classified and dealt with.
2. Read the documentation of motor tasks dataset and tried to analysis and how to deal with the signals. 

### Week3:
1. Loading and preprocessing of data from mne library
``` python
fnames = eegbci.load_data(subject, runs)
```
2.
#### Week4:
1.Classified the files according to events and added them in a variable ```task```.
2. Prepared y matrix
3. Split the data in train and test sets. 
4. Built a CNN model using Tensorflow and keras for multilabel classification.


### References

1. For understanding dataset: [official documentation](https://mne.tools/stable/generated/mne.datasets.eegbci.load_data.html?highlight=eegbci)
2. Understanding multi label classification: [Here](https://towardsdatascience.com/journey-to-the-center-of-multi-label-classification-384c40229bff)




