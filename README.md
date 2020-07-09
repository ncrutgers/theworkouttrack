# The Workout Track

A workout tracker that allows user to create, view, and track workouts. This application utilizes creation of Mongo database with a Mongoose schema and handle routes with Express.

## User Story

As a user, I want to be able to view create and track daily workouts therefore tracking their progress. I want to be able to log multiple exercises in a workout on a given day. I should also be able to track the name, type, weight, sets, reps, and duration of exercise. If the exercise is a cardio exercise, I should be able to track my distance traveled.

## Installation

No installation required for usage unless cloning project.

Dependencies can be installed with the following command:

```sh
npm install
```
MongoDB and connection to your application required to utilize a database with application.

To run application:

```sh
node server.js
```
or

```sh
npm start
```

## Usage

* The Workout Track is an application that as when the user's page loads, an option to create a new workout, or continue with their last workout is presented.

User should be able to:

  * Add exercises to a previous workout plan.

  * Add new exercises to a new workout plan.

  * View multiple the combined weight of multiple exercises on the `stats` page.


![The Workout Track](/public/assets/images/chart.PNG)
* The URL to the deployed application
[Heroku Deployment](https://theworkouttrack.herokuapp.com)



 