# sb_36-02-08_ExpressBookStore_APIValidationExercise


## Technology Stack
- **Front-end**: N/A
- **Back-end**: Node.js, Express, and Postgres.


## Assignment Details

**Express Bookstore** is an Express API application that demonstrates the use JSON schema validation. The bookstore application was already build with completed routes and database model. 

**Part One - Gestting Started + Adding Validation** involved setting up the environment, declaring databases, and creating and adding a JSON schema for validations. JSON schema validations were needed for books insert (`post`) and books update (`put`) routes. A different schema is used for updates and inserts because an insert requires an ISBN while the update does not because on an update, the ISBN is a url parameter. 

**Part Two - Add Tests** 
Twelve (12) tests were added to test the routes. Even though the `post books\` and `put books\:isbn` were the only routes edited, none of the other routes had tests. Test cases covered successful executions as well as ensuring the errors were also created as expected.

**Further Study** 
No further study suggestions were implemented.


## Enhancements
- Server port is a configurable parameter and the start message includes the data and time the server started. 

## Difficulties
- No major difficulties to report.
