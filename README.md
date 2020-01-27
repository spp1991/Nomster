# Flixter 

The application is a restaurnt database ,featuring individual pages for each restaurant containing restaurant details (address,photos) and place for a user to share their review on the restaurant. To enable user easily locate the restuarnt, application also has integrated Google Maps as location finder.

Functionalities include:
- Enabling restaurnat owners/users to create/update/delete restaurant pages, uploading photos  for user to visualize the place and geolocation feature of Google Maps to convert address into latitudes and longitudes and locate the restaurant on a Map 
- Allowing visitors to provide reviews on the restaurant
- Profile page for users showing restaurant created/comments posted


Technical details of the app is as follows :
Programming Language: Ruby, javascript, HTML5
Web/stylesheet Framwork : ruby on rails, bootstrap  
Database : postgresql
Gems : carrierwave, fog-aws, devise, geocoder, simple-form , bx-slider, will-paginate
Cloud Storage Platform ; Amazon Web Service (AWS)

Note : Please execute commands to install all gems ('bundle install') and create/migrate database/tables('rails db:create , rails db:migrate') before git repository of this application is downloaded and used to run on local server 

To checkout the application, click [here](https://grammable-sunnypatel.herokuapp.com/) 

## Home Page
<img src="screenshot-home.png" alt="Screenshot Home">

## Course Listing Page (Administrator)
<img src="Screenshot-course-administrator.png" alt="Course Page Administrator">

## Course Page (Student)
<img src="screenshot-course-student.png" alt="Course Page Student">

## Lesson Page (Student)
<img src="screenshot-lesson-page.png" alt="Student Lesson Page">

## Payment Page (Student)
<img src="stripe-payment-page.png" alt="Payment Page">