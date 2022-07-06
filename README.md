# EEG-Eye-State

Problem Statement
In 1958, the International Federation of Societies for Electroencephalography and Clinical Neurophysiology proposed an international standard for routine scalp EEG recording for clinical use. There are  21 electrodes placed at relative distances between cranial landmarks over the head. Electroencephalography (EEG) can be used to measure brain activity in many applications that require human input. Brain stimuli, for example, have been used as an input mode for computer games, to track emotions, for disabled people to control devices, and in various military scenarios. As a result, determining which specific stimuli can be detected with sufficient accuracy is critical.

We will be concentrating on the problems involving predicting whether subjects' eyes are open or closed based on brain wave data. Specifically, an electroencephalography (EEG) recording of a single person was made for 117 seconds while the subject opened and closed their eyes, which was captured on video. 

The motive of the project is to use the given 14 features to classify the state of the eye by implementing multiple machine learning algorithms.

Data Sources
​​All data is from one continuous EEG measurement with the Emotiv EEG Neuroheadset. The duration of the measurement was 117 seconds. The eye state was detected via a camera during the EEG measurement and added later manually to the file after analyzing the video frames. All values are in chronological order with the first measured value at the top of the data.

Link to the UCI repository: https://archive.ics.uci.edu/ml/datasets/EEG+Eye+State


Data Description
Number of Attributes: 15
Number of Instances: 14,980
