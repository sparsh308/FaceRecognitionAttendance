<h1 align="center">Attendance Management Sytem Using Face Recognition</h1>

#### ABOUT

This repository contains code for facial recognition using openCV and python with a tkinter gui interface. If you want to test the code then run main.py file

Technology used : -openCV (Opensource Computer Vision) -Python -tkinter GUI interface

Here I am working on Face recognition based Attendance Management System by using OpenCV(Python). One can mark thier attendance by simply facing the camera.

#### How it works :

When we run main.py a window is opened and ask for Enter Id and Enter Name. After enter name and id then we have to click Take Images button. By clicking Take Images camera of running computer is opened and it start taking image sample of person.This Id and Name is stored in folder StudentDetails and file name is StudentDetails.csv. It takes random images as sample and store them in folder TrainingImage (which will be automatically created).After completion it notify that iamges saved. After taking image sample we have to click Train Image button.Now it take few seconds to train machine for the images that are taken by clicking Take Image button and creates a Trainner.yml file and store in TrainingImageLabel folder. Now all initial setups are done. By clicking Track Image button camera of running machine is opened again. If face is recognised by system then Id and Name of person is shown on Image. Press Q(or q) for quit this window.After quitting it attendance of person will be stored in Attendance folder as csv file with name, id, date and time and it is also available in window.

#### Key Points

LANGUAGE USED- python
TECHNOLOGIES/TOOLS USED-
• Python
• OpenCV
• PyCharm
• Tkinter for Gui
• Pandas Library
• PIL Library

Algorithm Used

Local Binary Pattern Histogram(LBPH) 
It is a simple yet very efficient texture operator which labels the pixels of an
image by thresholding the neighborhood of each pixel and considers the result as a binary number.


#### Refrence Links

https://www.pyimagesearch.com/2018/07/19/opencv-tutorial-a-guide-to-learn-opencv
https://towardsdatascience.com/face-recognition-how-lbph-works-90ec258c3d6b
https://docs.python.org/3/

https://medium.com/dataseries/face-recognition-with-opencv-haar-cascade-a289b6ff042a

#### Future Scope

	•This application can be further enhanced by using higher resolution cameras
	•Re-calibrating the algorithms or choose better algorithms.
	•For more convenience, this application can be converted into an android application to work with smartphone cameras to generate attendance without need for extra equipment required in an IOT system.
	•Application can be made more secure and scalable.

#### This is how my Front-End UI looks
<img src="https://github.com/akashmittal18/FaceRecognitionAttendance/blob/master/FaceAttendace.png">