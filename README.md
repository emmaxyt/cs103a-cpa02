# CS103a CPA02

## What's this app? 
This app is built on the structure of CS103a course evlaution app. It allows users to anonymously evaluate the courses they've taken. Users can rate the course in a scale from 0 to 5, and type in comment to elaborate their experience. The app displays a list of courses that've been evaluated with an average rating and all the collected comments. This app is created to help students select their future courses based on the feedback from others. 

This app provides access to a mongoose database in the cloud.

## Installation
Download the project from github and download nodejs and npm from https://nodejs.org
and cd into the folder

Install the packages with
``` bash
npm install
```
Start the project with
``` bash
node app.js
```
or install nodemon (the node monitoring app) with
``` bash
npm install -g nodemon
```
and start the project with
``` bash
nodemon
```

## How to use this app once installed? 
-Go to http://localhost:5000
-Click on the "Course Evaluation" tab
-Enter the information about the course that you want to evluate and submit!
-You will be directed to a list of courses that've evaluated
-Click on the hyperlink embedded in the "course #" to read all the comments for this course
