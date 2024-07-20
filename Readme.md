# Book Management System
# Routes and endpoints

## /user
POST: creating a new user
GET: Get the List of all users

## /user/{id}
GET: Get a user by id
PUT: Update a user by id
DELETE: Delete a user by their id (check if he/she has an issued Book)(also need to the penality )

## /user/subscription-details/{id}
GET: Get user subscription details
    >>Date of the subscription
    >>Till the date validity
    >>Fine if any is exceeded the date of limit


## /books
GET: Get all the books
POST: creating/adding a new book

### /book/{id}
GET: Getting a book by Id

### /Subscription types
    >>Basic -3mon
    >>standard- 6mon
    >>premium- 12mon