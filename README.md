## Setup
The project can be loaded using Visual Studio Community Edition 2017
The App.Config files will both need to be updated to modify the DatabaseFile key to point to the location of this repository on your local machine.

## Tech Stack
This project makes use of the following technologies:
-SQLite for the database
-.Net 4.6

MVC 5 is used to handle the routing and layout.
Web Api 2 is used for the api

## Next Steps
Add a user tracking system to the order tracking
The UI should have an awareness of the remaining quantity of each flavor/topping to prevent selecting more flavors/toppings than remain. This would require expansion of the Ingredient Service and object to include quantity.
Improved Error Handling, the current system only displays errors to the end user, we should log error messages somewhere so the employees are aware of critical errors.


## Call Outs
Reset Inventory randomly generates a value between 10 and 100 for each ingredient and sets the Quantity of that Ingredient in the Inventory table to that value.
Employee Dashboard has the Done "button" to clear out delivered orders so that as new orders come in, completed orders can be cleared from the UI.
