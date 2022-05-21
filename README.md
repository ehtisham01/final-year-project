# final-year-project_181021-181129
Real-time fire detection system based on AI. YOLOv5 has been used at the back-end for detection purposes. 
The model was trained on hand-picked dataset images from Kaggle, Github, and Google.
The total dataset contains more than 500 images. Application has been developed in the .NET framework using Visual Studio.
YOLOv5 trained model was used with the help of the .onnx format for integration with the application. 
AI model yolov5 is trained and tested on colab
The application displays a camera feed via a mobile phone for now and the model works on the input source frame by frame and generates an alert in terms of email of registered user in case of fire or smoke happening.


Steps you must folow to run this project.


step_1: 
Donwload packages from nuget package manager in visual studio
Go to tools and click on Nuget Package Manager, and then click Package Manager Console, where you can see restore button and click on restore button to add packages.

step-2:
Update connection string in order to connect to database.
