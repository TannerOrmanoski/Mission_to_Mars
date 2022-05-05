# Mission_to_Mars

## Purpose

The purpose of this project was to create a Mars webpage that scrapes data from other webpages. Our final wedpage shows the latest Mars news, a featured image of Mars, a table of Mars facts, and images of the four hemispheres of Mars. The webpage also features a scrape button that will update the Mars news section.

## Process

This process involved many integrated steps. The first step was creating setting up splinter to automate a browser. The next step was to create our scraping script. This script accessed a few different sites inorder to collect the elements we needed. By using dev tools, we were able to pin down the desired elements. We then stored the data using mongo. From here we used flask to create the webpage. The scraping script had to be edited to include error handling and function, so that flask could appropriately execute the script. Finally, we customized the appearance using an html template and bootstrap.


