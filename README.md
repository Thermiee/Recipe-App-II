# Recipe-App
The Recipe app keeps track of all your recipes, ingredients, and inventory. It will allow you to save ingredients, keep track of what you have, create recipes, and generate a shopping list based on what you have and what you are missing from a recipe. Also, since sharing recipes is an important part of cooking the app should allow you to make them public so anyone can access them.

## Project requirements
- You should follow the layout of the wireframes provided. You should personalize the rest of the design including colors, typographies, spacings, etc.
- Login page and registration page:
    - Should be built with Devise.
- Food list:
    - Should display a list of food as in the wireframe.
    - Should lead to the form that allows users to add new food.
- Recipies list:
    - Should display a list of recipes created by the logged-in user as in the wireframe.
    - Should lead to recipe details.
    - If the user is the owner of the recipe, should allow user to delete it.
- Public recipe list:
    - Should display a list of all public recipes ordered by newest as in the wireframe.
    - Should lead to recipe details.
- Recipe details:
    - If the recipe is public or the user is the owner of the recipe, should display the recipe details as in the wireframe.
    - If the user is the owner of the recipe, should lead to the form that allows user to add new food.
- General shopping list view (**do not implement if in group of 3**):
    - Should show the list of food that is missing for all recipes of the logged-in user.
    - Should count the total food items and total price of the missing food.
- Make sure there are no N+1 queries happening.
- Create navigation menu that allows users to open all of the pages you created.

## Clone Project
- STEP 1:
  - git clone `git@github.com:oluyaratosin123/Recipe-App-II.git`
- STEP 2:
  - `cd Recipe-App-II` in your terminal
- STEP 3:
  - run `rails server` or `rails s` in your terminal
- STEP 4:
  - visit `localhost:3000` on your browser
> Yeyyy you have the app running **Congratulations** 😅🎉

## Run test suits
  > rspec spec

## Technologies Used
* Language (Ruby on Rails)
* PostgreSQL

## Installation
* Ruby
* Rails
* Postgresql

## 👤 Author 
Edward Yara  
- GitHub: [@oluyaratosin123](https://github.com/oluyaratosin123)
- Twitter: [@TOluyara](https://twitter.com/TOluyara)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/edward-oluyara/)

Emmanuel Jolugbo
- GitHub: [@Thermiee](https://github.com/Thermiee)
- LinkedIn: [@emmanuel-jolugbo](https://www.linkedin.com/in/emmanuel-jolugbo/)

## Contributing :handshake:
Contributions, issues, and feature requests are welcome!

## Show your support
Give a :star: if you like this project.

## Acknowledgments
* Hat tip to anyone whose code was used
* Inspiration
* etc

## License :memo:
This project is [MIT](https://github.com/microverseinc/readme-template/blob/master/MIT.md) licensed
