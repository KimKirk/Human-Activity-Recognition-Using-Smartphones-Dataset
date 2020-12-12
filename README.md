# Samsung Galaxy S II Smartphone Analysis
- Human Activity Recognition Data Analysis Using Samsung Galaxy S II Smartphone

- Healthcare: Wearables/Sensors

- Descriptive multivariate data analysis was conducted in R using "Human Activity Recognition Using Smartphones Dataset Version 1.0" from the UC Irvine Machine Learning Repository that includes triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration, triaxial Angular velocity from the gyroscope, 561 variables with time and frequency domain data, activity labels, and identifiers of the subject who carried out the experiment.

- Seven data files were gathered, merged, munged, and organized to create one data set. The data was analyzed and descriptive statistics were generated. The mean was calculated of each feature that contained the mean or standard deviation for that feature. A barplot visualization shows the mean for the subject's activity for each feature.

- The "Human Activity Recognition Using Smartphones Dataset Version 1.0" and represents six activities subject's carried out during experiments using the Samsung Galaxy S II smartphone. A complete explanation can be found at the [website](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Processing Instructions:
- [Report Here](https://kimkirk.github.io/Human-Activity-Recognition-Using-Smartphones-Dataset/)
- To improve reproducibility of the data analysis, a Jupyter Notebook file and RMD file are included.
- To read Jupyter Notebook file:
  - Use R for Jupyter Notebook
    - install R essentials packages for use in Jupyter Notebook.
    - at command line enter "conda install -c r r-essentials" without quotes.
    - [install IRKernel, a kernel for R](https://irkernel.github.io/installation/)
- Use R Studio or other application to read R-Markdown file.

## Steps to Transformation:
- [Data download](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)
- Files "features", "activity_labels", train files: "subject_train", "X_train", "y_train", test files: "subject_test", "X_test", "y_test" were imported into R studio. 
- Factor labels were created and bound to "features", "activity_labels", "subject_test", and "subject_train" files.
- Columns were renamed for human readability.
- "train" and "test" data sets were merged together to create a final data set.
- The final data set was subset for variables representing the mean and standard deviation of the features.
- Barplots were created for each subject's activity showing the mean for features variables. 
