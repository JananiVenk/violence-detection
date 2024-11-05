# violence-detection

#### DATA:

###### The dataset contains 500 violence and 500 non-violence videos.

#### DATA PREPARATION:

###### The data is preprocessed and 4 different types of data are obtained - original data,pose data,change detection data and fusion data
###### The original data is data which contains 20 video frames for each video.
###### The pose data is applying human pose estimation(spatial information) on original data - done with yolov8-pose
###### The change detection data is applying optical flow applied on consecutive frames on original data.
###### The fusion data is application of combination of pose and optical flow features on original data capturing spatio-temporal features.

#### MODEL TRAINING:

###### Model is trained using four types of data.
###### Fusion data has the highest accuracy of 93%.

#### VIOLENCE DETECTION IN REAL TIME WITH IOT:

###### Trained model is integerated in real time along with IOT system.
###### When model detects violence, the alarm is triggered with help of Pyfirmata package, alerting the security personnel.
