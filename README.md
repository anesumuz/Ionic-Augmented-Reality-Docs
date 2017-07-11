# Ionic-Augmented-Reality-Docs
Documentation for Ionic Augmented Reality Starter App

Thanks for purchasing Ionic Augmented Reality Starter App. Now that you have the project, lets get you set up!

## Installation

To install and run the application in a development environment, you will need 3 things installed;
- Node.js
- Ionic Framework
- Cordova
 
You can skip this step if you already have these installed. If you don't, ets walk through that process below!

### Step 1 : Install Node.js
To install Node.js head over to <a href="https://nodejs.org">nodejs.org</a> and download the version for your operating system. Take care to download a version market `LTS` as these will have the best support and stability. Node  will provide a package manager called `npm` that will help us install the other dependencies. Once you run the installer, open your terminal and type in


You should see a version number return after that command.For example, on my system I have version `6.9.5` and it returned the below. Note that we will requrire you install node version 6 and above.

Now that we have Node setup, lets move on to Ionic Framework and Cordova.


    $ v6.5.0
    
  ### Step 2 : Install Ionic and Cordova  
  
  As stated earlier, Node will come bundled with a package manager called `npm`. We'll use `npm` to install the Ionic Framework and Cordova. The two can be installed by a single command in the terminal.
                
      $ npm install -g ionic cordova

This will download and install ionic and cordova. It may take a few minutes. Once this is done, check they have
succesfully installe by running. It should return a version as below,(may show higher version than shown below).

    $ ionic -v
    > 2.2.1
    
### Step 3 : Run The App!!

Now we run the application. In your terminal, navigate to the root of the `augmented-ionic/` folder
			
    $ cd <path to the folder here>/augmented-ionic/
    
Once in the root folder, run the command;

    $ ionic serve
    
You should see log output similar to the below;

    Watching: www/**/*, !www/lib/**/*
     > ionic-hello-world@ ionic:serve /home/fitzmode/projects/firebase-ionDevJobs2
    > ionic-app-scripts serve "--v2" "--address" "0.0.0.0" "--port" "8100" "--livereload-port" "35729"

    [23:07:58]  ionic-app-scripts 1.1.0 
    [23:07:58]  watch started ... 
    [23:07:58]  build dev started ... 
    [23:07:58]  clean started ... 
    [23:07:58]  clean finished in 64 ms 
    [23:07:58]  copy started ... 
    [23:07:58]  transpile started ... 
    [23:08:29]  transpile finished in 30.71 s 
    [23:08:29]  preprocess started ... 
    [23:08:29]  preprocess finished in 3 ms 
    [23:08:29]  webpack started ... 
    [23:08:31]  copy finished in 33.12 s 
    [23:09:29]  webpack finished in 60.40 s 
    [23:09:29]  sass started ... 
    [23:09:42]  sass finished in 12.70 s 
    [23:09:42]  postprocess started ... 
    [23:09:42]  postprocess finished in 5 ms 
    [23:09:42]  lint started ... 
    [23:09:42]  build dev finished in 104.42 s 
    [23:09:43]  watch ready in 104.83 s 
    [23:09:43]  dev server running: http://localhost:8100/ 
    
What this does is to start a server at port 8100 on localhost of your machine by default. Navigate to `localhost:8100` in your browser to see the application running.

### Important!! You will need to resize your browser so you can view the app as it would appear on the actual mobile device.


Below I have simply opened the developer tools in Google Chrome by pressing F12 and resizing the Developer Tools to shrink app viewport. This will also double as a debugging mode to play around with your app in development.

## Directory Structure

The app is based on the default Ionic 2 and 3 directory structure. The app utilizes only one page component.

You will find the apps source under `augmented-ionic/src` directory. In this directory i where all your edits or modifications will go.




