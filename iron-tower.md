# Iron Tower

## Description

Iron Tower will be a web-based where the user builds a tower, floor by floor.
Each floor once built can be either businesses (restaurants, shopping outlets, etc) or apartments.
Apartments allow for certain numbers of residents which have to be available to work at businesses.
Each business generates income over time based on the type of floor it is (the time and payout vary and increase for each floor higher you go). You may theme this game as you like and can vary the balancing (residents allowed in apartments, time to payout, etc).

### Deliverables

* Trello Board including user stories, requirements, wireframes, etc..
* A repository posted to GitHub that contains both client and server files.
* Both sides of the project served using Microsoft Azure
    * SQL Server Database for storage
    * A .NET MVC application
    * A static website application

### Requirements

* User should have a cash balance
* User should be able to purchase floors
* User should receive cash based on floor income over time
* User should be able to create apartments which allow residents
* Residents should show up over time
* User should not be able to build new businesses without unemployed residents
* Developers should be able to configure game balancing with easy to get to variables

## Resources and Libraries (Suggested not required)

* [Hangfire (Timed jobs in .NET)](http://hangfire.io/)
* [Angular $interval](https://docs.angularjs.org/api/ng/service/$interval)
* [Bootstrap](http://www.getbootstrap.com)
* [Font Awesome](http://fortawesome.github.io/Font-Awesome/)
