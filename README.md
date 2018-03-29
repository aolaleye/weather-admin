# Weather Admin Node Application

#### __This application leads the user to one of two pathways: an Admin View or a User View.__

* If __User__ is chosen, the application prompts the user to enter his or her name, and a location for which weather information will be retrieved. Upon completion, the user receives the current weather in the specified location.
    * The user's name, location, and the date of search are logged into a separate file.

* If __Admin__ is chosen, the application allows the admistrator to access stored user information. The application prompts the adminstrator to specify the type of information that is requested and outputs the requested information. 
    * __NOTE:__ _When admin is chosen, the application asks for a password. For test purposes, the password is "admin"_.

#### __This application utlizes the following npm packages:__
* _fs (to access information within separate files)_
* _inquirer (to retrieve information from the user)_
* _weather-js (to retrieve weather information)_
* _moment (for date formatting)_

#### __How to initialize the application:__
#### `node weather.js`

