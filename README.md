# Nomstar

The application is a sample app for creating restaurants details in a city ,featuring individual pages for each restaurant containing restaurant details (address,photos) and place for a user to share their review on the restaurant. To enable user easily locate the restaurant, application also has integrated Google Maps as location finder.

Functionalities include:
- Enabling restaurant owners/users to create/update/delete restaurant pages, uploading photos  for user to visualize the place and geolocation feature of Google Maps to convert address into latitudes and longitudes and locate the restaurant on a Map 
- Allowing visitors to provide reviews on the restaurant
- Profile page for users showing restaurant created/comments posted
- Alerting creator of restaurant profile through email about the comments being posted on the restaurant

## [Try it yourself](https://nomster-sunny-patel.herokuapp.com/) 


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You will need to setup Vagrant environment to run the application on local machine. To find the installation instructions for your OS, visit :

```
https://github.com/FirehoseProject/firehose-vagrant-rails5
```
### Installing

Initiate the vagrant environment.

Git clone the repository to your local machine in the src folder :

HTTPS:
```
$ git clone https://github.com/spp1991/Nomster.git
```

SSH:

```
$ git clone git@github.com:spp1991/Nomster.git
```

Open application folder created by git clone command:

```
$ cd Nomster
```

Install all the gems used in application:

```
$ bundle install
```

Install the application database and create all the tables:

```
$ rails db:create
$ rails db:migrate
```

You will then be able to start the app locally by runnning:

```
$ rails server -b 0.0.0.0 -p 3000
```

## Built With

* [Ruby on Rails](https://rubyonrails.org/) - Web framework
* [PostgreSQL](https://www.postgresql.org/) - Database
* [HTML5](https://en.wikipedia.org/wiki/HTML5) - Web markup language
* [CSS3](http://www.css3.info/) - Webpage Style Sheet language
* [Bootstrap](https://getbootstrap.com/) - CSS Framework
* [Javascript](https://www.javascript.com/) - Web Programming language
* [jQuery](https://jquery.com/) - Javascript Framework
* [Amazon Web Service](https://aws.amazon.com/) - Cloud Storage Platform
* [Carrierwave](https://github.com/carrierwaveuploader/carrierwave), [Fog-aws](https://github.com/fog/fog-aws), [devise](https://github.com/heartcombo/devise), [Geo Coder](https://github.com/alexreisner/geocoder), [Simple Form](https://github.com/heartcombo/simple_form), [bx-Slider](https://github.com/manfe/bxslider-rails), [will paginate](https://github.com/mislav/will_paginate) - Ruby gems



## Home Page
<img src="Screenshot home.PNG" alt="Screenshot Home">

## Restaurant Page 
<img src="screenshot restaurant page 1.PNG" alt="Restaurant">
<img src="screenshot restaurant page 2.png" alt="Restaurant">
<img src="screenshot restaurant page 3.png" alt="Restaurant">

## User Profile 
<img src="screenshot user profile.PNG" alt="User Profile">
