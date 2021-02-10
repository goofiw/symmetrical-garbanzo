# Strive BE-HW

As a exercise of your excellent skills, we would like you to implement a backend graphql Create and Get route.

Clean architecture should be strived for.  A nestjs backend and docker image of the database is provided, along with run scripts.  However, you may use any nodejs typescript stack to complete the task as long as it uses a graphql api and and connects to a postrgres database

## Timing

We'll give 3 hours for this task, and then followup with a video call shortly after (please be in a place where your camera can be on!) to discuss design decisions and what there wasn't time for to make this production ready! 

### User Story

As a user I want to create a player

### Acceptance Criteria

- Route creates creates a player in a backend database with a required name and optional number and optional birth date
- Route to get player by playerId assigned by the database
- Typescript and postgres must be used (docker image for database and connection string provided)
- includes migration script for the database

### Out of scope

- any frontend code

