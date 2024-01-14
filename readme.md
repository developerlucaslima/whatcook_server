# App

What Cook


## RFs (Requisitos Funcionais)

User Authentication and Registration:
- [ ] Users must be able to register with unique email addresses.
- [ ] Users should authenticate themselves to access personalized features.
- [ ] Retrieving the profile of a logged-in user should be possible.
Recipe Discovery:
- [ ] Users must be able to discover recipes based on ingredients they have at home.
- [ ] Users should be able to search for recipes by name or type.
- [ ] It should be possible to filter recipes by meal (breakfast, lunch, dinner).
- [ ] It should be possible to filter recipes by region and cultures.
Recipe Tips:
- [ ] Users should be able to send recipe tips.
Nutritional Information:
- [ ] Recipes must contain nutritional information based on the TACO table.
- [ ] Users should be able to choose whether recipes include ingredients beyond their selection.
- [ ] Users can add pre-made recipes and input the ingredients for nutritional calculations.
Notifications:
- [ ] Users must be able to receive reminders to take creatine and water via WhatsApp or app notification


## RNs (Regras de Negócio)

User Registration Rules:
- [ ] Users cannot register with duplicate email addresses.
- [ ] Registration should not be mandatory for browsing recipes.
Recipe Rules:
- [ ] Recipes may or may not have ingredients beyond the selected ones, based on user preference.
Nutritional Information Rules:
- [ ] Nutritional information in recipes must adhere to the TACO table.
- [ ] Users can calculate daily macronutrients and micronutrients based on their food intake.


## RNFs (Requisitos Não-Funcionais)

Security:
- [ ] User passwords must be securely encrypted.
Data Storage:
- [ ] Application data must be persisted in a PostgreSQL database.
Pagination:
- [ ] All data lists (e.g., recipes, ingredients, gyms) must be paginated with a specified number of items per page (e.g., 20 items per page).
User Identification:
- [ ] Users should be identified and authenticated using JSON Web Tokens (JWT).
