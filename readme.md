
The web app will serve as a food recipe resort, displaying an amount of food and a way to show the preparation method.

## Design Concept

The web app will be responsive to Mobile and Desktop alike. It should not have a navigation system, rather just a hero section consisting of a responsive logo icon aligned at the left.

The hero section has a background image and a catchy text "Hello Foodie!". Right Under the text, we have 4 social icons linking to different personal social media handles.

After the hero section, we have a list of food in grid format: 3 per row and 4 per column on PC, ie 12 in total. On mobile, we have a list of 2 per row, and 6 per column, ie 12 also.

The Food listing will display a card with Food Image, Food Name, Food Category, & Budget Estimate.

When the card for a particular food is hovered on, we have some animation or hover effect. When clicked, a popup appears displaying the property of the particular food.

### Food Property

1. Image of the food in a carousel.
2. A table displaying the ingredients, and their prices.
3. An article describing the preparation method of the food.

## Resources

* Bootstrap CDN: For CSS & JS Library
* Font Awesome: For Icons like Fonts
* Google Fonts: For Impressive Fonts
* Google Image Search: For Our Images

### Personal CSS File: For Extra Styling.
* ID heroSection: Contains background Image, Color, and Padding of the hero section.
* Class myImg: Contains the style for our Logo Icon.
* Class foodIMG: Contains the class for the Food Image in the card.
* Class foodBox: Contains the class for the Food Box.

** NOTE THAT THE FOOD BOX SHOULD ALSO CONTAIN THE MODAL TRIGGER. **

## Developer Concept

The Hero Section will Contain both our Logo Icon and Our Welcome texts, both being separated by adequate amount of margin.

The Food listing contains grid layout system using col-6 class for PC, and col-md-4 for mobile ie class="col-6 col-md-4"

The food card uses a combination of Bootstrap Card and a Bootstrap Modal; the card to give it the design and the modal to give it the trigger  and modal content.

The carousel contains images of the food.


** NOTE THAT THE MODAL CONTENT SHOULD BE PLACED AT THE BUTTOM OF THE CODE CLOSE TO SCRIPTS.
FINALLY COMMENT YOUR CODE AS YOU GO, **


## General Overview




