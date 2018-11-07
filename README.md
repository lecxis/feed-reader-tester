
21. Write a README file detailing all steps required to successfully run the application. If you have added additional tests (for Udacious Test Coverage),  provide documentation for what these future features are and what the tests are checking for.
# Feed Reader Tester Project

## Table of Contents

* [Instructions](#instructions)
* [User expectation](#User expectation)
* [App dependencies](#App dependencies)

## Instructions

The feed reader application uses the Google Feed Reader API to grab RSS feeds as JSON object we can make use of. It also uses the Handlebars templating library and jQuery in performing DOM operation used in displaying the feeds to the users. The application uses the Jasmine 2.1.2 library, located in the jasmine folder, in carrying out test. Project folder conatins an index.html file which is run on the browser. It contains css folder where the style.css file is stored and a folder for storing the fonts. The app.js file in the js folder is where the application functionalities is located. The various test suites are written in the feedreader.js file in the spec folder.

## User expectation

The application runs with the internet. It is expected to load feeds which can be clicked in order to access the page. The app also passes the following tests;
menu element is hidden by default.
menu changes visibility when the menu icon is clicked.
when the `loadFeed` function is called there is at least a single `.entry` element within the `.feed` container.
when a new feed is loaded by the `loadFeed` function that the content actually changes

## App dependencies

The app was developed using javascript, html and css. The following libraries were also used- jasmine 2.1.2, Jquery and Handlebars templating. The  Google Feed Reader API waas also used.
