# Sky - Find & Watch Team - Unattended Test

The Find & Watch team at Sky are pleased to send you this unattended test. This means we think your CV is pretty good so we want to see if your approach to work is the same as ours. 
Our team is very Agile and TDD oriented so we believe a few lines of great code speak more than endless CV pages! 
We’d like you to use this test to show us how awesome you are at what you do.

## Pre-Interview Developer Test

Please clone this repository before commencing development. Once complete please provide a link to your repository. We’d like to understand your approach as well as how great your work is, so please don’t simply commit all of your work in a single chunk.

![alt text](https://github.com/sky-guide/angular-node-test/blob/master/it-compiles.png "It Compiles!")


Your solution will be evaluated on implementation of the below requirements, code maintainability, code clarity, and software development best practices. We would urge you to treat this like a mini-project and follow whatever Agile/TDD/BDD/etc approach you would use on any other project.
Once reviewed, we will ask you to delete (or make private) your repository once we have reviewed your code.

## Requirements

Create an angular app which allows a user to enter a username and password and authenticate. Successful authentication should provide the user with a logged-in page and the ability to log out.

Create a NodeJS app which provides an authentication API to your angular app. The usernames 'user', 'manager', 'admin', 'developer', 'tester', with the password 'password' should be authenticated. All other combinations should fail. Eg, username 'john.smith' can never authenticate. 

Usernames should be case-insensitive, passwords should be case-sensitive.

Authentication attempts should be recorded (preferably in a Mongo database, although any other persistence of your choice is acceptable), with the following data:
  *	IP
  *	Datetime (unix timestamp format)
  *	Action (should be one of AUTH_SUCCESS or AUTH_FAILURE)
  *	Username

Expose a JSON feed of the authentication data to authenticated admin users only.


Good luck!

Find & Watch dev team
