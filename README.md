# cypress-cucumber-saucedemo
saucedemo.com test automation with Cypress 10+ and Cucumber

## Prerequisites
- NodeJS `https://nodejs.org/en/download` 
- Cypress `npm install cypress --save-dev`

## Project Folder Structure

```
📦 cypress-cucumber-saucedemo
├─ cypress
│  ├─ e2e
│  │  └─ features --> Scenarios
│  ├─ plugins
│  │  └─ index.js  --> cypress plugins ( e.g Cucumber )
│  └─ support
│     ├─ pages --> Javascript Methods
│     ├─ steps --> Step Definations
│     └─ command.js --> Helper Methods
├─ cypress.config.js --> Contains cypress configuration
└─ package.json --> Contains the project's dependencies, commands and other project information.
```


## Run

- Without Allure-Reports :  `npx cypress run`
- With Allure-Reports : `npx cypress run --env allure=true`

Or you can run with Cypress GUI `npx cypress open`
