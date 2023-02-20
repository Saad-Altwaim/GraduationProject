# GraduationProject

App Description

This app allows users to srearch Recipe by name or name And CookingTime (using spoonacular API ) OR Selectrandom Recipes Once the user select any  
results . the results displayed in a table view for search Or collection view for Random 
Once the search results are displayed the user can select a Recipe to open a detail view . In the detail view the Recipe can be saved adding it to the Recipes list.

A Recipe can be deleted from the own list by swiping left on the respective cell.

Project Details
User Interface

    five main View Controllers:
        Food Joke ViewController
        Random Recipes ViewController
        ViewController (search view recipe )
        SavedDataViewController
        recipe Detail View Controller
        
    two View Controllers are using a Table View
    - SavedDataViewController
    - ViewController (search view recipe )
    
    Random Recipes ViewController 
    - collection view controller 
    
    to view all view you can tab Bar controller 

    All view are embedded in a Navigation View Controller to display Recipe Detail View
    Activity View Controller to share a book
    All recipe informations Are sorted 
    -title
    -recipeCookingTime
    -recipeImageView
    -recipeInstructions
    -recipeIngredient
    -numberOfServings
    Online Recipe search and searching in own Recipe list via UISearchBar

Networking

     spoonacular  API is used to retrieve Recipe information like:
    -title
    -recipeCookingTime
    -recipeImageView
    -recipeInstructions
    -recipeIngredient
    -numberOfServings


Persistence

    Recipe added to the RecipeDB  are stored in Core Data

