# Recipe Book &middot; ![node](https://img.shields.io/badge/node-12.16.2-blue) ![mysql](https://img.shields.io/badge/mysql-2.18.1-blue) ![mysql2](https://img.shields.io/badge/mysql2-1.7.0-blue) ![sequelize](https://img.shields.io/badge/sequelize-5.21.12-blue) ![express](https://img.shields.io/badge/express-4.17.1-blue) ![bcrypt](https://img.shields.io/badge/bcrypt-4.0.1-blue) ![passport](https://img.shields.io/badge/passport-0.4.1-blue) 

[https://create-recipe-book.herokuapp.com/](https://create-recipe-book.herokuapp.com/)

![Recipe Book](/images/Recipe-Book-home-page.png) 

## Description 
This application gives the user the ability to search for recipes based on keyword and dietary needs and allows them to view details, walk through the steps, and save recipes to their recipe book. 

## Table of Contents 
* [Installation](#installation) 
* [Usage](#usage) 
* [Collaborators](#collaborators) 
* [License](#license) 
* [Questions](#questions) 
 
## Installation 
1. Navigate to project folder in your terminal/command line  
2. Install the following packages by typing the following and pressing enter: npm i bcrypt bcryptjs dotenv env express express-session mysql mysql2 passport passport-local sequelize  
<<<<<<< HEAD
3. Get an API Key from the Spoonacular API by creating an account on [spoonacular.com](https://spoonacular.com)  
=======
3. Get an API Key from the Spoonacular API by creating an account on [spoonacular.com](https://spoonacular.com) 
>>>>>>> f69d0f1e1c8d024e9cf310c48cbe78f12efd1924
 
## Usage 
1.  The user starts by signing up for an account, and then logging in.  
2.  Once they have logged in, they are taken to their recipe book page with a message instructing them to search for recipes using either the global search at the top of the page, or the advanced search, provided by selecting the Advanced Search link. ![Recipes-home-no-recipes-added](/images/Recipes-home-no-recipes-added.png) 
3.  When search criteria text is entered in the search box and the “Search” button is clicked, results are displayed below displaying each recipe’s image, title, prep time, servings, and action buttons. The user has the option to either add the recipe to their recipe book by selecting the “Add” button, or viewing the recipe details first by selecting the “Details” button. ![Recipes-Global-Search](/images/Recipes-Global-Search.png) 
4.  Selecting the “Details” button will display the details for that recipe including recipe title, prep time, servings, description, cuisine categories (if available), diet categories (if applicable), ingredients list (includes images), and nutrition information (displayed in a table). At the top and bottom of this page is a “Go Back” button which takes the user back to their recipe book page, and a “Start Cooking” button which takes the user to the first step in the recipe. ![Recipe-Details-Form](/images/Recipe-Details-1.png) ![Recipe-Details-Results](/images/Recipe-Details-2.png)
5.  When the user selects the “Start-Cooking” button, they are taken to Step 1 of the cooking process. Each step displays the equipment needed (if applicable), the ingredients needed (if applicable, some images may not be displayed), and the directions at the bottom. When the user is done with the current step, they can select the “Next button” to go to the next step or the previous button to go to the previous step or the Details page if the user is currently on the first step. On the last step of the recipe, the “Done” button is displayed in place of the “Next” button. Selecting the “Done” button will redirect the user back to their Recipe Book page. ![Recipe-Step-1](/images/Recipe-Step-1.png)
6.  When a recipe is searched for either using the global search or the Advanced search page, and the “Add” button is pressed, an alert is displayed notifying the user that the recipe was just added to their recipe book. To view the recipe just added, the user must select the “My Recipes” link in the navigation bar. There they will see the recipe just added with a source link at the bottom. ![Added-Recipe](/images/Added-Recipe.png) 
7.  This is the Advanced Search form. ![Recipes-Advanced-Search-1](/images/Recipes-Advanced-Search-1.png) The user can enter various search criteria such as dish name, cuisine, prep time, and maximum amount of  calories, carbs, fat, sodium, and sugar. They can also search based on diet such as vegetarian, or ketogenic and intolerances such as dairy and gluten. ![Recipes-Advanced-Search-2](/images/Recipes-Advanced-Search-2.png) 
 
## Collaborators 
* Tevin Ward [github.com/TevinWard7/Recipes-Project](https://github.com/TevinWard7/Recipes-Project) - Created Advanced Search form and AJAX API query requests for Advanced Search form. Also created delete express route to remove recipes from the recipe book.
  
Spoonacular API [spoonacular.com/](https://spoonacular.com/) 
