# Feed Reader Testing Project

## Introduction

this project is designed to test a web-based application that reads RSS feeds. The testing framework used in this project is Jasmine 2.1.2


## How to run this application?

1. To Start the application, simply double click the "index.html" file to open in your favourite browser.
2. To access different available feeds, click on the hamburger icon on the top left corner of the screen, after that simply click on your desired feed to load it.
3. After the loading is complete, click on any news link to open it up.
4. If you opened the feed list but changed your mind regarding viewing a different feed, simply click once more on the hamburger icon to close the side menu.


## Tests implemented

* There are a set of different tests implemented using the Jasmine testing framework 2.1.2 and they are divided to four sections:

1. RSS Feeds: These test checks the different feeds that are available for selection and whether they are correctly defined and contain their respective names and URLs.
2. The menu: These test check to see that the functionality of the menu is not faulty, that it appears and disappears upon clicking of the hamburger menu icon, and also check to see that the menu is hidden by default.
3. Initial Entries: This test checks to see that actual news links are loaded onto the page when feed is clicked, that no error occured during loading that stopped the news from loading onto the page.
4. New Feed Selection: This test checks to see that new different news is loaded onto the page when a new feed is clicked.
