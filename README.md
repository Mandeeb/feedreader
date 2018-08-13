# Project Overview

I used  [Jasmine](http://jasmine.github.io/) to write tests against an existing Feed Reader Application.


## How to run the application:

1.
2.
3.
4.


## Steps I took to complete the project:

1. Took the JavaScript Testing [course](https://www.udacity.com/course/ud549)
2. Downloaded the [required project assets](http://github.com/udacity/frontend-nanodegree-feedreader).
3. Reviewed the functionality of the application within your browser.
4. Explored the application's HTML (**./index.html**), CSS (**./css/style.css**) and JavaScript (**./js/app.js**) to gain an understanding of how it works.
5. Explored the Jasmine spec file in **./jasmine/spec/feedreader.js** and reviewed the [Jasmine documentation](http://jasmine.github.io).
6. Edited the `allFeeds` variable in **./js/app.js** to make the provided test fail and see how Jasmine visualized this failure in the application.
7. Returned the `allFeeds` variable to a passing state.
8. Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
9. Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
10. Wrote a new test suite named `"The menu"`.
11. Wrote a test that ensures the menu element is hidden by default. I had to analyze the HTML and the CSS to determine how they were performing the hiding/showing of the menu element.
12. Wrote a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
13. Wrote a test suite named `"Initial Entries"`.
14. Wrote a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
15. Wrote a test suite named `"New Feed Selection"`.
16. Wrote a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
17. No test should be dependent on the results of another.
18. Callbacks should be used to ensure that feeds are loaded before they are tested.
19. Implemented error handling for undefined variables and out-of-bound array access.
20. All of my tests pass.
21. Wrote a README file detailing all steps required to successfully run the application.
