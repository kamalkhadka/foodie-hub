# FoodieHub

## Overview:
FoodieHub is a database of recipes and personal sous-chef. 

### Goal:
FoodieHub wants to motivate and inspire you to cook and try new recipes. It is a recipe app that will help you discover, plan, and share recipes. 

### Expected Users:
FoodieHub will be used by home chefs to find and discover recipes to make / plan next meal.

### Data:
Recipes will be categorized by cuisines. Each recipe will have a list of ingredients and directions to make it. 

### Outline:
**Database Schema:**
	Recipes 	- table to store recipe name
	Users		- save user info
	Cuisines	- name of cuisines 
	Favorites	- user saved recipe
	Nutritions	- nutrition info about a recipe
	Diets		- different kind of diets will be use to label a recipe 
	Reviews	- rating and comment by a registered user for a recipe
	Groceries	- list created by user
		
**Challenges:**
- Finding API to find recipes and their nutrition information
- Categorize recipe based on cuisines and diet
- Finding average time to prepare a recipe 
- Recipe searched is not found 


**Security:**
User password needs to be secured
Some of the pages and functionality need to be secured for the type of user (anonymous / registered user)

**Functionality:**
		
 >Anonymous user can
 >- Search for recipes
 >- Filter recipe based on diet preference
 >- Filter recipe by preparation time 
		
>Registered user can
> - Favorite a recipe
> - Add a recipe
> - Create grocery list 
> - Review a recipe

**Flow:**

A user will be shown a list of recipes from different cuisines on the home page. A user can either click on one of those recipes and learn more about it, directions to make it. A user can see registered user ratings and comments for each of those recipes.

A user can also search for a recipe from the home page. They can also filter their search by cuisine, preparation time, diet preferences.

A registered user can login and look up their saved recipes, review recipes, create grocery lists, and add new recipes.

Both anonymous and registered users will be able to share recipes on social media.
