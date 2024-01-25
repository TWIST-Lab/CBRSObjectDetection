# CBRSObjectDetection
##Overview
Speclearn is a YOLOv5-based machine learning framework developed for detecting radar signals in shared spectrum environments, particularly in noisy conditions. It aims to address the challenges of signal detection within the 3.5 GHz Citizen Broadband Radio Service (CBRS) band, focusing on maintaining high accuracy amidst various types of synthetic noise.

##Features
Robust Detection: Utilizes YOLOv5 for object detection, trained on clean spectrograms to accurately identify radar signals.
Noise Tolerance: Evaluates the model's performance under different noise conditions, emphasizing on extreme noise scenarios.
Experimental Analysis: Includes comprehensive tests with synthetic spectrograms, representing realistic CBRS band conditions.

##Dataset
The model is trained and tested using a dataset of approximately 1000 MATLAB-generated spectrograms. These spectrograms simulate a 10 MHz spectrum for 20ms with various signal-to-noise ratios, reflecting conditions near coastal regions with multiple Environmental Sensing Capability (ESC) sensors.

##Performance
Speclearn demonstrates high detection accuracy in low to moderate noise conditions. However, extreme noise significantly challenges radar signal detection, highlighting areas for future improvements in robustness.

##License
This project is licensed under [MIT]. See the LICENSE file for more details.

##Contact
For queries and further collaboration, please contact the authors at debashri.roy@uta.edu, mhr9808@mavs.uta.edu, gaurav.singh4@mavs.uta.edu

