# Smart-Attendance-System-using-Face-Recognition
Smart Attendance using Face Recognition is a real-world solution to handling the activities about student attendance. Face Recognition is a process of recognizing the students face for taking attendance by using face biometrics. The objective of this project is to process the live video stream of students sitting in the classroom and generating the attendance list. 
The Files in the directory are :
attendance.py : This is the main script of the project. It implements the GUI of the project and calls functions from the modules package developed.
# Getting Started
# Prerequisites
Download the project from the Attendance_Project.txt file. You need to install the XAMPP server in order to run the project. XAMPP is one of the widely used cross-platform web servers, which helps developers to create and test their programs on a local webserver. The system might require Python installed along with OpenCV libraries. Install Numpy, Python Face Recognition module, Python time Module, PyMySQL module, glob module in python.

# Steps to run the Project

First of all, you might need to store photos of the people whose faces need to be recognised. Store the photos in htdocs folder along with the name of the person whose phto has been stored.

After installing the XAMPP server, start the server. It might look somewhat like this.

![image](https://user-images.githubusercontent.com/87305411/171987207-1dc682e6-b7d5-4b89-b3b6-25adb84f671b.png)


You need to start the Apache, MySQL, FileZilla servers to run this project. If the servers give an error while running, make sure you uninstall any existing MySQL, Apache, FileZilla Programs you have installed on your PC.

![image](https://user-images.githubusercontent.com/87305411/171987323-fe69a54a-c478-4d69-8298-cc8c6c63cdd6.png)

This is done inorder to run our project on localhost.

After this, run the attendance.py file stored in the htdocs folder using IDLE (Integrated Development and Learning Environment). The Python installer for Windows contains the IDLE module by default.

![image](https://user-images.githubusercontent.com/87305411/171987668-6adff6de-ba07-4ef0-8fbb-564c8c946ed3.png)

Run the attendance.py file. 

![image](https://user-images.githubusercontent.com/87305411/171987781-5b77dbc8-da6a-4390-99d0-3875e4aabf16.png)

Enter the subject name for which the attendance needs to be taken and press enter. After this, the webcam might start live video-streaming and start recognising the faces of the people whose images have been stored in the htdocs folder. To end the video stream, press Q.

To check whether the attendance has been marked or not, open your browser and then type this : 
http://localhost/attendance/admin/index.php

![image](https://user-images.githubusercontent.com/87305411/171987987-540d2104-7453-46e2-9238-0136f66cb50c.png)

The Username and Password by default is admin. After you sign in, you might be able to view the attendance marked.

![image](https://user-images.githubusercontent.com/87305411/171988032-0383427a-72ae-4ac1-819b-115b5a135776.png)

If you want to make some changes in the attendance record, use this link : 
http://localhost/phpmyadmin/index.php

# Built with
1) Python
2) OpenCV - Implementation of Algorithm
3) Numpy - Used to manage computations

# Authors
Shikhar Bakshi
