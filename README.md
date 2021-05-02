# Face Recognition and Automated Attendance Marking

The program extracts frames from live camera and then detects human faces from them, human faces are deteted from this current frame and compared with encoded known faces already in the system. Then the corresponding label is set besides the face on screen, simultaneously a .csv file is updated with the name, date and time of the enrollment and hence kept as the database for this project

Python libraries used: OpenCV, numpy, face-recognition, datetime, os
