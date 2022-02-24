# SpringAPIDemo

This is a simple REST API demo created with the Java SpringBoot Framework.

One can perform CRUD operations on the Person instance.

## Endpoints

`/api/v1/person`

- GET -> Returns all people <br/>
- GET (query params: id `/{id}`) -> Returns a person by its ID <br/>
- PUT (query params: id `/{id}`, body: Person (String name)) -> Updates the name of a Person with a specific ID <br/>
- POST (body: Person (String name)) -> Inserts a new person entry to the db <br/>
- Delete (query params: id `/{id}`) -> Deletes a person by its ID <br/>
