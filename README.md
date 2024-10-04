run using nodemon index.js

##
### Authentication Endpoints

| Method | Route        | Description                  |
|--------|--------------|------------------------------|
| POST   | /register     | Register a new user          |
| POST   | /login        | Log in as an existing user   |
| GET    | /logout       | Log out the current user     |

##
### Recipe Endpoints

| Method | Route           | Description                      |
|--------|-----------------|----------------------------------|
| GET    | /recipes         | Fetch all recipes                |
| POST   | /recipes         | Create a new recipe              |
| PUT    | /recipes/:id     | Update an existing recipe        |
| DELETE | /recipes/:id     | Delete a recipe                  |
