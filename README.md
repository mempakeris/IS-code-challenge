# Hiring Assessment for Prospective Engineering Candidates
Thank you for taking the time to complete the Indigo Slate Engineering Team's full stack assessment!
Feel free to spend as much or as little time as you'd like. This assessment is designed to take approximately 6 hours.

## Data API
**You should not create your own data tier for this project.** A data storage api has been provided for you, please reference this [api documentation](api-doc/data-tier.md). \
\
**API_KEY is required**: If you do not already have an API key, please reach out to your contact at Indigo Slate to receive one.

# Assessment Scenario
An Indigo Slate client is hosting a three-day conference. The client is working with several vendors who will be scheduling presentations, panels, and interactive demos for the event. Indigo Slate has been tasked with creating a planning and scheduling app for the client. The app needs to consume the provided data API to house all of the data.

## Task
Build the event management application for this client. The client wants to be able to configure events by using an admin panel where events can be added, removed, updated and read from a schedule.
* **Create an Event API back-end**, providing endpoints for data manipulation for the view.
    * This API will be separate from the data storage api provided.
* **Utilize the provided CRUD storage API as the data tier** for the Event API backend. ([api documentation](api-doc/data-tier.md))
    * Hint: Depending on how you structure your data, you may not need to use all of the provided endpoints!
* Events should **not** overlap.
* The schedule should span across 3 days.
* Authenticate the Admin View to the Event API using Basic Authentication (Only a single set of credentials is necessary).
* We've provided a barebones front-end to help you get started. Feel free to adjust as necessary.
    * Hint: The front-end we've provided is pretty bland...

## Notes/Hints
* Carefully consider the problem before you code!
* There are many different ways to solve this problem. No one way is the best.
* There are multiple ways to store the data needed. The endpoints of the data api are available for your use. You need not use all routes if you don't want to.
* The front-end view is provided for ease, please don't feel restricted to the constraints that the current front-end has. If you don't like it, change it!
* Consider this project to be 70% back-end, 30% front-end. We'd like to see your skills in both.
* You are limited to the data api provided. Please do not create any additional data tiers.
* If you can't complete the problem, please submit what you have.
* Once you've completed the project, upload it to your github account and then submit your work:
    * Note that once submitted, your API_KEY will be invalidated, please ensure you've thoroughly tested your work prior to submitting.
    * **Submission URL**: [https://crud-api.azurewebsites.net]

**If you have any additional questions about the application please reach out to your recruiter.**


# Front-end framework (this repository)

## Project setup
* Clone this repository
* Install dependencies
```
npm install
```
### Getting Started
```
// serve for development
npm run serve

// Compiles and minifies for production
npm run build
```
