# Live Location Tracker

This is a mobile application to share your realtime location with GPS tracking and stay connected with your friends, families and co-workers.
The application is built using Flutter with Firebase and Firestore to handle the authentication of users and data management.

The pre-compiled .apk file for the app can be downloaded [here](https://github.com/pallavpp/material-hosting/raw/main/Location_Tracking_App_ReadMe_Material/APK%20File).


## Using the APK
- Download the APK and open it in your mobile.
- Give necessary permissions.
- Install and start using the application.


## Features
  
  - Live Location Sharing between members of a group using Location Markers on Google Maps.
  
    <img src="https://github.com/pallavpp/material-hosting/blob/main/Location_Tracking_App_ReadMe_Material/Screenshot%202021-07-26%20235949.png" width="192" height="400">
  
  - Form multiple groups with your friends or family easily and share your location with each other.
  
    <img src="https://github.com/pallavpp/material-hosting/blob/main/Location_Tracking_App_ReadMe_Material/Screenshot_20210726-234417.png" width="192" height="400">
    
  - Users can login either by creating an account or sign-in using their Google accounts as well.

    <img src="https://github.com/pallavpp/material-hosting/blob/main/Location_Tracking_App_ReadMe_Material/Screenshot_20210726-234050.png" width="192" height="400">
    
  - Users have an option to edit their name and profile picture after creating an account.
 
    <img src="https://github.com/pallavpp/material-hosting/blob/main/Location_Tracking_App_ReadMe_Material/Screenshot_20210726-234539.png" width="192" height="400">


## How the Location Sharing Works?
- The device gets its continous location updates from GPS using the Google Maps API.
- Location data for the user is updated in their respective firestore documents, and subsequently in the group documents.
- Other devices sharing goups with the first user read that firebase firestore document and show the marker in the stored location.


## Contributors
  This app has been designed and developed by
  - [Pallav Pandey](https://github.com/pallavpp)
  - [Anurag Singhal](https://github.com/Anu8690)
  - [Aryan Rathee](https://github.com/aryanrathee)
