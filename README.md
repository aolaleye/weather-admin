# Weather Admin Node Application

#### __How to initialize the application:__
* #### `node weather.js`

#### __This application leads the user to one of two pathways: an Admin View or a User View.__

* If __User__ is chosen, the application prompts the user to enter his or her name and a location. Upon completion, the application outputs the current weather in the specified location in the user's terminal/bash window.
    * The user's name, location, and the date of search are logged into a separate file.

* If __Admin__ is chosen, the application allows the admistrator to access stored user information. The application prompts the adminstrator to specify the type of information that is requested and outputs the requested information in the admin's terminal/bash window. 
    * __NOTE:__ When admin is chosen, the application asks for a password. For test purposes, the password is "admin".

#### __This application utlizes the following npm packages:__
* __fs__ _(to access information within separate files)_
* __inquirer__ _(to retrieve information from the user)_
* __weather-js__ _(to retrieve weather information)_
* __moment__ _(for date formatting)_

__Note:__ _run `npm i` to install the packages included in the json package_


