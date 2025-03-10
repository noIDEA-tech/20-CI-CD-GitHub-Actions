# GitHub Actions CI/CD Setup

![MIT](https://img.shields.io/badge/License-MIT-blue)

## Website Links: 
- [GitHub-website](https://github.com/noIDEA-tech/20-CI-CD-GitHub-Actions)
- [Deployed-website](https://two0-ci-cd-github-actions.onrender.com)


## Description
This web application is an interactive Tech Quiz designed to allow users to test their knowledge of Python language and syntax by answering a series of questions when prompted to begin by clicking the "start quiz" button. Once the user has completed the series of questions, they are given their test score result and have the option to take another quiz or exit out of the website by closing it. This project also demonstrates how to create a CI/CD pipeline using GitHub Actions and utilizing the workflow process with feature branches → develop (with tests) → main (with deployment). It also demonstrates using automated Cypress components testing on Pull Requests to develop branch as well as automated deployment to Render when code is merged from the develop branch to the main GitHub branch.

![app_image](/client/assets/images/image-start-quiz.png)
![app_image](/client/assets/images/image-quiz-question.png)
![app_image](/client/assets/images/image-quiz-score.png)
![app_image](/client/assets/images/image-test-results.png)

## Table of Contents:
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies-Used](#technologies-used)
- [Tests](#tests)
- [Credits](#credits)
- [License](#license)
- [Contact](#contact)

## Installation:
- In root directory, run: 
    -  `npm run install`
    - cd server `npm run build` && `npm run seed`
    - cd .. cd client `npm run build`
   
## Usage:
- In root directory, run:
    -  `npm run develop` (to start both client and server in development mode)

## Features:
1. User-facing features:  
    - Users can take a tech quiz to test their Python knowledge
    - Users can start a new quiz with the click of a button
    - Users receive immediate feedback as they progress through questions
    - Users can see their final score after completing the quiz
    - Users can take a new quiz after completing one

2. CI/CD Pipeline Features:
    - Automated Cypress component testing on Pull Requests to develop branch
    - Automated deployment to Render when code is merged to main
    - GitHub Secrets management for secure deployment

## Technologies Used:
- Frontend: React, Bootstrap
- Backend: Node.js, Express, MongoDB
- Testing: Cypress for component testing
- CI/CD: GitHub Actions
- Deployment: Render

## Tests:
- To run component test in root directory, run: 
    - `npm run test-component`

- To view test results in Cypress UI, in root directory, run:
    - `npm run test-gui`

## Credits: 
- Nancy Watreas
- Assistance with Cypress test implementation was provided by Anthropic. (2025). Claude.ai [AI Assistant]. Retrieved from https://claude.ai

## License
MIT

## Contact:
If there are any questions or concerns, I can be reached at:
##### [github: noIDEA-tech](https://github.com/noIDEA-tech)
##### [email: nwatreas2023@gmail.com](mailto:nwatreas2023@gmail.com)
