# Welcome to the Integrating With HubSpot I: Foundations Practicum

This repository is for the Integrating With HubSpot I: Foundations course. This practicum is one of two requirements for receiving your Integrating With HubSpot I: Foundations certification. You must also take the exam and receive a passing grade (at least 75%).

To read the full directions, please go to the [practicum instructions](https://app.hubspot.com/academy/l/tracks/1092124/1093824/5493?language=en).

**HubSpot developer test account: Vessel custom object list view:**
https://app-eu1.hubspot.com/contacts/149396932/objects/2-253796869/views/all/list


## Justen van Eck: What this does
Small Express app for the Integrating with HubSpot I: Foundations practicum.
- 'GET /' lists Vessel (custom HubSpot Object) records via the CRM v3 Objects API
- 'GET /update-cobj' is the form to add a new vessel
- 'POST /update-cobj' create the new record in HubSpot and redirect back home

## To run this locally:
1. Run `npm install`
2. Create `.env` with `PRIVATE_APP_ACCESS=<private app token>` and `CUSTOM_OBJECT_TYPE=<object id>`
3. Run `node index.js` → http://localhost:3030 (port can be changed in the index.js file)


___
## Tips:
- Commit to your repository often. Even if you make small tweaks to your code, it’s best to be committing to your repository frequently.
- The subject of the custom object is up to you. Feel free to get creative!
- Please create a test account and include your private app access token in your repo.
- Ensure you re-merge any working branches into the main branch.
- DO NOT ADD YOUR PRIVATE APP TOKEN TO YOUR REPOSITORY. 

## Pre-requisites:
- Using [Node](https://nodejs.org/en/download) and node packages
- Using [Express](https://expressjs.com/en/starter/installing.html)
- Using [Axios](https://axios-http.com/docs/intro)
- Using [Pug templating system](https://pugjs.org/api/getting-started.html)
- Using the command line
- Using [Git and GitHub](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)

## Requirements
- All work must be your own. During the grading process we will check the revision history. Submissions that do not meet this requirement will not be considered.
- You must have at least two new routes in your index.js file and one new pug template for the homepage.
- You must create a developer test account and link to it in your README.md file. Submissions that do not meet this requirement will not be considered.
