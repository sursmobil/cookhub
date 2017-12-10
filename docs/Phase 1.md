 # CookHub - phase 1
 
 ## Views
 
 ### Recipes list
 1. You can see list of recipes
 1. You can create a named recipe, ex. Kim chi
 1. You can delete recipe
 1. You can switch to a definite recipe
 
 ### Recipe
 1. You can change a recipe name
 1. You can add/change recipe description, ex. Korean Sauerkraut
 1. You can add/change ingredients list, simple text
 1. You can add/change way of preparation
 1. You can return to recipe list
 
## Model

### Recipe
```
{
  "name": string|required,
  "description": string|optional,
  "ingredients": string|otpional,
  "howToPrepare": string|optional
}
```
