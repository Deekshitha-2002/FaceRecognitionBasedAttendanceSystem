# FaceRecognitionBasedAttendanceSystem
A python GUI integrated attendance system using face recognition to take attendance.

In this python project, I have made an attendance system which takes attendance by using face recognition technique. I have also intergrated it with GUI (Graphical user interface) so it can be easy to use by anyone. GUI for this project is also made on python using tkinter.

TECHNOLOGY USED:

tkinter for whole GUI\
OpenCV for taking images and face recognition (cv2.face.LBPHFaceRecognizer_create() is the recognizer to recognize the images captured)\
CSV, Numpy, Pandas, datetime etc. for other purposes.

FEATURES:

1.Easy to use with interactive GUI support.\
2.Notification box helps the user to understand if each step has been performed correctly or not.\
3.Updates CSV file for details of students.\
4.Creates a new CSV file everyday for attendance and marks attendance with proper ID, name, date and time.\
5.Also displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.

Packages to be installed:
1.opencv-python\
2.numpy\
3.datetime\
4.opencv-contrib-python\
5.Pillow\
6.Pandas\
7.csv

How to Start:

1.In the pycharm project (named "FacialRecognition" in my case) , create directories named TrainingImageLabel, TrainingImage , Attendance , StudentDetails(inside it a  student.csv file with columns "Id" and "Name")\
2.Open main.py\
3. Download the "haarcascade_frontalface_default.xml" file and provide its path.(path is provided if stored in remote location else just provide harcascadePath = "haarcascade_frontalface_default.xml" in TrackImages() function.)\
4.Run main.py\
.Capture images\
5.Train the model\
6.Take attendance\
7.Quit

3 Step process:
1. Image capture(Creating dataset)\
2. Train the model\
3. Take attendance

![2022-06-01 (1)](https://user-images.githubusercontent.com/97438706/171450558-9296ac03-1415-4a1b-8d88-c18724ddb5a9.png)

![2022-06-01 (3)](https://user-images.githubusercontent.com/97438706/171450830-b290d04a-7209-4152-b4ff-413f2e1f54dc.png)

![2022-06-01 (4)](https://user-images.githubusercontent.com/97438706/171450876-28fe4b23-15d4-489b-ad8f-9735d21ed98d.png)

![2022-06-01 (7)](https://user-images.githubusercontent.com/97438706/171450926-465f5922-abef-4445-b627-817fa3a6fcfe.png)

![2022-06-01 (8)](https://user-images.githubusercontent.com/97438706/171450980-6f981776-c1b2-4b98-b98b-6eed20a41d0e.png)

For more information:

https://www.ijrte.org/wp-content/uploads/papers/v9i1/A2927059120.pdf
