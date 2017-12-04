# Project Overview

This project is a web-based application that reads RSS feeds. The project was provided as part of Udacity 'Test Driven Development' assignment. I have added [Jasmine](http://jasmine.github.io/) based test suites to test the following functionality 

### RSS Feeds Test Suite
1. Make sure that the allFeeds variable has been defined and that it is not empty.
2. loop through each feed in the `allFeeds` object and ensure it has a URL defined and that the URL is not empty.
3. Loop through each feed in the `allFeeds` object and ensure it has a name defined and that the name is not empty.
### The menu.
1. Make sure the menu element is hidden by default. 
2. Make sure the menu changes visibility when the menu icon is clicked. This test has two expectations:  menu displays when clicked and hides when clicked again.
### Initial Entries.
1. Make sure when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
### New Feed Selection.
1. Make sure when a new feed is loaded by the `loadFeed` function that the content actually changes.

## How to run the tests
Load index.html in your browser. The tests in feedreader.js would run before the web app is loaded. The resulted of the tests would be available in the lower part of the window (in Chrome) after the page has loaded.
