# HAR_Mobile

This is an open dataset for human activity recognition (HAR) obtained from a mobile device and tagged manually. It contains four activities carried out by four subjects. Specifications of the dataset are the following:

Activities and time duration (each subject performed each activity three times):
1. Jumping   -- 2 minutes per subject
2. Walking   -- 5 minutes per subject
3. Laying-on -- 5 minutes per subject
4. Running   -- 5 minutes per subject

Sensors (built-in of the mobile device) involved in the measurements:
1. Accelerometer        -- X,Y,Z axes
2. Gyroscope            -- X,Y,Z axes
3. Magnetic Field       -- X,Y,Z axes
4. Linear Accelerometer -- X,Y,Z axes

Columns in a sample:
- (1) Timestamp
- (2-4) Accelerometer X, Y and Z
- (5-7) Gyroscope X, Y and Z
- (8-10) Magnetic Field X, Y and Z
- (11-13) Linear Accelerometer X, Y and Z

Profile of the subjects (age/gender/height/weight):
1. 22 /  male  / 1.85m / 75kg
2. 28 / female / 1.57m / 49kg
3. 55 /  male  / 1.75m / 75kg
4. 29 / female / 1.68m / 54kg

Technical specifications of the mobile device:
- Model:                            Huawei NXT-L09
- Processor:                        HiSilicon Kirin 950
- Memory:                           32GB internal with 3GB RAM
- Battery:                          Li-Po 400mAh
- Application for data acquisition: Sensorstream IMU+GPS V1.0
- Sampling Frequency:               5Hz
- Storage Media:                    internal memory

Settings of activity performance:
1. All activities were perfoemd in a plain terrain with dimension 7 x 5 meters-squared
2. The mobile device was located at the left pocket of the subjects' pants in vertical position
3. This dataset has missing values

Files are named as SXA_Activity.csv:
- X - represents the number of subject
- A - represents the number of attempt
- Activity - refers to the activity performed
 
Example: S32_Jumping.csv refers to the Jumping activity carried out by subject number 3, and this file represents the second attempt
 
If you want to use this dataset or need more details about it, please refer and cite the following article:
1. Ponce, H., González, G., Miralles-Pechuán, L., Martínez-Villaseñor, M.L., Human Activity Recognition on Mobile Devices Using Artificial Hydrocarbon Networks, Mexican International Conference on Artificial Intelligence (MICAI 2017), Lecture Notes in Computer Science, in press.

