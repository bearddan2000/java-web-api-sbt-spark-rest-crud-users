# java-web-api-sbt-spark-rest-crud-users

## Description
A REST API to create/update/delete
and edit a list of in-memory users.

## Tech stack
- java
- sbt
  - spark

## Docker stack
- openjdk:8-jdk-alpine

## To run
`sudo ./install.sh -u`
- Available at http://localhost
  - GET /users — get list of all users
  - GET /users/:id — get user with given id
  - POST /users/:id — add a user
  - PUT /users/:id — edit a particular user
  - OPTIONS /users/:id — check whether a user exists with given id
  - DELETE /users/:id — delete a particular user

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- [Building an API With the Spark Java Framework] (https://www.baeldung.com/spark-framework-rest-api)
