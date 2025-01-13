# Outfit Planner
Outfit Planner is a website that gives you an opportunity to plan your outfits ahead for the week.

## Features
- You can add, remove, and reorder clothing categories and clothing items to each category.
- You can select what clothing items you're going to wear for each day.
- You can assign properties to each clothing item.
- You can reset the outfits for the day, the week, or the category.
- You can move between weeks to view what outfits were added to the given week.

## Structure
- Login/Signup page: The first page of the website where you can either create an account or log in to an existing account.
  - Each account has a username, a display name, an e-mail address and a password. You can log in using either the username or the e-mail address.
- Main page: Table containing each day of the week in the first row with dates, and the clothing categories in the first column.
  - You can add selected outfit types to the first column using the plus button.
  - The second row contains the information about what the weather is going to be like on the given day.
    - Temperature
    - Wind
    - Precipitation
  - Under the first two rows you can select clothing items from the categories of the first column for each day.
  - The navbar contains a dropdown menu where you can visit the rest of the pages of the website.
- Clothing categories: A page that contains a list of all the categories of clothing. You can add and remove categories. By clicking on a clothing category you can add clothing items to it.
- Clothing items: There's a clothing items page for each category which lists all the clothing items added by the user.
  - You can add clothing items by clicking on the plus button.
  - You can assign a name, a description, what type of weather the item is suited for, and select multiple categories it can belong to. You can also upload an image of the item.
- Calendar: List of each week the user added any clothing items to. You can open the weeks to view what outfits were assigned to the given week.
 
## Technology
| Framework: | Spring Boot |
| Language: | Kotlin |
