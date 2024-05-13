# Mobility iQ - Backend Take-Home Assignment #

## Objective ##

Build a simple CRUD application that has the following requirements/features:

* Application should start with `docker compose up`
* Two services:
  * Postgres database
  * FastAPI web app
* Endpoints should be:
  * GET /users - returns a list of all users
  * DELETE /user - delete a user in the database
  * POST /users/create - creates a user record in the db
* sqlalchemy as an ORM

A user has the following attributes:

* firstname
* lastname
* age
* date of birth

The above task is designed to show your familiarity with the technology MobilityIQ uses.

Once complete, a non-technical person should be able to pull your repo and:

1. Type `docker compose up` to start the application.
2. Use POST `/users/create` to add a user.
3. Use GET `/users` to retrieve a list of users.
4. Use DELETE `/users` to delete a user from the database.

## Submission ##
Once submitted, your application will be tested and in a short technical interview you will be asked to go over your 
code and answer some questions about the application.

Please use this as an opportunity to show how you normally code and approach coding assignments.