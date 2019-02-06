# pwa-polymer-starter
PWA Polymer starter kit examples on firebase.

You can see both examples code working on these links:

https://pwa-polymer-starter.firebaseapp.com/

https://pwa-polymer-shop.firebaseapp.com/


## PWA Polymer Starter Kit - Official Documentation
[https://pwa-starter-kit.polymer-project.org/setup](https://pwa-starter-kit.polymer-project.org/setup)

## Steps to run locally
1. Clone this repo on your pc: 

   ```git clone https://github.com/gabrielruiz/pwa-polymer-starter```
   
2. You need to have installed NodeJS, otherwise you can download and install here: [https://nodejs.org/en/download/](https://nodejs.org/en/download/)

2. Go to the app’s root directory (/pwa-app or /pwa-shop) and run this command:

    ```npm install```
3. After that, you can run the application with this command (this will run on http://localhost:8081):

   ```npm start```
   
   If you need to run the application in a different hostname or port use this command:
   
   ```npm start -- --hostname 0.0.0.0 --port 4444```

4. To run the application’s unit and integration tests use this commnad:

   ```npm run test```

5. To run just the unit or integration tests:

   ```npm run test:unit``` or ```npm run test:integration```
   
5. To build your application for production (see the [Building and deploying](https://pwa-starter-kit.polymer-project.org/building-and-deploying) section for more details):

   ```npm run build```
   
## Building and Deploying in Firebase

1. First, needs to have installed firebase-tools:

   ```npm install -g firebase-tools```
   
2. [Sign up for a Firebase account](https://www.firebase.com/signup/) if you don’t have one. Then go to [Firebase Console](https://www.firebase.com/) to create a new project. Make note of the project ID associated with your project.
   
4. Login to the Firebase and set the previously created project as the active Firebase project for your working directory:

   ```firebase login```
   
   ```firebase use <project_ID>```
   
5. To deploy your project:

   ```firebase deploy```
   
NOTE: If you will not use firebase you can remove firebase.json on your files.
