# README

This was the result of a one day HackaThon sponsored by Aweber. Anything was allowed, but we had to use the Aweber API. Participants in the AWeber HackAWthon were  tasked with using the AWeber API to create unique applications that solve problems.

## Contributors
***Collaboration between***
[Cassi King] https://github.com/cassking
[Benjamin Ennis] https://github.com/ennisbenjamind
[Eric Ruan] https://github.com/launcheric
[Monica Kosciuk] https://github.com/koscim

## Technologies
* Backend: Rails 5.1.5
* Webpacker
* Frontend: React.js
* Database: PostgreSQL

## To run locally
* Install Ruby.2.3.3
* In a terminal, run git clone `https://github.com/cassking/sweetbikerides.git`
* Navigate to the project's root directory with `cd sweetbikerides`
* Run `bundle install && yarn install && npm install && rake db:create && rake db:migrate && rake db:seed`
* In a separate terminal windows, run `npm start` && `rails server -- or-- rails s`
* Visit http://localhost:3000/ in your browser.

[ ![Codeship Status for cassking/sweetbikerides](https://app.codeship.com/projects/ee140d20-131d-0136-a67e-068f11ae90dc/status?branch=master)](https://app.codeship.com/projects/283120)
[![Code Climate](https://codeclimate.com/github/cassking/sweetbikerides/badges/gpa.svg)](https://codeclimate.com/github/cassking/sweetbikerides)
[![Coverage Status](https://coveralls.io/repos/github/cassking/sweetbikerides/badge.svg?branch=master)](https://coveralls.io/github/cassking/sweetbikerides?branch=master)
