# Body-Face-recognition-
The goal of the project is to detct various actions performed by a person while sitting infront of a system. It also identifies whethere the person is authorized or not.
This project is focused on Single person detection. The actions that this project can detect are as follow:

1. Detect the Head bent along with the angle(in degree).
2. Detect if the person is turend Left or Right
3. Detect is the person is doing any kind of stretch with his/her hands or head.
4. Detect the person leaning towards to the system or away from the system.
5. Recognize the person sitting infornt of the system.


The project uses Openpose to detect the person joint coordinates. The coordinates are then used to calculate angles between various joints. The first 3 points used joint 
coordinates to detect various activities performed.
The forth and fifth points uses DLIB Face ai to detect and recognize the face and then to detect if the user is leaning forward or backward from the position of origin.


To Run the "Body-Face-recognition"
 run "main.py"
 
To train the model to recognize new face.
 1. create a directory with the person's name in the dataset folder.
 2. Add few images in that person's directory
 3. Make sure that the path to the ".pickle" file in "train_faces.py" is set to "current_directory/model/file.pickle"
 3. run "train_faces"
 
 
