# Face_Recognition

## 1. Face Recognition using the face_recognition.py module
A face recognizer has been built using the face_recognition.py module. 
- There are two ways in which the images can be stored into the database, one through an existing image of the person from anywhere on the system and the other using the webcam implementation wherein the person registers himself using the webcam. 
- The face images are stored into a directory named face_images
- The images are then encoded using the face_recognition.face_encodings function and both the name and the encodings are stored into seperate dictionaries.
- These encodings are then used to identify any person who tries to get authenticated from the webcam.
- If identified, the face is marked by a rectangle around it with the corresponding name.

This model runs with an average accuracy of over 97% and hence is very efficient and reliable.

## 2. Face Recognition using Facenet and mtcnn
Work in progress...
