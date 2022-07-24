# Tripilo RestFul-API
Full stack Application developed with RESTful Api and MVC Architecture

## Overview

This application is richly built with astonishing features such as rating, reviews, booking, email sending, online payment, Aggregation pipeline, and Geospatial Queries among others.

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

