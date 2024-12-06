**Introduction**

Our project focuses on machine learning using an SVM (Support Vector Machine) model. 

We trained the model on EEG data found publicly. OpenNeuro is an open platform where neural data can be found in all formats. We chose EEG data because it is the best at capturing temporal resolution. This means that the smallest changes in the brain can be tracked to the millisecond. This is important when measuring brain activity when stimulated in different ways emotionally. 

The EEG dataset found on OpenNeuro was collected from a psychology study where researchers were investigating brain activity across 7 emotional categories: joy, inspiration, tenderness, fear, disgust, sadness, and neutral. There were 60 subjects in the original however, due to the large file size, we conducted our project on subset of the dataset on 10 of those subjects (2, 3, 4, 5, 6, 7, 9, 10, 11, 12). Subject 8 was skipped due to a lack of data, less imagery was conducted on this subject. 

Our project's code is based on a public GitHub repository on Python Data Science. The 05.07 file is that repository's explanation of SVM and the basics of the code. 


**Instructions**
1. To use our dataset, download the Group_2 dataset zip file and the code file.
2. Unzip the dataset file and ensure the data and the file can be found in the same directory.
3. _(Optional step)_ If your data is found in a subfolder within the directory you can edit line 21 (file_path = os.path.join(dataset_path, f"{sub}_task-emotion_eeg.edf")) and add your subfolder like this: file_path = os.path.join(dataset_path, "subfolder_name", f"{sub}_task-emotion_eeg.edf")
4. Run the code.

