# Progressive-Budget
# Unit 18 PWA Homework: Online/Offline Budget Trackers

Add functionality to our existing Budget Tracker application to allow for offline access and functionality.

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.


## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.

- - -

## Commit Early and Often

* One of the most important skills to master as a web developer is version control. Building the habit of committing via Git is important for two reasons:

1. Your commit history is a signal to employers that you are actively working on projects and learning new skills

2. Your commit history allows you to revert your code base in the event that you need to return to a previous state

* Follow these guidelines for committing:

  * Make single purpose commits for related changes to ensure a clean, manageable history. If you are fixing two issues, make two commits

  * Write descriptive, meaningful commit messages so that you and anyone else looking at your repository can easily understand its history

  * Don't commit half done work, for the sake of your collaborators (and your future self!)

  * Test your application before you commit to ensure functionality at every step in the development process

* We would like you to have well over 200 commits by graduation, so commit early and often!

* Deploy your application with [Heroku and MongoDB Atlas.](../04-Important/MongoAtlas-Deploy.md)

## Submission on BCS

* You are required to submit the following:

  * the URL to the deployed application

  * the URL to the Github repository

- - -

## Hint

* In order to cache dynamic content, i.e. users' inputs for withdrawals or deposits, incorporate `indexedDB` from the previous module.

* Use [Google](https://www.google.com) or another search engine to research this topic.








 
## Motivation
The motivation behind this project was to allow for us to make a working fitness appliation using the MVC model as well as new technologies such as Mongod, Mongodb and seeting up back end code for pre-build front end code, we learned in unit 18 of the UT coding Bootcamp.
## Build status
Build status of continous integration 

## Code style
Standard
 
## Screenshots

## Tech/framework used
Uses Mongo, Momgodb,MongoAtlas, Heroku, as well as Javascript.

## Features
Features include dashboard that allows for new and previous workouts. 

## Code Example
Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Installation
1. Npm install.
2. Install dev dependencies.
3. Create workout schema.
4. Create html routes.
5. Test run in local host server.
6. Npm run start. 
7. Deploy to heroku.



## API Reference
None

## Tests
Run tests using npm run start and npm seed to see if the database information has been seeded and check for errors in the server. 


## Credits
Github repo: https://github.com/amcourson/FitnessTracker
Project creation credit belongs to UT Austin Coding Bootcamp. 


## License
 MIT

MIT © [amcourson]()