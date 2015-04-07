Programming Exercise: Address Book
---
## Instructions for running the web application
There is nothing different you must do to run the web application. Simply execute "node server.js" 
and everything should work. 

## Changes/Additional features
Things changed:
- added fields in the JSON file for extra info and testing
- added a search box with an error alert if the name was not found
- added forwards and backwards search methods
- rendered profile pics via URL and images "on file"
- added a simple instruction text at the top of the screen 

There were many things I could have added, such as an auto-complete drop-down list for the search box,
making the search input case-insensitive, sorting the names in reverse solely by each letter's heading, 
adding functionality to open your default email with the clicked person's email address in the recipient's text 
field, etc, but being swamped with current projects at work, I left it fairly simple. 


## Setup
1. Install NodeJS
2. Install Dependencies
```bash
npm install
```

## Run Server
```bash
node server.js
```

## URL Endpoints
**Mockup:**
http://localhost:8080/mockup/

**People Data:**
http://localhost:8080/api/people

## Goals
- Fork this repo
- Create a simple address book web application and use the given static
  HTML mockup (`mockup/index.html`) as a starting point or as inspiration.
- Your web application should fetch people data from http://localhost:8080/api/people
- Renders the names of all people from the people data in the left panel
  in alphabetical order.
- When a person's name is clicked in the left panel, render the full profile in the right panel.
- Update the `README.md` with any instructions for running the web application.

### Bonus Points
- Add image URLs to the people data and render these photos in the profile
- Make it possible to change sort order of people shown in directory panel

### Additional Notes
- Feel free to use any framework or library (or use vanilla JavaScript)
- Feel free to modify `data/people.json` with any changes that you see fit.
- Feel free to add additional routes to the express app by modifying `server.js`
- Your address book does not need to use the exact same CSS or HTML as provided
  by the mockup.
