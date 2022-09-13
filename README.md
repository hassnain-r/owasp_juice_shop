## Installations

- Clone repo
- Open New Terminal
- Go to project directory
- Execute following command to install project dependencies
-     npm install
-     open file from path owasp_automation/cypress.env.json and pass valid email id and password value

- Execute following command to open cypress dashboard

      npx cypress open
###

- you can click test case on dashboard it will start executing

#

- Execute following command to run all cases as headless it will generate a html report as well as the videos

      npm test


## basic Setup for reporting  

- Execute following command to install reporting dependencies

     - npm install mocha  
     - npm install mochawesome
     - npm install mochawesome-merge
     - npm install mochawesome-report-generator

## Api Integration test are covered using both Cypress and Postman

- In order to run api integration cases just use cypress dashboard 
- In order to run api integration cases using postman you need to perform below steps

  - Unzip the file, you will get a folder having collection and env, import the folder in postman
  - choose the only environment and run collection
  - I am attaching a video as well for assistance
  

Note: For now I am not adding cypress.env.json to .gitignore, but we can do that  