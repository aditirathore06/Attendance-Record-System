# Attendance-Record-System
It is face recognition based attendance record system.
A facial recognition system uses computer generated filters to transform images into numerical expressions that can be compared to determine their similarity.
It is a step by step process :
The first step is to find the faces using HOG(histogram of oriented gradients) method.
Then it finds the encodings for the  face. Their are 128 encodings used to recognise landmarks.
looking at all the faces we have measured in the past, and see which person has the closest measurements to the face shown in camera. That's our match!
And then attendance is marked in an excel sheet for the face matched according to data along with date and time.


#How to run the project
      Clone or download this repository to your local machine.

      Install all the libraries mentioned with the command pip install.

      Open your terminal/command prompt from your project directory and run the file main.py by executing the command python main.py.

#Note

      Please download libraries in latest versions accordingly by opening python file :
          1.numpy
          2.opencv-python
          3.face-recognition
          4.dlib
          5.cmake

      Run it using python 3.10      
