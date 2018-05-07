# API Website

This website generates a random Pokemon name, and lists that Pokemon's type(s). Each type has an image that is used to represent it, as well as a color for the text, and the type(s) will be displayed above (and below) the Pokemon's name.

![](https://github.com/Camgerine/all-projects/blob/master/Webpage.png)

## What does it do?

Every time the page is loaded, the website randomly selects the name of a Pokemon from a JSON file. The Pokemon's name is displayed in the center of the page. The website also finds out the Pokemon's type(s) from the same JSON file. The name and image for the first type is displayed above the Pokemon's name, and the second type (if there is one) is displayed below the Pokemon's name. The name of each type also has a unique color in which the text will be shown.

## Tools and language used

The Twitter bot was coded in JavaScript using Brackets, and made use of a JSON file that allows it to generate the Pokemon names and detect the type(s) for each one. It also uses a variety of PNG images.

## Challenges

Properly aligning the images and text was the biggest challenge of this assignment. This is mainly due to it being very tedious to repeatedly try different X and Y values until I got it to look exactly how I wanted it to. Since there were many different variables involved due to all the different Pokemon types, I had to enter the new coordinates for each type to make sure that I could see the changes for whatever type combination was generated.

An additional challenge was that the JSON file was somewhat outdated. In recent Pokemon games, the Fairy type was added, and some of the old Pokemon ended up being changed to this new type. This meant I had to edit the JSON file and manually fix the data for every Pokemon that was changed in this way.

## Link to code

https://github.com/Camgerine/API-Assignment/blob/master/sketch2.js

## Link to site

https://camgerine.github.io/API-Assignment/