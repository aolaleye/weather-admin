# Weather Admin Node Application

* The application leads the user to one of two pathways: an Admin View or a User View.
* The User View prompts the user to provide their Name and the Location they'd like weather information for. Upon completion, the User receives the weather in Fahrenheit the specified locations
    * The user's name, location, and the date of search are logged into a separate file.
* The Admin View allows an admistrator to access stored user information. The application prompts the adminstrator to specify the type of information that is requested. 
* __NOTE__: _When admin is chosen, the application asks for a password. For test purposes, the password is "admin"_.

This application utlizes the following npm packages:
  * weather-js (to retrieve weather information)
  * moment (for date formatting)
  * inquirer (to retrieve information from the user)

How to initialize the application:
## `node weather.js`

