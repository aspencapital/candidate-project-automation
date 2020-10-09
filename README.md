## Introduction
Welcome to Aspen Capital's Test Automation Engineer challenge. This assignment will help us better assess your technical and design skills. We recommend that you focus on the requirements listed below, and if time permitting, work on any additional features of your own choosing. These additional features can be enhancements to the basic framework, setup to run in a CI/CD pipeline, etc.

## Background

This application displays the 5 day weather forecast for a given location.

* Enter city name, get 5 day weather forecast
* Select day, get 3 hour forecast
* Select day again, hide 3 hour forecast
* Daily forecast should summarise the 3 hour data:
	* Most dominant (or current) condition
	* Most dominant (or current) wind speed and direction
	* Aggregate rainfall
	* Minimum and maximum temperatures


## Requirements

* All values should be rounded down

* We would like the application to be tested against the requirements above. But that is only a starting place. Add any funtional or non-functional tests you see as approprite. Feel free to include mindmaps, decision tables, or other tools you use to design the tests. You can add BDD tests (Gherkin) or any other types you think appriate.

* You can use the language and test framework of your choice.

* Make sure that your test scenarios and code are clear, demonstrate good practices, and that you include a README file explaining how to build and run your solution.


### Technical

The application is running in "test" mode, using a set of test data, matching that which comes from the public API at OpenWeatherMap (http://openweathermap.org/forecast5). 
There is test data for a number of locations, found in the folder src/data.

You should find that every important part of the HTML produced has been marked with data-test attributes.

To run the app locally:

You'll need node and npm installed - first off, install the required dependencies:

$ npm install

To start up the application:

$ npm run develop


## Submission
* Your submission should be accessible in a public git repository that includes a README.md with all the pertinent information of how to run your application. 
The expectation is that we can easily follow the steps provided and run the application without any guesswork.
* If your submission does include additional artifacts that are not represented within the repository - the README should provide information on how to retrieve and access these items.

* Details on anything further that you would like to achieve given more time, including any trade-offs that you may have made

Good luck and thank you for your time - we look forward to seeing your submission.
