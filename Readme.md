#  MY RECIPE APP 
The web app will serve as food recipe resort, displaying an amount of food and a way to show the prepartion method.

## Design Concept
The web app will be responsive to Moblie and Desktop alike. It should not have a navigation system, rather just a hero section consisting of a responsive logo icon alignerd at the left.

The hero section has a background image and a catchy text "Hello Foodiel". Right Under the text we have 4 social icons linking to different personal media handles.

After the hero section, we have a list of foods in grid formal: 3 per row and 4 per column on PC ie 12 in total. On mobile, we have a list of 2 per row and 6 per column ie 12 also.

The Food listing will display a card with Food Image, Food Category and Budget Estimate.

When the card for a particular food is hovered on we have some animation or hover effect. When clicked a popup appears displaying the property of the particular food.

## Food Property 
1. lmage of the food in a carousel,
2. A table displaying the ingredients, and their prices.
3. An article describing the preparation method of the food.

## Resources
* Bootstrap CDN: For CSS and JS Library
* Font Awesome: For Icons like Fonts
* Google Fonts: For impressive fonts
* Google Image Search: For Our Images

Personal CSS File: For Extra Styling.
* ID heroSection: Contains background Image, Color, and Padding of the hero section.
* Class mylmg:Contains the style for our logo Icon.
* Class foodIMG: Contains the class for the Food Image in the card.
* Class foodBox: Contains the class for the Food Box.

** NOTE THAT THE FOOD BOX SHOULD ALSO CONTAIN THE MODAL TRIGGER **

## Developer Conceptg

The Hero Section will Contain both our Logo lcon and Our Welcome texts, both being separated by adequate amount of margin.

The Food listing contain grid layout system using col-6 class for PC, and col-md-4 for mobile ie class= "col-6 col-4".

The food card uses a combination of Bootstrap Card and a Bootstarp Modal; the card to give it the design and the modal to give it the trigger and modal content.

The carousel contains images of the food.

** NOTE THAT THE MODAL CONTENT SHOULD BE PLACED AT THE BUTTOM OF THE CODD CLOST TO SCRIPT, FINALLY COMMENT YOUR CODE AS YOU GO.**

## General Overview
