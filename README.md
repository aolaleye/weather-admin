# Weather Admin Node Application

* Create a command line interface application using Node.js (either with inquirer or process.argv).

* The application should lead the user to one of two pathways: an Admin View or a User View.

* The User View should prompt the user to provide their Name and the Location they'd like weather information for. Upon completion, the User should get the weather in Fahrenheit at that location.

* The Admin View should simply provide a list of every user's search while also including the "date" of each search. See sample below:

```
Name: Ahmed, Location: Atlanta, Date: 10-15-16
Name: Adri, Location: Newark, Date: 10-12-16
Name: Joe, Location: Omaha, Date: 10-10-16
```

---

* In order to complete this activity you will need to make use of:

  * The weather-js npm package.

  * The moment npm package for date formatting.

  * Two constructors: One for "UserSearch" and one for "WeatherAdmin".
