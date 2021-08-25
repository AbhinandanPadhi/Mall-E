# Mall-E

## What is Mall-E?
Mall-E is a mobile app (iOS and Android) created using React Native that allows users to monitor the crowd density of various malls around Singapore as well as check approximate waiting times for restaurants in Singapore's malls. This app relies on data from various APIs, including Google Places API, BestTime API, and more, to obtain up-to-date crowd density and waiting times information.


## Instructions for running the Mall-E app (on a virtual Android device)
Run "npm i" both from root directory and then from MallE directory to install all the node modules.

To run the project on an Android Virtual Device or on real debugging device:
IF YOU ARE USING REACT CLI:

1. Uncomment this line "org.gradle.java.home=C:\\Program Files\\Java\\jdk-11.0.8" in gradle.properties file in MallE/Android folder
2. Go to Code/MallE dirctory and run "npx react-native run-android"

link for vector icons
https://oblador.github.io/react-native-vector-icons/

To start python server for popular times:
1. change the ipAddress in the cofig.json file to your ip address
2. Go to python_server folder 
3. pip install flask
4. pip install flask_cors
5. Type 'python api.py'

To start server for login/register:
1. change the ipAddress in the cofig.json file to your ip address
2. Go to server folder 
3. Type 'npm i'
4. Type 'npm start'

Test credentials for login:
Email: test123@test.com
Password: test123
