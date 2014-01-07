Angular Firebase squeleton
===========================

This repository is a squeleton serving as starting point to develop angular&fierbase apps.

How to use:
===========================

clonning the project git clone https://github.com/dydycloud/angFireBase.git

The files are served off of a basic Node server, so you’ll need node.js: http://howtonode.org/how-to-install-nodejs

 
Next, go to https://www.firebase.com and sign up for an account

 
Go to https://www.firebase.com/account/ and create a Firebase. Remember the name you use for the Firebase, you’ll use it in a second.

At the end of app/js/config.js, change the .constant() line and add in your Firebase URL:

app/js/config.js

  // your Firebase URL goes here
  // should look something like: https://blahblah.firebaseio.com
  .constant('FBURL', 'FIREBASE_URL_GOES_HERE')

Great! You should now be able to boot the skeleton of the application. 

 
Start the server from the app/ directory with node scripts/web-server.js

 
Navigate to 'localhost:8000/app/index.html' to see it in action!
