# Tripilo RestFul-API
Full stack Application developed with RESTful Api and MVC Architecture

## Overview

This web application allows it's users to book tour vacations.

A tour refers to a series of locations, specially picked to excite the adventurous spirit of the individual who books it.

A visiting user who has not yet created an account on the app can simply see all the current tours as well as detailed information about each tour.

Once signed up or logged in, they can then book any tour of their choice.

Users can write only one review for any tour they book.

## API Endpoints

| Methods | Endpoints                                                | Access  |  
| ------- | -------------------------------------------------------- | ------- |
| GET     | /api/v1/users/:userId                                    | Private |
| GET     | /api/v1/users                                            | Private |
| PATCH   | /api/v1/users/:userId                                    | Private |
| DELETE  | /api/v1/users/:userId                                    | Private |
| POST    | /api/v1/tours                                            | Private |
| GET     | /api/v1/tours                                            | Public  |
| GET     | /api/v1/tours/:tourId                                    | Public  |
| PATCH   | /api/v1/tours/:tourId                                    | Private |
| DELETE  | /api/v1/tours/:tourId                                    | Private |


## Technologies

- Node.js
- Express.js
- MongoDB
- Mongoose
- and other commonly used back-end implementations

## Prerequisites

- [npm](https://www.npmjs.com/)
- [mongoose](https://mongoosejs.com/)

## Cloning this project repository

`git clone https://github.com/tush16/tripilo.git`

## Installing dependencies

`nom install`

## Running this app locally

- In development mode: `npm start:dev`
- In production mode: `npm start:prod`
- Server should be running on port 3000
## Developed By

- [@Tushar choudhary](https://www.github.com/tush16)
