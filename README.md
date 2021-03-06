# SPACEBOOK
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

🚀[Deployed on Heroku: https://spacebook-mars.herokuapp.com/](https://spacebook-mars.herokuapp.com/)

## Description:  
 The year is 2099. Humans now live in a colony on Mars. They need an app to help them plan their day. 
 
SPACEBOOK allows Martians to see the current weather for their colony location, check on photos from the nearby rover, and manage a task list. 

For future development: Martians will be able to connect with other Martians to share tasks, alert to weather conditions, and save Rover photographs. 

## Table of Contents:
* [Developers](#developers)
* [Installing Locally](#installing-locally)
* [Quick Start](#quick-start)
* [Usage](./USAGE.md)
* [ScreenShots](#screenshots)
* [Tests](./TESTS.md)
* [License](#license)

# Developers
These Earthlings enjoy imagining life as Martians. Please feel free to reach out with questions or comments. 

### Lisbeth Machado
* :octocat: [GitHub](https://github.com/lisbethmachado)
* 📧 E-mail: lizmachado.xo@gmail.com

### Timothy Lam
* :octocat: [GitHub](https://github.com/tlam1288)
*  📧 E-mail: tlam1288@gmail.com

### Jessica Blankemeier
* :octocat: [GitHub](https://github.com/jessicablank)
*  📧 E-mail: jessicablankemeier@gmail.com

# Installing Locally

Add a .env file at the top level of this project.

Then inside of the .env add a SERVER_SECRET set to any value you'd like

```
SERVER_SECRET = 123456
```

First off make sure you have a local version of MongoDB running on your machine. This project will make a local database for you called `appDB`.

```
mongod
```

Start by installing front and backend dependencies. While in the root directory, run the following command:

```
npm install
```

After all installations complete, run the following command in your terminal:

```
npm start
```

That's it, your app should be running on <http://localhost:3000>. The Express server should intercept any AJAX requests from the client.

# Quick Start
These Martians are already registered with populated task lists if the User would like to test the application without creating a new Martian. 

* Test User 1

    * Martian Name: Mr. Martian XLF-12
    * Email: Mars.Rocks@email.com
    * Password: p@ssw0Rd

* Test User 2

    * Martian Name: Ms. Martian XLF-15
    * Email: Martians.Rocks@email.com
    * Password: p@ssw0Rd

# Screenshots

Web Application Views Signup Page:

![WebSignup](./assets/spacebook-web-signup.png)

Web Application Views Login Page:

![WebLogin](./assets/spacebook-web-login.png)

Home Page:

![PhoneHome](./assets/sapcebook-phone-home.png)

Home Banner:

![TabletBanner](./assets/spacebook-banner-home.png)

Home Weather:

![HomeWeather](./assets/spacebook-weather-home.png)

Weather Info:

![WeatherInfo](./assets/spacebook-weather-modal.png)

Weather Page:

![PhoneWeather](./assets/spacebook-phone-weatherfull.png)

Home Task:

![HomeTask](./assets/spacebook-task-home.png)

Task Page:

![PhoneTask](./assets/spacebook-phone-taskfull.png)

Task Info:

![TaskInfo](./assets/spacebook-task-modal.png)

Rover Page:

![PhoneRover](./assets/spacebook-phone-rover.png)

Rover Info:

![RoverInfo](./assets/spacebook-rover-modal.png)

Inavlid Signup:

![InvalidSignup](./assets/spacebook-invalid-signup.png)

Invalid Login:

![InvalidLogin](./assets/spacebook-invalid-login.png)

No Match Page:

![NoMatch](./assets/no-match.PNG)

## License
Copyright 2020 - present Lisbeth Machado, Timothy Lam, Jessica Blankemeier.
This project is licensed under the terms of the MIT license. 
More information is available at [opensource.org/licenses](https://opensource.org/licenses/MIT)
