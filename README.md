# Intro to CI/CD with Node.js

This project demonstrates how to set up a simple Node.js application with **Continuous Integration (CI)** and **Continuous Deployment (CD)** using GitHub Actions and Render.  
It covers the full workflow: initializing a repo, writing code, automating tests, and deploying to production.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Screenshots & Explanations](#screenshots--explanations)
- [Lessons Learned](#lessons-learned)

---

## Project Overview

This project is a basic Node.js app designed to help you learn and practice CI/CD concepts.  
You’ll see how to automate testing and deployment, ensuring your code is always production-ready.

---

## Screenshots & Explanations

![1](./img/1.%20git%20repo.jpg)  
*Created a new GitHub repository to host the project code.*

![2](./img/2.%20git%20clone.jpg)  
*Cloned the repository to the local machine for development.*

![1](./img/3.%20git%20init.jpg)  
*Initialized the project with npm to create a package.json file.*

![1](./img/4.%20git%20install%20express.jpg)  
*Installed Express.js, the web framework for the Node.js app.*

![1](./img/5.%20script.jpg)  
*Added scripts to package.json for starting and testing the app.*

![1](./img/6.%20next.jpg)  
*Outlined the next steps for project setup and development.*

![1](./img/7.%20commit.jpg)  
*Committed the initial project files to version control.*

![1](./img/8.%20mkdir.jpg)  
*Created necessary directories for organizing the project.*

![1](./img/9.%20script.jpg)  
*Updated or added more scripts to package.json as needed.*

![1](./img/10.%20commit.jpg)  
*Committed further changes after updating scripts or structure.*

![1](./img/11.%20push.jpg)  
*Pushed all local commits to the remote GitHub repository.*

![1](./img/12.%20fail.jpg)  
*First GitHub Actions CI run failed, indicating issues to fix.*

![1](./img/13.%20rectify.jpg)  
*Started troubleshooting and fixing the CI/CD pipeline errors.*

![1](./img/14.%20error%202.jpg)  
*Encountered another error in the workflow, requiring more fixes.*

![1](./img/15.%20solution.jpg)  
*Applied solutions to resolve the errors in the workflow.*

![1](./img/16.%20push%20again.jpg)  
*Pushed the fixes to GitHub to trigger another CI/CD run.*

![1](./img/17.%20ERROR%203.jpg)  
*Faced a new error during the CI/CD process.*

![1](./img/18.%20SOLUTION%203.jpg)  
*Identified and implemented the solution for the latest error.*

![1](./img/19.%20successful.jpg)  
*Achieved a successful CI run after resolving all errors.*

![1](./img/20.%20automation.jpg)  
*CI/CD pipeline is now automated and working as expected.*

![1](./img/21.%20index%20test.jpg)  
*Added a Jest test file to enable automated testing.*

![1](./img/22.%20push.jpg)  
*Pushed the test file and related changes to GitHub.*

![1](./img/23.%20successsss.jpg)  
*CI/CD pipeline successfully ran the tests and passed.*

![1](./img/24.%20render.jpg)  
*Set up deployment to Render, a free Node.js hosting platform.*

![1](./img/25.%20deployment%20error.jpg)  
*Encountered a deployment error due to a missing or incorrect start script.*

![1](./img/26.%20fixed%20script.jpg)  
*Fixed the start script in package.json to resolve the deployment issue.*

![1](./img/27.%20push%20again.jpg)  
*Pushed the corrected package.json to trigger a new deployment.*

![1](./img/28.%20successssful.jpg)  
*Deployment to Render was successful after fixing the script.*

![1](./img/29.%20deployed.jpg)  
*The app is now live and deployed on Render.*

![1](./img/30.%20hello%20world.jpg)  
*Accessed the deployed app in the browser, confirming it works ("Hello World").*

---

## Lessons Learned

- How to set up a Node.js project with version control.
- How to automate testing and deployment using GitHub Actions.
- How to troubleshoot common CI/CD and deployment errors.
- How to deploy a Node.js app for free using Render.
- The importance of clear scripts and configuration for automation.

---




