# Project Overview

In this project I was given a web-based application that reads RSS feeds. It included [Jasmine](http://jasmine.github.io/) but was missing the tests. I wrote tests against this pre-existing application and tested the underlying business logic of the application as well as the event handling and DOM manipulation.

## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

## Tests I have implemented
1. Test suite: Named `"RSS Feeds"`
  * test: Loops through each feed in the `allFeeds` object to ensure they have a valid URL (is defined & not empty).
  * test: Loops through each feed in the `allFeeds` object to ensure they have a valid name (is defined & not empty).
2. Test suite: Named `"The menu"`
  * test: Ensures the menu element is hidden by default.
  * test: Ensures the menu changes visibility when the menu icon is clicked.
3. Test suite: Named `"Initial Entries"`
  * test: Ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container (includes asynchronous testing).
4. Test suite: Named `"New Feed Selection"`
  * test: Ensures when a new feed is loaded by the `loadFeed` function that the content actually changes (includes asynchronous testing).

## How to use this program
If you're mainly interested in the feedreader or seeing how Yasmine displays my passing tests, you can view it [here](https://katharinaxeniakufieta.github.io/frontend-nanodegree-feedreader/#).

For using the project locally:

1. Download files, or clone the repository: `git clone https://github.com/KatharinaXeniaKufieta/frontend-nanodegree-feedreader.git`
2. Open `index.html`
3. View (passing) tests at the bottom of the page

