## All data matrices:
* aggr_data -> 813621 instances with 5 columns (subject, Activity_ID, Activity_Label, variable, value)
* data -> combined train and test set, 10299 instances of 82 columns
* subject_test and subject_train-> contains subject field for train and test data
* test_data and train_data -> contains the values for train and test, 2947x82 and 7352x82 respectively
* tidy_data-> cleaned data, 180x81

## Variables used
* activity_label -> list of activities recorded (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING)
* data_labels -> list of the 79 measurements gathered with mean and std
* extract_features -> list to determine if feature is wanted or not
* features -> list of all features available in the dataset
* id_labels-> subject, Activity_ID, Activity_Label
* x and y contains values of each feature