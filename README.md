**PROJECT: SeanWeather**

**PROJECT DESCRIPTION**

This is a weather site where one can input the name of a city and get back the current weather conditions including:

* What the sky looks like currently.
* Current room temperature.
* Current humidity.
* Current Wind speed.

**INSTALLATION**

As this is a hosted website it requires no further installation or configuration.

You can visit the site at: `https://seansama.github.io/SeanWeather/`

**CORE DELIVERABLES**

The main objectives of this project were:

1. [x] That a user could search for a city of choice and get a response.
2. [x] That in case a city is not found it would return 'No weather found'
3. [x] That a user can get current temperature as an output.
4. [x] That a user can get current Wind speed and humidity as an output.
5. [x] That a user can get sky conditions as an output.
6. [x] That all the data above would come from a public API
7. [x] That the main page would link to two other pages with forms on them.

**THE PAGES HEREIN**

**Main page**

This page contains the main features of the app that include all the functionality described in the project description and core deliverables.

**Javascript functionalities that made this all possible:**

* `fetch()` - this was used to get the data needed from: `https://api.openweathermap.org/data/2.5/weather?q=" +
   city +
   "&units=metric&appid=`.
* `DOMContentLoaded` event - event fires when the HTML document has been completely parsed.
* `keyup` event - this event fires when the search key is released completing the weather search.
* `click` event - this event fires when the search key is clicked initiating a data query.

**Login page**

This page contains a set of fields namely:

* Email/Phone number
* Password

This form is validated and will return error messages if:

* The email entered is less than nine characters.
* The password entered is less than six characters

_* Unfortunately this feature does not work correctly at present as the browser throws a 405 error upon trying to redirect to the main page. The user will have to use the back button on the browser to return to the main page. Corrections will be made once knowledge base increases._

**Contact Us Form**

The fields in this form are:

* Username
* Subject
* Email Address
* Message

_*This form is built in only CSS and HTML due to time constraints and thus doesn't have any functionality. For this one a user will also need to return to the main page manually._

**FILE CONFIGURATION**

The files in this project are structured as follows:

**Root Folder**

* Authentication.html - this houses the Log-in form.
* ContactUs.html - this houses the Contact-us form
* index.html - this houses the main application form.
* DOCS.text - This contains the project documentation and the project links.
* README.md - This contains details about the project and its files.
* LICENCE - This contains an open source MIT licence.

**SRC**

* app.js - Functionality for MVP and main app.
* styles.css - Styling for the main application.

**ContactUs**

* ContactUs.js - Currently void(Should hold form validation for ContactUs form).
* ContactUs.css - Styling for Contact-us form.

**Authentication**

* Authy.css - Styling for the Log-in page.
* Authy.js - Form validation functionality for the Log-in form.

**Assets**

* Contains the logo as used in the project header.

**This project has been done by:**

_Shaun Mwangi_

_**This project is open source under an MIT open source licence.**_
_Copyright (c) 2022 Seansama_









