README
•	For our program to run you need to have OpenCV , Python 3.6,  Anaconda installed in your systems. In addition, you need to have tkinter, cv2, pickle, argparse, numpy, os  and face_recognition libraries installed.
•	As we are using our mobile camera to connect the camera to the system you need an android application called IP Webcam installed in your mobile.
•	To connect the mobile and the system, both should be connected to the internet through the same wifi access. When we will open the IP Webcam application in our mobile phone, there will be a URL displayed on the screen. When we run that URL on our system, the camera will get connected to the system and the image displayed on the camera could now be seen on our laptop screen.
•	Our program has a folder called dataset, inside which there are separate folders for every person in the dataset. They form our training images. The folder called examples has multiple our images which form our test image dataset and the file gui.py is our code file.
•	When we will run the code, our GUI screen will be displayed. It is having four buttons.
•	The first option Take Input is used to register a new student to our system and their database is created using our mobile and the system.
•	The second option Train images, is for training the system on the training dataset. Every time a new student gets registered we need to train our system
•	The third option Take attendance , is to capture a real time image of the classroom.
•	The fourth option Quit is to run the face recognition code. After this code runs, a final image will be displayed with the recognized faces and attendance of the students will be marked in the Excel sheet.
