![CF](https://i.imgur.com/7v5ASc8.png)  Lab 08: CRUD a Resource
=======
[![Build Status](https://travis-ci.org/codefellows-seattle-301d9/08-crud-a-resource.svg?branch=master)](https://travis-ci.org/codefellows-seattle-301d9/08-crud-a-resource) [![GitHub issues](https://img.shields.io/badge/Issues%3F-Ask%20for%20Help!-orange.svg)](https://github.com/codefellows/seattle-301d4/issues/new)

The starter code is all set for you and a pair to dive it, and get it working! Open up the [production deployment](https://cf-mvc-blog--class08.aerobatic.io/) of the working version, and play around in the console.

## User Stories: MVP
 - As a developer, I want article data to persist with SQL, so that I can store more, faster and have more query flexibility.

This means you'll want to be able to do full CRUD on articles in the database. You'll have to use SQL to make a table for articles (**and clear out the table for troubleshooting**), with a class-level method attached to the constructor function (because it does not apply to any single instance). Then teach each article instance how to write or update itself to the database, or delete itself, via instance methods (available for use as needed in the code).

Crucially, you'll need to trace through the app logic, and all those callback functions to determine WHEN is the right time to load data, or convert JSON.

Look through the TODOs, which signify areas of the code with varying levels of completeness, and focus initially on writing correct SQL. Practice in the web inspector.

There is no portfolio assignment.

## Technical Requirements and Grading Rubric
 - Keep your code linted, as you work. Clean up all concerns before submitting.
 - Write your SQL queries inside the quotes found near the TODOs
 
