# hello-jest-github-actions

on `commit`:  
![example workflow](https://github.com/github/docs/actions/workflows/main.yml/badge.svg)

on `push`:  
![Jest](https://github.com/siljeangelvik/hello-jest-github-actions/actions/workflows/jest.yml/badge.svg)

on `pull_request`:  
![Cypress](https://github.com/siljeangelvik/hello-jest-github-actions/actions/workflows/cypress.yml/badge.svg)


Forked GitHub repository from [NoroffFEU/social-media-client](https://github.com/NoroffFEU/social-media-client).  
Cloned GitHub repository.  
Created new branch: `workflow`  
- command: `git checkout -b main`  
Made new file: `README.md`  
Push new local branch: `workflow` to remote repository    
- command: `git push -u origin main`  
Create new branch: `setup-prettier-eslint`  
- command: `git checkout -b setup-prettier-eslint`  


Set up Prettier (manually):
Set up ESLint (manually):


Create new branch: `setup-jest-cypress`  

Set up Jest (manually):  
`npm install jest -D`  
`mkdir -p src/__test__/math.test.js .github/workflows/`  
`touch src/math.js src/__test__/math.test.js .github/workflows/jest.yml`  
`npm test`  
_Commit changes_
   
Set up Cypress (manually):  
`npm install -D cypress`   
`touch cypress.config.js`  
`mkdir -p cypress/e2e cypress/support`  
`touch cypress/e2e/flask.cy.js cypress/support/e2e.js cypress/support/commands.js`  
_Commit changes_



##Resources:  
**Course Assignment:** [Workflow](https://noroff-content.gitlab.io/feu/workflow/ca.html)
**Course Asignment:** [social-media-client](https://github.com/NoroffFEU/social-media-client)

* [Workflow Status Badges](https://docs.github.com/en/actions/monitoring-and-troubleshooting-workflows/adding-a-workflow-status-badge)
* [Cypress Docs](https://docs.cypress.io/guides/overview/why-cypress)

###Tools  
**Bundler:** Vite / Webpack
**Formatter:** Prettier
**Linting:** ESLint
**Unit Tester:** Jest / Cypress
**E2E Tester:** Cypress

