# What's For Dinner?

## Table of Contents
  - [Introduction](#introduction)
  - [Technologies](#technologies)
  - [Features](#features)
  - [Illustrations](#illustrations)
  - [Deployed Page](#deployed-page)
  - [Possible Future Extensions](#possible-future-extensions)
  - [Set Up](#set-up)
  - [Organizational Resources](#organizational-resources)
  - [Sources](#sources)
  - [Contributors](#contributors)
  - [Project Specs](#project-specs)

## Introduction
  The purpose of this project is to build an application that utilitizes HTML, CSS, and Javascript. This assignment provides a comp that I used to recreate the web page. I can fulfill at least one feature that allows me to improve my programming skills and understanding of user events.

## Technologies
- Javascript
- HTML
- CSS

## Illustrations
##### What's For Dinner? 🥘🥘🥘
- Page on small screen.
  <img width="1439" alt="Small screen webpage view" src="https://user-images.githubusercontent.com/94808267/180631283-d9bb1c56-4280-419c-b361-83ed8a98f250.png">

- Page on large screen.
  ![Large screen webpage view](https://user-images.githubusercontent.com/94808267/180630899-932e4a58-73d0-4717-bde2-a6e70a90dae4.png)

1. Random Dish Functionality
<img width="1436" alt="Random Dish provided in right box" src="https://user-images.githubusercontent.com/94808267/180631299-31b6cd77-5945-44d2-ace6-504b78acd931.png">

2. Entire Meal Functionality
<img width="1324" alt="Entire Meal provides new main, side, and dessert dish" src="https://user-images.githubusercontent.com/94808267/180632238-9b2439fd-5a1c-4925-872d-858c9f9b604b.png">

3. Tell user to make a selection
  <img width="1325" alt="Tell user to make a selection" src="https://user-images.githubusercontent.com/94808267/180631065-eaa114b5-5dda-44b6-9554-85fa39a631f6.png">

4. Clear Button Functionality
- Without the cookpot image.
  ![Clear Button without cookpot](https://user-images.githubusercontent.com/94808267/180630968-f4031347-7f34-41be-8fca-075b1d79c537.png)
- With the cookpot image.
  <img width="1300" alt="Clear Button with cookpot" src="https://user-images.githubusercontent.com/94808267/180631109-71994c5f-7a74-4485-9503-6e84be26f739.png">

5. **Delete Button Functionality**
- Remove the dish from its respective array and see change in array length.
  <img width="721" alt="Remove dish from respective array" src="https://user-images.githubusercontent.com/94808267/180631212-bc761e8d-c0f3-4a0d-acb8-0d651cd22f59.png">

- Change button color and tell user that the dish has been removed.
  ![Delete button and text changes](https://user-images.githubusercontent.com/94808267/180630973-c2370999-7ce8-4f4d-964c-8c6cb36141f7.png)


## Features
1. Any of the radio buttons chosen will output a random dish from its respective array. The dish name will be displayed inside the right box as it replaces the cookpot image.
2. The user can select the "Entire Meal" radio button and it will output a combination of main, side, and dessert dishes.
3. When the user clicks the "Let's Cook!" button without selecting a radio button, the right box will output a message.
4. The "Clear" button will always revert the right box to the cookpot image.
5. The Choose Your Own Adventure I fulfilled was the “User can delete a recipe”. The button "I don't like this dish" is located on the top left corner of the right box. When clicked, the data model is updated by removing the current dish shown from its respective array. The button will change to red and the text will inform the user the dish was removed. With the inclusion of the entire meal's functionality, the user cannot choose to remove the Entire Meal output.

## Deployed Page
Visit my published What's For Dinner Site [here](https://ohclaire.github.io/whats-for-dinner/)

## Possible Future Extensions
  - Some of my functions are lengthy and need to be refactored for DRY and Single-Responsibility. Given more time, I would like to refactor showACourseDish and create a function for adding/removing the hidden class.
  - Having the "Add A Recipe" functionality would be nice to have so each array could be updated and expanded. 
  - Having a local storage would have gone well with my CYOA so that the dishes that were deleted would remain gone after reload. 
  - If I had chosen the "User can favorite a recipe" CYOA, I would have liked to build local storage that would save dishes that were favorited and design bookmarks to appear on the side of the page for the user to view these dishes even after a page reloads.
  - Building in transitions via CSS would make the page more interesting and have other features on the page for the user to interact with.


## Set Up
1. Fork this repo
2. Clone the repo to my local machine
3. View the project in the browser by running open index.html in my terminal.


## Sources
- [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList)
- [W3Schools](https://www.w3schools.com/tags/att_input_type_radio.asp)
- [BEM](http://getbem.com/introduction/)
- [StackOverflow](https://stackoverflow.com/questions/58606047/how-to-use-on-addeventlistener-on-radio-button-in-plain-javascript)
- [Pluralsight](https://www.pluralsight.com/guides/semantic-html)

## Project Specs
The spec for this project can be found [here](https://frontend.turing.io/projects/module-1/dinner.html). 
