# RecipeFinder (Web App Implementation): Prototype Implementation Report
## Introduction
RecipeFinder is a mobile application that aims to enhance the regular user’s overall cooking experience and motivate new users to start out. It provides a variety of options that make cooking enjoyable and satisfying for any user. With RecipeFinder, they can search for their favourite recipes, create their own favourites list, and be provided with each recipe’s nutritional information while also having the flexibility to view their daily nutritional intake.

This interactive prototype implementation was created in correlation to the original project proposal from Phase 1 (<a href="https://sites.google.com/view/seng-310" target="_blank">link</a>) and the low-fidelity mock ups and design models from Phase 2 (<a href="https://sites.google.com/view/seng310-recipefinder/home" target="_blank">link</a>). 
We followed the requirement specifications with extreme care and precision and made sure to only make changes to aspects that were otherwise unclear and/or non-existent. Any design deviations are outlined below.  

## Design Deviations
While creating the prototype, we made deviations in the app’s design. Each deviation is described below. 

### App-Wide Deviations
* We have chosen a green/orange/white color theme to be displayed across the app, as no color theme was specified in the design document.
* We also chose to apply material design across the app alongside the color theme for aesthetic appeal.

### User Profile Deviations
* Since the Email field is meant to be unmodifiable, we didn’t want it to share the same affordances as the fields that can be modified, as this would be very misleading. For this reason, we decided to remove the surrounding display box for this particular field, as well as separated it from the others via a horizontal line. 
* Removing the menu for pre-editing the serving size of each recipe was another design choice we had to make in developing this prototype. The specifications did not clearly describe the functionality of this menu, and it’s aesthetic design was never included. Without a clear description of its design or purpose, we were unable to prototype this menu.  

### Health Tracker Deviations
* Rather than having the user scroll down for more intake details, it would be more convenient for the user to press “+” for further information. This would make the application faster as it wouldn’t have to display all user health information with every load.
* When the user expands the dropdown for options, pressing a valid option would add it to the graph in the real application. A second press will remove it and so on.
* Additionally, when the user expands the dropdown, instead of listing every single option (which could exceed 100), it would be more intuitive for the user to see the two most popular options and have the flexibility of viewing all other options on a separate tab. 

### Weekly Meal Plan Deviations
* To stay consistent with the overall flow of the prototype, we decided it was better to keep the same general format in both Weekly Meal Plan and Group Meals.  

### Group Meal Planner Deviations
* According to the design specifications for the Group Meal Planner, users are able to receive polls from other users as well as view the results of polls they create, however, the method for accessing these interfaces is never described. We decided to add a general purpose “INBOX” button to the header on the Group Meal Planner page, in order to allow the user to access these interfaces.

## Live Prototype
A few notes should be considered when using our prototype app. We have decided to create the prototype as a **responsive web app for ease of access/evaluation**. RecipeFinder, however, is intended to be run as a native mobile application. Therefore, a final implementation should only adopt the user interface presented in the prototype. To mimic a native mobile experience, we strongly encourage **resizing the browser window to match a smartphone screen**. This can be accomplished in one of two ways: 
1. Open the web app on a smartphone browser. 
2. Open the web app on a desktop browser and resize the browser window to mimic a smartphone browser.

As is the standard for high-fidelity prototypes, no real data is stored, collected, or shown in the RecipeFinder prototype. The prototype should be used to view where and how data would be shown to the user.

<span style="color:red;">Please note that there is an issue with running this web app with Firefox, Safari, and IE where some elements overlap each other. Therefore, please access this app with <b>Google Chrome</b> for guarenteed optimum functionality.</span>

---

Our prototype can be accessed at <a target="_blank" href="https://recipe-finder-web-app.herokuapp.com/">https://recipe-finder-web-app.herokuapp.com/</a>. Please be aware that it may take a few seconds for Heroku to wake up the app.

---

## Contributions
**V00825042** wrote the code for Help & Support and the code for View Specific Recipe. He also made minor tweaks to files that maps to View Specific Recipe.

**V00841719** has written the code for Weekly Meal Planner, Saved Recipes, and Health Tracker. He also fixed minor bugs across other files.

**V00822365** set up the GitHub repository, template code, and the Heroku web app. He has written the code for the Search Recipes screen, the Display Recipes screen, Task Bar, and Login screen. He has also searched for various bugs, fixed some and cleaned up the repository throughout the phase and created the README. 

**V00820622** wrote the code for the Profile and Group Meal Planner pages. 
