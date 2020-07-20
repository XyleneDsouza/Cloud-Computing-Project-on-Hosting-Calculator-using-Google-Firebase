# Cloud-Computing-Project-on-Hosting-Calculator-using-Google-Firebase

Hosting URL: https://calculator-9eab2.web.app/ 

Calculator is used to calculate arithmetic operations on numbers. It can also handle trigonometric and inverse trigonometric functions, logarithm and natural logarithm, roots, factorial, power and so on. We have round off feature in our calculator which defaults to rounding to the nearest integer. 

Unit converter, Age calculator and LCM GCF calculator is linked to the Calculator. Unit Converter helps to convert units of measurement based on the unit type. For each unit type, there are different units for conversion. 

Age calculator calculates age by date of birth. It provides you accurate results. Our age calculator by date of birth gives you age from DOB to now in years, months, days, hours, minutes, seconds, & milliseconds. 

LCM GCF Calculator calculates lcm and gcf of  two or more numbers. To calculate lcm it uses two or more numbers and calculates the least common multiple, i.e. the smallest positive integer which is divisible by each one of these numbers. GCF of a set of whole numbers is the largest positive integer that divides evenly into all numbers with zero remainder.  
 
Before you can set up Firebase Hosting, you need to create a Firebase project. 
Step 1: Install the Firebase CLI 
Install NodeJS 
Make sure to install NodeJS in your computer. Then, run: 
npm install -g firebase-tools 
Sign in and test the Firebase CLI 
After installing the CLI, you must authenticate. Then you can confirm authentication by listing your Firebase projects. 
Sign into Firebase using your Google account by running the following command: 
firebase login 
This command connects your local machine to Firebase and grants you access to your Firebase projects. 
Step 2: Initialize your project 
To connect your local project to your Firebase project, run the following command from the root of your local project directory: 
firebase init 
During project initialization, from the Firebase CLI prompts: 
Step 3:Select to set up Hosting 
If you want to set up other Firebase products for your project, refer to their documentation for setup information. Note that you can always run firebase init later to set up more Firebase products. 
 
Step 4:Select a Firebase project to connect to your local project directory 
The selected Firebase project is your "default" Firebase project for your local project directory. To connect additional Firebase projects to your local project directory, set up project aliases. 
 
 
7 
 
Step 5:Specify a directory to use as your public root directory 
This directory contains all your publicly served static files, including your index.html file and any other assets that you want to deploy to Firebase Hosting. 
The default for the public root directory is called public. 
You can specify your public root directory now or you can specify it later  
      in your firebase.json configuration file.  
      If you select the default and don't already have a directory called public,  
      Firebase creates it for you. 
       If you don't already have a valid index.html file or 404.html file in your  
      public root directory, Firebase creates them for you. 
Step 6:Choose a configuration for your site 
If you select to make a one-page app, then Firebase automatically adds rewrite configurations for you. 
At the end of initialization, Firebase automatically creates and adds two files to the root of your local app directory: 
A firebase.json configuration file that lists your project configuration.  
      Learn more about this file on the configure hosting behavior page. 
A .firebaserc file that stores your project aliases. 
Step 7:Deploy to your site 
To deploy to your site, run the following command from the root of your local project directory: 
firebase deploy 
This command deploys a release to your Firebase project's default Hosting sites: 
projectID.web.app 
projectID.firebaseapp.com 
