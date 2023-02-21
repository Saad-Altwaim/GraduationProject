# QuickRecipe

## App Description

This app allows users to srearch Recipe by name or name And CookingTime (using spoonacular API ) 
OR Select A Random Recipes from the Main screen 
Once the user select any results . the results displayed in a table view for search App Screen Or collection view for Random App Screen 
Once the use select a Recipe that recipe is  open in a detail view . 
In the detail view the Recipe can be saved adding it to the Recipes list.

A Recipe can be deleted from the own list by swiping left on the respective cell
Project Details User Interface

## five main View Controllers:

 - ViewController (search view recipe )
- Food Joke ViewController
- Random Recipes ViewController
- SavedDataViewController
-  recipe Detail View Controller

## The Main view is Random Recipes ViewController


[![N|Solid](https://i.ibb.co/GQC0H9s/Screen-Shot-2023-02-21-at-3-43-43-PM.png)](https://nodesource.com/products/nsolid)

every time you open the App a List of random Recipe will be display on the App Screen
And you can select A recipe to view the Recipe Detailes 
if you want a new set of recipe you can press the refreach button on the up right 

# Food Joke ViewController
[![N|Solid](https://i.ibb.co/HKPstdV/Screen-Shot-2023-02-21-at-3-45-10-PM.png)](https://nodesource.com/products/nsolid)

if  you select the next tab you can see A random Food Joke to make you day a happy day 

# search Recipe ViewController
[![Build Status](https://i.ibb.co/FxPY0bF/Screen-Shot-2023-02-21-at-3-45-36-PM.png)](https://travis-ci.org/joemccann/dillinger)

if you select the third tap you can search by recipe Name 
# OR

[![Build Status](https://i.ibb.co/k4Q6Mmf/Screen-Shot-2023-02-21-at-3-46-02-PM.png)](https://travis-ci.org/joemccann/dillinger)

you can search by Recipe name And Recipe Time 

And if pick any recipe the detail view will open to display the Recipe informations 

[![Build Status](https://i.ibb.co/XVg6jJV/Screen-Shot-2023-02-21-at-3-46-24-PM.png)](https://travis-ci.org/joemccann/dillinger)

and the recipe info include 
 - recipe name
- cooking time 
- number of srevings
- ingredients
-  instructions 
-  recipe Photo

# SavedDataViewController

[![Build Status](https://i.ibb.co/1QP9GT0/Screen-Shot-2023-02-21-at-3-48-04-PM.png)](https://travis-ci.org/joemccann/dillinger)

if you select the Last you will view your saved recipes 
but becuase we did not save Any Recipe we see this Message 


# if we press the save button 

[![Build Status](https://i.ibb.co/1n7nkyb/Screen-Shot-2023-02-21-at-3-50-37-PM.png)](https://travis-ci.org/joemccann/dillinger)
if we press the save button in the detail view controller the recipe will be save in coredata And we will view this Message 

# view saved recipes List

[![Build Status](https://i.ibb.co/frXnN59/Screen-Shot-2023-02-21-at-3-50-54-PM.png)](https://travis-ci.org/joemccann/dillinger)

after we saved our recipe we can view the recipe in last tab 
the save recipe tab

# view saved recipes detailes from save recipe tab

[![Build Status](https://i.ibb.co/3W3ns2T/Screen-Shot-2023-02-21-at-3-51-07-PM.png)](https://travis-ci.org/joemccann/dillinger)

if the user pick any recipe he will see the recipe detailes here 

## How to build
you build the  app, 
by cilck the build button in xcode .

## Requirements
Xcode 14
Swift 5.X

