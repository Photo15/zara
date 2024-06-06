# zara
Recipe Management Console Application


This is a console application for managing recipes. The application allows you to:

1.	Enter recipe details.
2.	Display a list of recipes.
3.	Scale the quantities of a recipe.
4.	Reset the quantities of a recipe to their original values.
5.	Clear all the data of a recipe.
6.	Exit the application.



Features

•	Enter Recipe Details: Input the name, ingredients, quantities, measurements, calories, food groups, and preparation steps for a recipe.
•	Display Recipe List: View the list of all recipes along with their details.
•	Scale Recipe: Adjust the ingredient quantities based on a scaling factor (e.g., 0.5, 2, 3).
•	Reset Quantities: Reset the ingredient quantities of a recipe to their original values.
•	Clear All Data: Remove all data associated with a recipe.



Prerequisites

•	.NET SDK (Version 5.0 or higher recommended)


Usage

Menu Options

1.	Enter Recipe Details

•	Enter the name of the recipe.
•	Enter the number of ingredients.
•	For each ingredient, provide the name, quantity, measurement unit, calories, and food group.
•	Enter the number of preparation steps and describe each step.


2.	Display Recipe List

•	Lists all recipes.
•	Choose a recipe by its number to view its detailed ingredients and preparation steps.

3.	Scale Recipe

•	 Lists all recipes.
•	Choose a recipe by its number.
•	Enter a scaling factor (e.g., 0.5, 2, 3).
•	View the scaled quantities of the ingredients.

4.	Reset Quantities

•	Lists all recipes.
•	Choose a recipe by its number.
•	Resets the ingredient quantities to their original values.

5.	Clear All Data

•	Lists all recipes.
•	Choose a recipe by its number.
•	Clears all data associated with the selected recipe.

6.  Exit

•	Exits the application.



Input Validation



•	Ensure all inputs are valid. For example, ingredient quantities and calories must be numeric.
•	Ingredient names and measurement units should not contain numbers or punctuation.
•	The application provides prompts for invalid inputs.


Health Warning

•	A warning is displayed if the total calories of a recipe exceed 300.


Code Structure


•	Program.cs: Contains the Main method and the Menu method for displaying the menu and handling user input.
•	getandset.cs: Defines the getandset.cs class with properties for recipe attributes.
•	UserData.cs: Contains the UserData class with methods for capturing, displaying, scaling, resetting, and clearing recipe data.

