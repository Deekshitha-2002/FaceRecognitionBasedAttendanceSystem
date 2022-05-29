# FaceRecognitionBasedAttendanceSystem
A python GUI integrated attendance system using face recognition to take attendance.

In this python project, I have made an attendance system which takes attendance by using face recognition technique. I have also intergrated it with GUI (Graphical user interface) so it can be easy to use by anyone. GUI for this project is also made on python using tkinter.

TECHNOLOGY USED:

tkinter for whole GUI
OpenCV for taking images and face recognition (cv2.face.LBPHFaceRecognizer_create() is the recognizer to recognize the images captured)
CSV, Numpy, Pandas, datetime etc. for other purposes.

FEATURES:

Easy to use with interactive GUI support.
Notification box helps the user to understand if each step has been performed correctly or not.
Updates CSV file for details of students.
Creates a new CSV file everyday for attendance and marks attendance with proper ID, name, date and time.
Also displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.

Packages to be installed:
1.opencv-python
2.numpy
3.datetime
4.opencv-contrib-python
5.Pillow
6.Pandas
7.csv

How to Start:

1.In the pycharm project (named "FacialRecognition" in my case) , create directories named TrainingImageLabel, TrainingImage , Attendance , StudentDetails(inside it a  student.csv file with columns "Id" and "Name")
2.Run main.py
3.Capture images
4.Train the model
5.Take attendance
6.Quit

For more information:

https://www.ijrte.org/wp-content/uploads/papers/v9i1/A2927059120.pdf
