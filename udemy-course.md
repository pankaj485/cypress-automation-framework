# Udemy Cypress Learning

This note is a summary of the Udemy [course](https://www.udemy.com/course/cypress-io-master-class/) on cypress

- The course has 66 sections

- Cypress [website](https://www.cypress.io/)

[cypress community ](https://www.notion.so/cypress-community-2343862ee4004516ac1b9a0aa12f96dc)

[Cypress Documentation](https://www.notion.so/Cypress-Documentation-2a80ad42115742038fdaac0514551a16)

`date: Wed, 27 oct 2021`

<!-- TOC -->

- [Udemy Cypress Learning](#udemy-cypress-learning)
- [Section 1: Cypress Introduction](#section-1-cypress-introduction)
  - [1. What is Cypress](#1-what-is-cypress)
  - [2. Why learn Cypress?](#2-why-learn-cypress)
  - [3. How does Cypress work?](#3-how-does-cypress-work)
  - [3. What are the Key differences between Cypress and other automation Tools?](#3-what-are-the-key-differences-between-cypress-and-other-automation-tools)
  - [5. Want to dive deeper into Cypress Code?](#5-want-to-dive-deeper-into-cypress-code)
  - [6. Cypress Demo](#6-cypress-demo)
  - [7. Cypress Chat](#7-cypress-chat)
- [Section 2: Future course and cypress updates](#section-2-future-course-and-cypress-updates)
  - [8. Future course and cypress updates](#8-future-course-and-cypress-updates)
- [Section 3: Environment Setup](#section-3-environment-setup)
  - [9. Chrome and Firefox browser Installation](#9-chrome-and-firefox-browser-installation)
  - [10. Prerequisites Node Js setup](#10-prerequisites-node-js-setup)
  - [11. Node Js setup](#11-node-js-setup)
  - [12. Gitbash setup](#12-gitbash-setup)
  - [13. VS Code Installation and Configuration](#13-vs-code-installation-and-configuration)
- [Section 4: Cypress Setup](#section-4-cypress-setup)
  - [15. Cypress Installation & Setup](#15-cypress-installation--setup)
  - [16. NPM installation and update](#16-npm-installation-and-update)
- [Section 5: Cypress Overview](#section-5-cypress-overview)
  - [17. Opening Cypress for the first time](#17-opening-cypress-for-the-first-time)
  - [19. Cypress Test Runner](#19-cypress-test-runner)
  - [20. Cypress Project Structure](#20-cypress-project-structure)
- [Section 6: Cyrpess Updates](#section-6-cyrpess-updates)
  - [21. Keeping cypress up to date](#21-keeping-cypress-up-to-date)
- [Section 7: Cypress API](#section-7-cypress-api)
  - [22. Cypress API](#22-cypress-api)
- [Section 8: Cypress Updates - (Change Logs)](#section-8-cypress-updates---change-logs)
  - [23. Cypress Updates (Change Logs)](#23-cypress-updates-change-logs)
- [Section 9: The Real Project Examples](#section-9-the-real-project-examples)
  - [24. Systems Under Test](#24-systems-under-test)
- [Section 10: Mocha](#section-10-mocha)
  - [26. Constructing Our first test using mocha](#26-constructing-our-first-test-using-mocha)
- [Section 11: Basic Cypress Commands](#section-11-basic-cypress-commands)
  - [27. Command Activation & Inspecting Specific Cypress Commands](#27-command-activation--inspecting-specific-cypress-commands)
  - [28. Visit and click command](#28-visit-and-click-command)
  - [29. Click options](#29-click-options)
  - [30. Type Command](#30-type-command)
- [Section 12: Creating Our First Test (The Challenge)](#section-12-creating-our-first-test-the-challenge)
  - [31. Challenge overview](#31-challenge-overview)
  - [33. Creating Our Second Cypress Test (Negative Test Case)](#33-creating-our-second-cypress-test-negative-test-case)
  - [34. Targeting individual Tests via Mocha](#34-targeting-individual-tests-via-mocha)
- [Section 13: Running Tests in Chrome, Electron & Firefox](#section-13-running-tests-in-chrome-electron--firefox)
  - [35. Running Tests in Chrome, Electron & Firefox](#35-running-tests-in-chrome-electron--firefox)
- [Section 14: Web Elements & Selectors](#section-14-web-elements--selectors)
  - [36. Why do we need Selectors?](#36-why-do-we-need-selectors)
  - [37. Document Object Model (DOM) & Elements](#37-document-object-model-dom--elements)
  - [38. Practical In Depth Look into selectors Part 1/2](#38-practical-in-depth-look-into-selectors-part-12)
  - [39. Practical In Depth Look into selectors Part 2/2](#39-practical-in-depth-look-into-selectors-part-22)
  - [40. Selector Generator Tools](#40-selector-generator-tools)
  - [41. CSS Selector](#41-css-selector)
  - [42. Xpath Selectors Part 1/3](#42-xpath-selectors-part-13)
  - [43. Xpath Selectors Part 2/3](#43-xpath-selectors-part-23)
  - [44. Xpath Selectors Part 2/3](#44-xpath-selectors-part-23)
  - [45. Improving Our Tests with Dynamic Selectors](#45-improving-our-tests-with-dynamic-selectors)
  - [46. More selector examples](#46-more-selector-examples)
- [Section 15: Assertions](#section-15-assertions)
  - [48. Why Do We Need Assertions?](#48-why-do-we-need-assertions)
  - [49. Chai Assertions & Cypress examples](#49-chai-assertions--cypress-examples)
  - [50. Adding Assertions to our existing Tests](#50-adding-assertions-to-our-existing-tests)
  - [51. Chai JQurey](#51-chai-jqurey)
  - [54. Cypress Contains](#54-cypress-contains)
- [Section 16: Referencing Windows](#section-16-referencing-windows)
  - [55. cy.document()](#55-cydocument)
  - [56. cy.title()](#56-cytitle)
  - [57. cy.url()](#57-cyurl)
- [Section 17: Triggering Tests via Command line](#section-17-triggering-tests-via-command-line)
  - [58. Headless Electron Browser](#58-headless-electron-browser)
  - [58. Non Headless Electron Browser](#58-non-headless-electron-browser)
  - [60. Non-Headless Chrome Browser](#60-non-headless-chrome-browser)
  - [61. Trigger Individual Tests](#61-trigger-individual-tests)
- [Section 18: Cypress Chaining Commands](#section-18-cypress-chaining-commands)
  - [62. Cypress Chaining Commands - Introduction](#62-cypress-chaining-commands---introduction)
  - [63. More Examples of Command Chaining -get, find, contains, eq - Part 1/2](#63-more-examples-of-command-chaining--get-find-contains-eq---part-12)
  - [64. More Examples of Command Chaining -get, find, contains, eq - Part 2/2](#64-more-examples-of-command-chaining--get-find-contains-eq---part-22)
- [Section 19: Synchronous vs Asynchronous](#section-19-synchronous-vs-asynchronous)
  - [65. Synchronous vs Asynchronous Overview](#65-synchronous-vs-asynchronous-overview)
  - [66. Synchronous Example](#66-synchronous-example)
  - [67. Asynchronous Example](#67-asynchronous-example)
  - [68. Cypress Asynchronous Nature](#68-cypress-asynchronous-nature)
- [Section 20: Logging - Practical Asynchronous JS Example](#section-20-logging---practical-asynchronous-js-example)
  - [69. Non Cypress Commands and Async Nature](#69-non-cypress-commands-and-async-nature)
  - [70. Cypress Log](#70-cypress-log)
- [Section 21: Promises and the Then Command](#section-21-promises-and-the-then-command)
  - [71. Promises Real World Example](#71-promises-real-world-example)
  - [72. Promises and Cypress](#72-promises-and-cypress)
  - [73. then command](#73-then-command)
- [Section 22: Variables](#section-22-variables)
  - [76. Variables - Part 1/4](#76-variables---part-14)
  - [77. Variables - Part 2/4](#77-variables---part-24)
  - [78. Variables - Part 3/4](#78-variables---part-34)
  - [79. Variables - Part 4/4](#79-variables---part-44)
  - [80. Variables, Promises & Nested Closures Part 1/2](#80-variables-promises--nested-closures-part-12)
  - [81. Variables, Promises & Nested Closures Part 2/2](#81-variables-promises--nested-closures-part-22)
- [Section 23: Iterating Through Elements](#section-23-iterating-through-elements)
  - [82. Iterating Through Elements- Documentation & preparation](#82-iterating-through-elements--documentation--preparation)
  - [83. Practical Example of Iterating Through Elements part 1/2](#83-practical-example-of-iterating-through-elements-part-12)
  - [84. Practical Example of Iterating Through Elements part 1/2](#84-practical-example-of-iterating-through-elements-part-12)
- [Section 24: Alias & Invoke](#section-24-alias--invoke)
  - [85. Alias & Invoke - Documentation](#85-alias--invoke---documentation)
  - [86. Alias & Invoke - Practical example](#86-alias--invoke---practical-example)
- [Section 26: Cypress Limitations](#section-26-cypress-limitations)
  - [94. Cypress Limitations](#94-cypress-limitations)
- [Section 27: Recipies](#section-27-recipies)
  - [95. Cypress Recipies](#95-cypress-recipies)
- [Section 28: Child Windows](#section-28-child-windows)
  - [96. Handling Multiple Browser Tabs](#96-handling-multiple-browser-tabs)
- [Section 29: Same Origin Policy](#section-29-same-origin-policy)
  - [97. Same Origin Policy - Example 1/2](#97-same-origin-policy---example-12)
  - [98. Same Origin Policy - Example 1/2](#98-same-origin-policy---example-12)
- [Section 30: Browser Navigation](#section-30-browser-navigation)
  - [99. Back, Forward, Reload - Part 1/2](#99-back-forward-reload---part-12)
  - [100. Back, Forward, Reload - Part 2/2](#100-back-forward-reload---part-22)
- [Section 31: Handling Alerts](#section-31-handling-alerts)
  - [103. Handling Alerts - Documentation](#103-handling-alerts---documentation)
  - [104. Handling Alerts - Example 1/2](#104-handling-alerts---example-12)
  - [105. Handling Alerts - Example 2/2](#105-handling-alerts---example-22)
  - [108. Handling Alerts with Stubs](#108-handling-alerts-with-stubs)
- [Section 32: Handling Iframes's](#section-32-handling-iframess)
  - [109. Handling Iframes's Part 1/2](#109-handling-iframess-part-12)
- [Section 33: Handling Checkboxes](#section-33-handling-checkboxes)
  - [111. Handling checkboxes part 1/2](#111-handling-checkboxes-part-12)
  - [Selecting Multiple checkboxes](#selecting-multiple-checkboxes)
- [Section 34: Handling Radio Buttons](#section-34-handling-radio-buttons)
  - [116. Handling - Radio Buttons](#116-handling---radio-buttons)
  - [117. Validating States of Radio Buttons (checked and unchecked)](#117-validating-states-of-radio-buttons-checked-and-unchecked)
- [Section 35: Handling Drop-down Lists](#section-35-handling-drop-down-lists)
  - [118. Handling Drop-down Lists 1/2](#118-handling-drop-down-lists-12)
  - [118. Handling Drop-down Lists 2/2](#118-handling-drop-down-lists-22)
- [Section 36: Autocomplete (Suggested) Lists](#section-36-autocomplete-suggested-lists)
  - [122. Handling Autocomplete Lists - Part 1/2](#122-handling-autocomplete-lists---part-12)
  - [123. Handling Autocomplete Lists - Part 2/2](#123-handling-autocomplete-lists---part-22)
- [Section 37: Mouse Actions](#section-37-mouse-actions)
  - [127. Scroll into view](#127-scroll-into-view)
  - [128. Drag and Drop](#128-drag-and-drop)
  - [129. Double Click](#129-double-click)
  - [130. Click, Hold & Assertions](#130-click-hold--assertions)
- [Section 38: Traversal](#section-38-traversal)
  - [131. Traversal Prepration](#131-traversal-prepration)
  - [132. children()](#132-children)
  - [133. closest()](#133-closest)
  - [134. eq()](#134-eq)
  - [135. filter()](#135-filter)
  - [136. find()](#136-find)
  - [137. first()](#137-first)
  - [138. last()](#138-last)
  - [139. nextAll()](#139-nextall)
  - [140. nextUntil()](#140-nextuntil)
  - [141. not()](#141-not)
  - [142. parent()](#142-parent)
  - [143. parents()](#143-parents)
  - [144. prev()](#144-prev)
  - [145. prevAll()](#145-prevall)
  - [146. prevUntil()](#146-prevuntil)
  - [147. siblings()](#147-siblings)
- [Section 39: Handling Data from Tables](#section-39-handling-data-from-tables)
  - [148. Handling Data - Example 1 - Part 1/3](#148-handling-data---example-1---part-13)
  - [151. Handling Data - Example 2 - Part 1/3](#151-handling-data---example-2---part-13)
- [Section 40: Handling Date Pickers](#section-40-handling-date-pickers)
  - [153. Handling Date Pickers - Part 1/5](#153-handling-date-pickers---part-15)
  - [156. Handling Date pickers - Part 4/5](#156-handling-date-pickers---part-45)
- [Section 41: File Upload](#section-41-file-upload)
  - [158. Introduction and preparation](#158-introduction-and-preparation)
  - [160. Uploading no File(s)](#160-uploading-no-files)
- [Section 42: Hooks](#section-42-hooks)
  - [161. Hooks - Documentation & Practical Example](#161-hooks---documentation--practical-example)
- [43: Fixtures](#43-fixtures)
  - [165. Fixtures - Documentation](#165-fixtures---documentation)
  - [168. Alias and Fixtures](#168-alias-and-fixtures)
- [Section 44: Custom Commands](#section-44-custom-commands)
  - [169. Custom Commands - Documentation & Practical Example - Part 1/2](#169-custom-commands---documentation--practical-example---part-12)
- [Section 45: Custom Commands & Fixtures - Wrap Up](#section-45-custom-commands--fixtures---wrap-up)
  - [175. Custom Commands and fixtures - Wrap Up - Part 1/3](#175-custom-commands-and-fixtures---wrap-up---part-13)
- [Section 46: Overriding Default Settings](#section-46-overriding-default-settings)
  - [178. cypress.config](#178-cypressconfig)
  - [179. Ignore files](#179-ignore-files)
- [Section 47: Environment & Global Variables](#section-47-environment--global-variables)
  - [180. Prerequisites](#180-prerequisites)
  - [181. Environment Variables](#181-environment-variables)
  - [182. Setting up a Base URL](#182-setting-up-a-base-url)
  - [183. Dynamic URL's](#183-dynamic-urls)
- [184. Dynamic URL's & custom commands: Example 1/2](#184-dynamic-urls--custom-commands-example-12)
  - [185. Dynamic URL's & custom commands: Example 2/2](#185-dynamic-urls--custom-commands-example-22)
- [Section 48: Page Object Modelling](#section-48-page-object-modelling)
- [Section 49: Configuring & Handling Timeouts](#section-49-configuring--handling-timeouts)
  - [192. URL Timeouts](#192-url-timeouts)
  - [193. Explicit Timeouts](#193-explicit-timeouts)
  - [194. Assertion Timeouts](#194-assertion-timeouts)
  - [195. Pause](#195-pause)
  - [196. Wait](#196-wait)
- [Section 50: Debugger](#section-50-debugger)
  - [197. Cypress Debugger](#197-cypress-debugger)
  - [Section 51: Screenshots and Debugger](#section-51-screenshots-and-debugger)
  - [199. Recording Videos](#199-recording-videos)
- [Section 52: Viewport - Altering Screen Sizes](#section-52-viewport---altering-screen-sizes)
  - [200. Altering Viewports - Configuring Size and Orientation](#200-altering-viewports---configuring-size-and-orientation)
- [Section 53: Cookies and Local Storage](#section-53-cookies-and-local-storage)
  - [201. Clearing Cookies & Local Storage](#201-clearing-cookies--local-storage)
- [Section 54: Cypress Dashboard](#section-54-cypress-dashboard)
  - [202. Cypress Dashboard - Practical Example Part 1](#202-cypress-dashboard---practical-example-part-1)
  - [203. Cypress Dashboard - Practical Example Part 2](#203-cypress-dashboard---practical-example-part-2)
- [Section 55: NPM scripts and NPX](#section-55-npm-scripts-and-npx)
  - [205. Npx](#205-npx)
  - [206. Npm scripts](#206-npm-scripts)
- [Section 56: Reporting](#section-56-reporting)
  - [208. JUnit Reporter](#208-junit-reporter)
  - [209. JUnit - Merging Reports](#209-junit---merging-reports)
  - [210. Npm scripts - Merge & Delete JUnit Reports](#210-npm-scripts---merge--delete-junit-reports)
  - [211. Mochawesome Reporter](#211-mochawesome-reporter)
  - [212. Mochawesome - Merging Reports](#212-mochawesome---merging-reports)
  - [213. Npm Scripts - Merge & Delete Mochawesome Reports](#213-npm-scripts---merge--delete-mochawesome-reports)
- [Section 57: Multiple Configuration Files](#section-57-multiple-configuration-files)
  - [215. Custom config File - Overview & creation](#215-custom-config-file---overview--creation)
  - [217. Injecting Custom config file logic into our Framework](#217-injecting-custom-config-file-logic-into-our-framework)
  - [218. Using custom config file settings during Runtime](#218-using-custom-config-file-settings-during-runtime)
- [Section 58: Cypress Retry](#section-58-cypress-retry)
  - [219. Adding Retry Logic to Framework](#219-adding-retry-logic-to-framework)
- [Section 59: Github -(source control)](#section-59-github--source-control)
  - [222. Github](#222-github)
  - [223. Visual Studio Code & Github Setup](#223-visual-studio-code--github-setup)
- [Section 60: Cross Browser Testing](#section-60-cross-browser-testing)
  - [229. NPM Scripts - Multi Browser Testing](#229-npm-scripts---multi-browser-testing)
  - [230. Configuring Code & Tests for specific Browsers](#230-configuring-code--tests-for-specific-browsers)
- [Section 61: Jenkins (CI) - Continuous Integration](#section-61-jenkins-ci---continuous-integration)
  - [231. Jenkins (CI) - Overview](#231-jenkins-ci---overview)
  - [234. Jenkins - Download & Setup](#234-jenkins---download--setup)

<!-- /TOC -->

# Section 1: Cypress Introduction

## 1. What is Cypress

- Cypress is modern day automation testing framework
- It has own custom commands to run tests
- It also gives additional debugging environment
- It takes snapshots as the test run, more features are mentioned in the [website](https://www.cypress.io/)
- It also has network traffic control
- Takes auto screenshots on failure or video of entire test when run headlessly

## 2. Why learn Cypress?

- It's constantly growing
- Is important for manual testers, automation testers and so on

## 3. How does Cypress work?

- Cypress wrap all the architecture into it's package and combines into one
- Key facts on Cypress
  - Cypress doesn't use Selenium
  - It's focused more on end to end testing
  - Can work on any frontend framework and website
  - It's for developers and QA engineers
  - It runs much faster
- All these are mentioned on cypress [website](https://www.cypress.io/)

## 3. What are the Key differences between Cypress and other automation Tools?

- Pros of cypress
  1. Easy to setup
  2. Quick and very stable
  3. Flake resistant
- Cons of cypress
  1. Must have JS experience
  2. No mobile testing
  3. Single domain and single tab

## 5. Want to dive deeper into Cypress Code?

- To explore cypress in depth go through their [github link](https://github.com/cypress-io)
- It includes projects as well and the projects are officially uploaded

## 6. Cypress Demo

- `integration` folder is the key place where all our testing files will be located
- All the testing will be executed within the cypress runner
- Before and after feature is also available to compare the states

## 7. Cypress Chat

- Cypress also has great [community](https://gitter.im/cypress-io/cypress)

# Section 2: Future course and cypress updates

## 8. Future course and cypress updates

- As cypress new version will be releasing new sections will be keep on adding to the course
- Course is incremental

# Section 3: Environment Setup

## 9. Chrome and Firefox browser Installation

- Make sure to install and update both chrome and firefox

## 10. Prerequisites Node Js setup

- Download and install node Js

## 11. Node Js setup

- Download and install node Js
- Check the installation of node js with `node -v` command

## 12. Gitbash setup

- Download and install git to use gitbash

## 13. VS Code Installation and Configuration

# Section 4: Cypress Setup

## 15. Cypress Installation & Setup

- To install the cypress version used in course run:
  ```
  npm install --save-dev cypress@8.4.1
  ```

## 16. NPM installation and update

# Section 5: Cypress Overview

## 17. Opening Cypress for the first time

- Inside `node_modules` there are various packages required to run cypress
- To open cypress:
  - method 1:
  ```
  ./node_modules/.bin/cypress open
  ```
  - method 2:
  ```
  npx cypress open
  ```
- Whenever cypress releases new version, new version installation will be asked for update
- To update cypress:
  ```
  npm install --save-dev cypress
  ```

## 19. Cypress Test Runner

- In the folder `INTTEGRATION TESTS` there includes all the testing files
- On installing by default it provides few demo test files as well as an example
- Click on any file listed to run the test
- Refer to cypress guides [documentation](https://docs.cypress.io/guides/overview/why-cypress) for more infos
- Each individual test is listed along with how many is passed and how many is failed along with the time taken
- Each test blocks has several details which is revealed on clicking the test block
- Cypress give handy tool which provides a way to click on the page and get the selector of that element of the website. Sometimes it's also not the optimized
- The website can also be inspected as well on the cypress runner. It also has before and after feature

## 20. Cypress Project Structure

- In the root project directory we will have following directory and file on starting cypress
  1. cypress
  2. node_modules
  3. cypress.json
  4. package-lock.json
  5. package.json
- Inside of cypress folder we will have following sub-directories
  1. fixtures
  2. integration
  3. plugins
  4. support
- `cypress.json` enables us to change the default options of the cypress. It's created in root folder of the project
- `support` directory has 2 files.
  - `index.js` is used to add additional infos, libraries, event-listeners e.t.c
  - `commands.js` is used to centralize the functions or commands. It is used to extract common logics and enabling reduced codes
- `plugins` directory has `index.js` file which is used to extend the functionality of the cypress by adding plugins
- `fixtures` directory is to store any test data which may be needed for the frameworks and can be fed while testing
- Summary
  - `node_module` is house of dependencies (packages)
  - `cypress.json` is created in project root directory, enables to change default settings
  - `screenshoots` is used to store images of specific tests
  - `support` is used to store custom commands and files
  - `index.js` is the first file which cypress investigates any imports, additional libraries, event listeners, changes to cypress default behavior, even ability to add hooks etc
  - `command.js` is used to store common/ custom commands, even the ability to override cypress functions
  - `plugins > index.js` is used to extend cypress functionalities, it's location where plugins can be added
  - `integration` is the main folder where test files are stored, cypress test runner will look into this folder to locate test files
  - `fixtures` is where we keep our test data objects, mocked objects and any other data which we need for tests. In most cases it's JSON files

# Section 6: Cyrpess Updates

## 21. Keeping cypress up to date

- On cypress test runner if we click on the version on the status bar present at the bottom of the runner it will give the version info and updates info
- Also it will provide the command for updating cypress
- O copying and pasting the command and running the command, it will update the cypress and downloads the updates

# Section 7: Cypress API

## 22. Cypress API

- Cypress API [link](https://docs.cypress.io/api/table-of-contents) includes various methods or commands we can use with cypress
- On clicking the specific methods, further detailed page to use the particular command or method along with it's detail

`date: Thr, 28 oct 2021`

# Section 8: Cypress Updates - (Change Logs)

## 23. Cypress Updates (Change Logs)

- When cypress releases new version, we can see the changes from the change logs from the docs
- On each new update the change logs can be visited in the official docs with respective [link](https://docs.cypress.io/guides/references/changelog)

# Section 9: The Real Project Examples

## 24. Systems Under Test

- The links available on the resources are two websites which will be used to test
- Both of them are going to be on use
  1. first site [link](https://www.webdriveruniversity.com/index.html)
  2. second site [link](https://www.automationteststore.com/)

# Section 10: Mocha

- Mocha is a JavaScript test framework for Node.js programs,
  featuring browser support, asynchronous testing, test coverage reports,
  and use of any assertion library
- It comes with pre bundled with two function calls which are `describe()` and `it()` both having their own specific purpose
- `describe()` is simply a way to group our tests in mocha. It allows to group series of tests together. It takes 2 arguments. First is the name of the test group and second is call-back function. (A call-back function is a function that is to be executed after another function has finished executing)
- `it()` is a way to describe each individual test case which is nested inside `describe()` block.
- Example:

  ```jsx
  describe("Test group tilte", ()=>{
  	it("Individual test case", ()=>{
  			cy.get('[name="first_name"]').type('Joe')
  	}

  	it("Individual test case", ()=>{
  			cy.get('[name="first_name"]').type('Joe')
  	}

  }
  ```

## 26. Constructing Our first test using mocha

- Video includes basic implementation of test files using mocha

# Section 11: Basic Cypress Commands

## 27. Command Activation & Inspecting Specific Cypress Commands

- To activate the cypress code and use it's all methods:
  ```jsx
  /// <reference types="cypress" />
  ```
- Typing `cy.` will give all of the available commands then

## 28. Visit and click command

- To visit any website:
  ```jsx
  cy.visit(url);
  ```
  - Example:
    ```jsx
    cy.visit("http://localhost:3000");
    cy.visit("/"); // visits the baseUrl
    cy.visit("index.html"); // visits the local file "index.html"
    ```
- Click a DOM element:
  ```jsx
  .click()
  ```
  - Example:
    ```jsx
    cy.get(".btn").click(); // Click on button
    cy.focused().click(); // Click on el with focus
    cy.contains("Welcome").click(); // Click on first el containing 'Welcome'
    ```
  - Use selector playground to select DOM elements directly

## 29. Click options

- Even though any element has got own id we can't select and click it since it alone won't have any dimension in the DOM and with cypress we can't select element without any dimensions
  - In such situation to use specific options like `force:true` as parameter of the `click()` method, which will disable the error checking.
  - Example:
    ```jsx
    cy.get("#contact-us").click({ force: true });
    ```

## 30. Type Command

- `type()` is used to type in the input
- We have to get the input and select before typing
- Example:
  ```jsx
  cy.get('[name="first_name"]').type("Pankaj");
  ```

# Section 12: Creating Our First Test (The Challenge)

## 31. Challenge overview

- Was fairly easy challenge
- LInk to repo with `12` folder

## 33. Creating Our Second Cypress Test (Negative Test Case)

- We will simulate a scenario where test case is going to be failed
- We will keep the email field blank and check the test
- Code:

  ```jsx
  /// <reference types="cypress" />

  describe("Test Contact Us form via WebdriverUni", () => {
  	it("Should fail to submit form", () => {
  		cy.visit("https://www.webdriveruniversity.com/Contact-Us/contactus.html");
  		cy.get('[name="first_name"]').type("Pank");
  		cy.get('[name="last_name"]').type("Aj");
  		cy.get('[name="email"]').type(" ");
  		cy.get("textarea.feedback-input").type(
  			"this is lorem ipsum equivalnet text which means these are texts but these are not the valid texts so we can't even see or read the contents and consider it as a valid text field "
  		);
  		cy.get('[type="submit"]').click();
  	});
  });
  ```

  - Which will give following error message
    ```jsx
    Error: Invalid email address
    ```

- Don't afraid with the errors but try to understand what it's throwing

## 34. Targeting individual Tests via Mocha

- We can use `.only` method to make the specific test scenario run
- `.only` comes from mocha
- Example:

  ```jsx
  describe("Test Contact Us form via WebdriverUni", () => {
  	it.only("visit website", () => {
  		cy.visit("https://www.webdriveruniversity.com/Contact-Us/contactus.html");

  });
  ```

# Section 13: Running Tests in Chrome, Electron & Firefox

## 35. Running Tests in Chrome, Electron & Firefox

- To use the particular browser while testing just utilize the browser list dropdown given on test cypress GUI

# Section 14: Web Elements & Selectors

## 36. Why do we need Selectors?

- Selectors allows to use the particular part of the DOM
- One need to know the best practice to use the selector
- Visit this [link](https://docs.cypress.io/guides/references/best-practices#Selecting-Elements) for better understanding
- Important:
  1. Don't target elements based on CSS attributes such as: `id`, `class`, `tag`
  2. Don't target elements that may change their `textContent`
  3. Add `data-*` attributes to make it easier to target elements like
     - `data-cy`
     - `data-test`
     - `data-testid`

## 37. Document Object Model (DOM) & Elements

- HTML opening tags and closing tags
- Class and id attributes
- Parent, child and sibling elements

## 38. Practical In Depth Look into selectors Part 1/2

- Looking into the XHR logs warnings and errors will let us improve or systems more
- To prevent cypress to log xhr errors, navigate to `cypress > support > index.js` and add:
  ```jsx
  Cypress.Server.defaults({
  	ignore: (xhr) => bool,
  });
  ```
  - Doing this can also cause some other issues to the projects. more information can be found [here](https://github.com/cypress-io/cypress/issues/9358)

## 39. Practical In Depth Look into selectors Part 2/2

- It's recommended to use chrome browser instead of fireFox since firefox may show security concerns while selecting the forms

## 40. Selector Generator Tools

- We can use chrome addon called `Ranorex Selocity` in chrome instance to Auto-generate robust XPath, link text, RanoreXPath, and CSS selectors for use with Selenium.
- To use `Ranorex Selocity`, go to Inspect element and then use your selctors
  - Example to select a link with href of `https://google.com`:
  ```jsx
  a[(href = "https://google.com")];
  ```

## 41. CSS Selector

- To know how CSS selectors work, visit this [link](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)

[CSS selectors - CSS: Cascading Style Sheets | MDN](https://www.notion.so/CSS-selectors-CSS-Cascading-Style-Sheets-MDN-82a275e1544241bcaaad18f016c76b17)

- To select the elements more sophisticatedly, we can utilize the CSS selector properties,
  example: to select button having title of submit will make sure that it is unique in the page
  ```jsx
  button[(type = "Submit")];
  ```

## 42. Xpath Selectors Part 1/3

[XPath Tutorial](https://www.notion.so/XPath-Tutorial-ab9bd8e4d79149faa96f0c163072715e)

[XPath Syntax](https://www.notion.so/XPath-Syntax-fbf872f842c949249be684db95d88834)

- We can use the Xpath selector just the way we have used the CSS selector

## 43. Xpath Selectors Part 2/3

- All about how to use the Xpath to select elements in the site.
- Referring to doc will be a good practice

`date: Fri, 29 oct 2021`

## 44. Xpath Selectors Part 2/3

- `cypress-xpath` package can also be used to code along which should be imported
- npm link for the package is [here](https://www.npmjs.com/package/cypress-xpath)

## 45. Improving Our Tests with Dynamic Selectors

- We need to select the element in way so that it won't break even if the element is manipulated or it's attributed will be manipulated in the future.
- It's recommended to use more specific ways to select the elements
- Example: selecting independent links whose href ends with "contact" and 'starting" with https
  ```jsx
  a[(href$ = "contact")];
  a[(href ^= "https")];
  ```
- Example: selecting button with type "Submit"
  ```jsx
  button[(title = "Submit")];
  ```

## 46. More selector examples

- By tag name
  ```jsx
  cy.get("input");
  ```
- By attribute name and value
  ```jsx
  cy.get("input[name='first_name']");
  ```
- By id
  ```jsx
  cy.get("contact_me");
  ```
- By class
  ```jsx
  cy.get(".feedback-input");
  ```
- By multiple classes
  ```jsx
  cy.get("[class='navbar navbar-inverse navbar-fixed-top]");
  ```
- By two different attributes
  ```jsx
  cy.get("[name='email'][placeholder='Email Address']");
  ```
- By xpath
  ```jsx
  cy.xpath("//input[@name="first_name"]")
  ```

# Section 15: Assertions

## 48. Why Do We Need Assertions?

- Is used to validate weather the test should pass or fail
- It's done with respect of end user

## 49. Chai Assertions & Cypress examples

- Chai is an assertion library
- Refer [here](https://docs.cypress.io/guides/references/assertions#Adding-New-Assertions) for official doc on adding new assertions

## 50. Adding Assertions to our existing Tests

- It's just doing all the tests and in the end we will be adding an assertion to verify the content is present there which appears after all the test is done
- Example:
  ```jsx
  cy.get("#user-name").should("have.text", "Joe Smith");
  ```

## 51. Chai JQurey

- Refer [here](https://docs.cypress.io/guides/references/assertions#Chai-jQuery) for more info
- We can also see the states of the tests and see before and after situations of he particular states
- We can also perform the tests against the element just like we did with the test
- Example: to select email field which have attribute of name and having value "email"
  ```jsx
  cy.get("#ContactUsFrm_email").should("have.attr", "name", "email");
  ```

## 54. Cypress Contains

- It looks for the string in the document
- Example:
  ```jsx
  cy.get("body").contains("Error: all fields are required");
  ```

# Section 16: Referencing Windows

## 55. cy.document()

- Gets the `window.document` of the page that is currently active.
- Refer to this [link](https://docs.cypress.io/api/commands/document) for more details
- With this we can target the codes related to the pages as well
- Example: checking meta charset
  ```jsx
  cy.document().should("have.property", "charset").and("eq", "UTF-8 ");
  ```
- Note: we need to do this after page is rendered i.e. visited only
- Meta is the property of the website so we can do it

## 56. cy.title()

- Get the `document.title` property of the page that is currently active
- Visit this [link](https://docs.cypress.io/api/commands/title) for more info
- Example:
  ```jsx
  cy.title().should("eq", "My Awesome Application");
  ```

## 57. cy.url()

- Get the current URL of the page that is currently active.
- Visit this [link](https://docs.cypress.io/api/commands/url#Syntax) for more info
- Example:
  ```jsx
  cy.url(); // Yields the current URL as a string
  ```

# Section 17: Triggering Tests via Command line

## 58. Headless Electron Browser

- Need to use some sort of bash or cmd to run the test in command line
- It will run test in headless mode so there will not be any browser window
- Once test will fully executed, test result will appear
- When you run test on cmd then it will also create a video folder inside of which test execution video files will be created
- To run cypress in headless mode:
  ```jsx
  npx cypress run
  ```
  - It will execute all the test files
- To execute specific test file only:
  ```jsx
  cypress run --spec cypress/integration/<file_name>.test.js
  ```
- To execute test with the npm do following in `package.json` file
  ```jsx
  "scripts": {
      "test": "cypress run"
    },
  ```

## 58. Non Headless Electron Browser

- For more information on cypress command line follow this [link](https://docs.cypress.io/guides/guides/command-line#Installation)
- Video snapshot is recorded for each tests in headless mode
- In headless option, test will run on electron browser while in headed mode it will run both with runner client and the electron browser
- To execute command in headless mode:
  ```jsx
  cypress run --headless
  ```
- To execute command in headed mode:
  ```jsx
  cypress run --headed
  ```

## 60. Non-Headless Chrome Browser

- To use specific browser or chrome in this context in headed environment:
  ```jsx
  cypress run --headed <browser_name>
  ```
- To run particular test file with browser of your choice on headed mode:
  ```jsx
  cypress run --spec  cypress/integration/<file_name.test.js>  --headed <browser_name>
  ```

## 61. Trigger Individual Tests

- To target on of the test we need to use `--spec` option along with the path of the test file from the root directory
- Example:
  ```jsx
  cypress run --spec cypress/integration/<file_name>.test.js
  ```
- To run all the test files inside of the folder:
  ```jsx
  cypress run --spec cypress/integration/<folder_name>/*
  ```
  - It will run all the test files inside of the test folder mentioned

# Section 18: Cypress Chaining Commands

## 62. Cypress Chaining Commands - Introduction

- Follow this [link](https://docs.cypress.io/guides/core-concepts/introduction-to-cypress#Chains-of-Commands) for doc
- Chaining is to just the combine the commands together while each command is subject to the another after it's completion
- Example:
  ```jsx
  cy.get("textarea.post-body").type("This is an excellent post.");
  ```

## 63. More Examples of Command Chaining -get, find, contains, eq - Part 1/2

- Just normal way to chain the methods
- Keep in mind that chained each next command is dependent on previous one

## 64. More Examples of Command Chaining -get, find, contains, eq - Part 2/2

- Same way as previous one
- For the following test case:
  ```jsx
  cy.get(".fixed_wrapper").find(".productname").eq(0).click();
  ```
  - Get the element with class `.fixed_wrapper` which further has got class `.productname` and select 1st one from the list (i.e. 0th index) and then click it in end

# Section 19: Synchronous vs Asynchronous

## 65. Synchronous vs Asynchronous Overview

- JavaScript can have asynchronous code, but it is generally single threaded
- Follow this youTube [tutorial](https://www.youtube.com/watch?v=ZYb_ZU8LNxs&t=72s) on async and await for the in-depth explaination
- Synchronous:
  1. Code is executed one at a time in order it appears
  2. Single threaded synchronous execution (Executed in sequenced manner)
  3. In javaScript this means one thing is happening at a time
- Asynchronous:
  1. Is more than one thing happening at a time
  2. Some code is executing which starts of executing some other code and that starts executing some more code
  3. All this code is executing within the engine at the same time
  4. Whatever step is available to be executed will be executed
  5. Cypress is asynchronous in nature

## 66. Synchronous Example

- In synchronous, code executes one at a time in an order

## 67. Asynchronous Example

- In asynchronous, code doesn't follow any particular order to be executed
- An example of this can be `[setTimeOut](https://www.w3schools.com/jsref/met_win_settimeout.asp)` function

## 68. Cypress Asynchronous Nature

- It uses wrappers in the background to handle asynchronous events
- Follow this [link](https://docs.cypress.io/guides/core-concepts/introduction-to-cypress#Commands-Are-Asynchronous) for official documentation example
- Cypress commands don't do anything at the moment they are invoked, but rather enqueue themselves to be run later. This is what we mean when cypress commands are asynchronous

# Section 20: Logging - Practical Asynchronous JS Example

## 69. Non Cypress Commands and Async Nature

- If we use non-cypess commands like `console.log()` then the order of execution is not guaranteed

## 70. Cypress Log

- Prints a message to the Cypress Command Log.
- Refer to this [link](https://docs.cypress.io/api/commands/log) for documentation
- Example:
  ```jsx
  cy.log("created new user");
  ```

# Section 21: Promises and the Then Command

## 71. Promises Real World Example

- A promise has 2 states they are resolve and reject. It starts with blank state though
- If promise is fulfilled then it will execute the resolve block and if not then reject block will be executed
- Follow this [video](https://www.youtube.com/watch?v=DHvZLI7Db8E) for in-depth tutorial in promises

## 72. Promises and Cypress

- Cy handles the all the promises by itself but it you can still choose to write it

## 73. then command

- Follow this [link](https://docs.cypress.io/api/commands/then) for the official documentation
- Enables you to work with the subject yielded from the previous command
- Callbacks are generally used with prefix of `$` symbol
- Example:
  ```jsx
  cy.get(".nav").then(($nav) => {}); // Yields .nav as first arg
  cy.location().then((loc) => {}); // Yields location object as first arg
  ```
- Example: to click on a product and then log the text where it was clicked

  ```jsx
  cy.get(".prdocutname")
  			.contains("Skinsheen Bronzer Stick")
  			.click()
  			.then((itemHeaderText) => {
  				console.log("selected following text: " + itemHeaderText.text());

  			});
  	});
  ```

  - `.text()` comes from jQurey

- Promise will allow to run the non js codes like `conosle.log()` to run asynchronously unlike regular commands where the codes order won't be fixed

# Section 22: Variables

## 76. Variables - Part 1/4

- Variables in cypress are just like js variables
- Examples:

```jsx
const makeupLink = cy
	.get(
		"a[href*='https://automationteststore.com/index.php?rt=product/category&path=']"
	)
	.contains("Makeup");
```

## 77. Variables - Part 2/4

- Clicking the `makeUpLink` we created on previous link:
  ```jsx
  makeupLink.click();
  ```
- One needs to be very careful while executing variable commands because it can affect the execution order
- Example:

  1. Good practice

  ```jsx
  const skinCareLink = cy
  	.get("a[href*='https://automationteststore.com']")
  	.contains("Skincare");
  skinCareLink.click();

  const makeupLink = cy
  	.get("a[href*='https://automationteststore.com/']")
  	.contains("Makeup");
  makeupLink.click();
  ```

  1. Bad practice

  ```jsx
  const skinCareLink = cy
  	.get("a[href*='https://automationteststore.com']")
  	.contains("Skincare");

  const makeupLink = cy
  	.get("a[href*='https://automationteststore.com/']")
  	.contains("Makeup");

  makeupLink.click();
  skinCareLink.click();
  ```

`date: Sun, 31 oct 2021`

## 78. Variables - Part 3/4

- While getting contents of the particular field it's always better to use promises to make sure that there won't be any issues while getting values
- Example:
  ```jsx
  **cy.get("h1 > .maintext").then((foundHeader) => {
  			const contents = foundHeader.text();
  			cy.log("header content is", contents);
  		});**
  ```

## 79. Variables - Part 4/4

- Using assertion to confirm that the tested block is working properly by using expect and comparing the contents
  ```jsx
  cy.get("h1 > .maintext").then((foundHeader) => {
  	const contents = foundHeader.text();
  	cy.log("header content is", contents);
  	expect(contents).is.eq("Makeup");
  });
  ```

## 80. Variables, Promises & Nested Closures Part 1/2

- Follow this doc for more full [details](https://docs.cypress.io/guides/core-concepts/variables-and-aliases#Closures)
- To access what each Cypress command yields you use
  `[.then()](https://docs.cypress.io/api/commands/then)`
- Each nested command has access to the work done in previous commands

## 81. Variables, Promises & Nested Closures Part 2/2

- `.then()` is used to handle the order of execution as well so it's quite important to use it
- Notes from [youtube](https://www.youtube.com/watch?v=izT3DpFCOpw) on wrap
  - We use `cy.wrap()` on web element, objects, arrays and js promises

# Section 23: Iterating Through Elements

## 82. Iterating Through Elements- Documentation & preparation

- We use `each()` method to iterate over the elements in cypress
- It allows us to iterate through an array like structure (arrays or objects with a `length`
  property).
- For full details visit this [link](https://docs.cypress.io/api/commands/each)
- Example:
  ```jsx
  cy.get('ul>li').each(() => {...}) // Iterate through each 'li'
  cy.getCookies().each(() => {...}) // Iterate through each cookie
  ```

## 83. Practical Example of Iterating Through Elements part 1/2

- Example:

  ```jsx
  it("Log information of all hair care products", () => {
  	cy.visit("https://automationteststore.com/");
  	cy.get("a[href*='product/category&path=']").contains("Hair Care").click();

  	cy.get(".fixed_wrapper .prdocutname").each(($el, index, $list) => {
  		cy.log("Index: " + index + " : " + $el.text());
  	});
  });
  ```

## 84. Practical Example of Iterating Through Elements part 1/2

- Whenever we are using some sort of text content to active any event or use any functions, make sure to wrap it and yield so that we can use cypress operation on it
- Example:
  ```jsx
  cy.get(".fixed_wrapper .prdocutname").each(($el, index, $list) => {
  	if ($el.text().includes("Curls to stright Shampoo")) {
  		// we need to use cypress method to trigger the click, we can't directly select $el and use click but has to be yeilded and wrapped so that we can use cypress click method there
  		cy.wrap($el).click();
  	}
  });
  ```

# Section 24: Alias & Invoke

## 85. Alias & Invoke - Documentation

- Aliasing **describes a situation in which a data location in memory can be accessed through different symbolic names in the program**
- Highly suggested to go through this [documentation](https://docs.cypress.io/guides/core-concepts/variables-and-aliases#Return-Values) for the in-depth explanation
- Example:

  ```jsx
  beforeEach(() => {
  	// alias the $btn.text() as 'text'
  	cy.get("button").invoke("text").as("text");
  });

  it("has access to text", function () {
  	this.text; // is now available
  });
  ```

## 86. Alias & Invoke - Practical example

- We use `.invoke()` to invoke and `.as()` to alias
- After declaring as an alias, to access we need to use it with `@`
- Example:

  ```jsx
  cy.get(".fixed_wrapper .prdocutname")
  	.eq(0)
  	.invoke("text")
  	.as("productThumbnail");

  cy.get("@productThumbnail").its("length").should("be.greaterThan", 5);
  ```

- We can use alias multiple times

`date: Mon, 1 Nov 2021`

# Section 26: Cypress Limitations

## 94. Cypress Limitations

- Cypress is not a general purpose automation tool
- Cypress commands runs inside of a browser
- There will never be support for multiple browser tabs
- You can't use cypress to drive two browsers at the same time
- Each test is bound to a single origin
- Visit the [link](https://docs.cypress.io/guides/references/trade-offs#Permanent-trade-offs-1) for more details

# Section 27: Recipies

## 95. Cypress Recipies

- Recipes show you how to test common scenarios in Cypress
- Follow this [link](https://docs.cypress.io/examples/examples/recipes#Fundamentals) for documentation

# Section 28: Child Windows

## 96. Handling Multiple Browser Tabs

- Follow this [link](https://docs.cypress.io/guides/references/trade-offs#Multiple-tabs) for documentation
- Most of times while visiting any sites and some new tabs will open, we can't actually test the new tab and cypress considers the old tab as testing tab
- Solution to such problem is to remove the attribute of the link and then make the tab open in the same tab instead of new tab
- We can use jQuery `removeAttr()` method to remove to remove attributes
- Go through this [link](https://www.w3schools.com/jquery/html_removeattr.asp) for more information
- Example:
  ```jsx
  cy.get("#contact-us").invoke("removeAttr", "target").click();
  ```

# Section 29: Same Origin Policy

## 97. Same Origin Policy - Example 1/2

- Follow this [link](https://docs.cypress.io/guides/guides/web-security#Limitations) for documentation on same origin policy on cypress
- If you attempt to visit two different superdomains, Cypress will error. Visiting subdomains works fine. You can visit different superdomains in different tests, but not in the same test

## 98. Same Origin Policy - Example 1/2

- Currently cypress doesn't support visiting multiple domains in one test
- In `cypress.json` file though we can disable the browser security to try as:
  ```jsx
  {
  	"chromeWebSecurity": false
  }
  ```

# Section 30: Browser Navigation

## 99. Back, Forward, Reload - Part 1/2

- We use `cy.go()` to perform browser actions
- Example: to go back
  ```jsx
  cy.go("back");
  ```
- Example: to reload
  ```jsx
  cy.reload();
  cy.reload(true); // reload without using cache
  ```
- Example: to go forward
  ```jsx
  cy.go("forward");
  ```

## 100. Back, Forward, Reload - Part 2/2

- To ensure that we have navigated to specific page we can use assertions as well to check the URL

# Section 31: Handling Alerts

## 103. Handling Alerts - Documentation

- Cypress can automatically handle js alerts however we can still add logic to catch the alerts by handling the events
- Visit this [link](https://docs.cypress.io/api/events/catalog-of-events#Event-Types) for more information on catalog of events in cypress

## 104. Handling Alerts - Example 1/2

- Though cypress handles the js alerts by itself, we can further tweak into it to do operations by selecting the relevant operations and making assertions
- To handle events we use `.on()` method
- Example:
  ```jsx
  cy.on("window:alert", (stringPresent) => {
  	// asserting that the alert box has the text we are expecting
  	expect(stringPresent).to.equal("I am an alert box!");
  });
  ```

## 105. Handling Alerts - Example 2/2

- Working with confirm alert box

  ```jsx
  it.only("confirm js confirm alert box works correctly when clicking ok", () => {
  	cy.visit("http://www.webdriveruniversity.com");
  	cy.get("#popup-alerts")
  		.invoke("removeAttr", "target")
  		.click({ force: true });

  	cy.get("#button4").click();

  	cy.on("window:alert", (stringPresent) => {
  		// if we return true then it will click the true button while on returing false it will click the other button
  		return true;
  	});

  	// asserting that the alert box has the text we are expecting
  	cy.get("#confirm-alert-text").contains("You pressed OK!");
  });
  ```

## 108. Handling Alerts with Stubs

- A stub is a way to modify a function and delegate control over its behavior to the programmer
- Follow this [link](https://docs.cypress.io/api/commands/stub) for documentation
- It can be used in such a way that when a particular event has triggered then that `sutb` will also be triggered
- A stub can be chained with multiple events and the events can be accessed through index as `stub.getCall(index)` and then it can be further asserted for validation
- Example:

  ```jsx
  it("implementing stubs feature", () => {
  	cy.visit("http://www.webdriveruniversity.com");
  	cy.get("#popup-alerts")
  		.invoke("removeAttr", "target")
  		.click({ force: true });

  	//  creating a stub for an event
  	const stub = cy.stub();
  	// triggering stub for an event
  	cy.on("window:confirm", stub);

  	cy.get("#button4")
  		.click()
  		.then(() => {
  			// check if stub with particular index is having partiuclar text
  			// isImportant
  			expect(stub.getCall(0)).to.be.calledWith("Press a button!");
  		})
  		.then(() => {
  			// clicking ok button since true returns ok
  			return true;
  		})
  		.then(() => {
  			// validating with assertion
  			cy.get("#confirm-alert-text").contains("You pressed OK!");
  		});
  });
  ```

# Section 32: Handling Iframes's

## 109. Handling Iframes's Part 1/2

- If your site embeds an `<iframe>` that is a cross-origin frame, Cypress will not be able to automate or communicate with this `<iframe>`
- It's actually _possible_ for Cypress to accommodate these situations, but you will never have _native_ access to these iframes from inside of Cypress
- Follow this [link](https://docs.cypress.io/guides/guides/web-security#Cross-origin-iframes) for documentation
- Example of uses for cross-origin iframes
  1. Embedding a Vimeo or You Tube video
  2. Displaying a credit card form from Stripe or Braintree
  3. Displaying an embedded login form from Auth0
  4. Showing comments from Disqs
- We can manipulate DOM to connect with iframe

`date: Tue, 2 Nov 2021`

# Section 33: Handling Checkboxes

## 111. Handling checkboxes part 1/2

- This element must be an `<input>` with type `checkbox` or `radio`
- visit this [link](https://docs.cypress.io/api/commands/check#Syntax) for more information
- example:
  ```jsx
  cy.get('[type="checkbox"]').check(); // Check checkbox element
  cy.get('[type="radio"]').first().check(); // Check first radio element
  ```

## Selecting Multiple checkboxes

- example:
  ```jsx
  cy.get("input[type=checkbox]")
  			.check(["option-1", "option-2", "option-3", "option-4"])
  			.should("be.checked");
  	});
  ```

# Section 34: Handling Radio Buttons

## 116. Handling - Radio Buttons

- example:
  ```jsx
  // finding all the radio buttons and then accessing child according to index starting from 0
  cy.get("#radio-buttons").find("[type='radio']").eq(2).check();
  ```

## 117. Validating States of Radio Buttons (checked and unchecked)

- example:
  ```jsx
  cy.get("[value='lettuce']").check();
  cy.get("[value='lettuce']").should("be.checked");
  ```

# Section 35: Handling Drop-down Lists

## 118. Handling Drop-down Lists 1/2

- we need to select the dropdown item first and then only we should be able to select any options
- example: to select a dropdown menu and then select a particular option

  ```jsx
  it("Select specific values via select dropdown lists ", () => {
  	cy.visit("http://www.webdriveruniversity.com");

  	cy.get("#dropdown-checkboxes-radiobuttons")
  		.invoke("removeAttr", "target")
  		.click({ force: true });

  	// selecting a dropdown menu first and then clicking an option from there
  	cy.get("#dropdowm-menu-1").select("c#");
  	cy.get("#dropdowm-menu-3").select("JavaScript");
  	// cy.get("#dropdown-menu-1").select("jquery");
  });
  ```

## 118. Handling Drop-down Lists 2/2

- we can handle drop down by selecting with the text value of the option as well directly
- example: using present in the option to select an option
  ```jsx
  // selecting a dropdown menu first and then clicking an option from there from options
  cy.get("#dropdowm-menu-1").select("c#");
  ```

`date: Wed, 3 Nov 2021`

# Section 36: Autocomplete (Suggested) Lists

## 122. Handling Autocomplete Lists - Part 1/2

- while typing for autocomplete text, it's the same process as typing on other normal text field
- example:
  ```jsx
  cy.get("#myInput").type("A");
  ```

## 123. Handling Autocomplete Lists - Part 2/2

- to select option from the suggestion list, we should select the main list first then we will select particular element
- example:

  ```jsx
  it("check if suggestion includes grapes", () => {
  	cy.visit("http://www.webdriveruniversity.com");

  	cy.get("#autocomplete-textfield")
  		.invoke("removeAttr", "target")
  		.click({ force: true });

  	cy.get("#myInput").type("G");

  	cy.get("#myInputautocomplete-list > *").each(($el, index, $list) => {
  		const product = $el.text();
  		const productToSelect = "Grapes";

  		if (product === productToSelect) {
  			// $el.click();
  			$el.trigger("click");
  			cy.get("#submit-button").click();
  		}
  	});
  });
  ```

- `$el.click()` is now deprecated. Instead it is now recommended to use `$el.trigger("click")` instead

# Section 37: Mouse Actions

## 127. Scroll into view

- we can perform mouse events like drag and drop, double click, hover, click and hold
- we use cypress command `trigger` for mouse events
- follow this [link](https://docs.cypress.io/api/commands/trigger) for documentation
- `scrollIntoView()` method is used to use scroll method to the view of the selector
  ```jsx
  cy.get("#actions")
  	.scrollIntoView()
  	.invoke("removeAttr", "target")
  	.click({ force: true });
  ```

## 128. Drag and Drop

- follow this [link](https://docs.cypress.io/api/commands/trigger#Mouse-Events) for documentation on mouse events
- The DOM element must be in an "interactable" state prior to the triggered event
  happening (it must be visible and not disabled).
- example: to perform drag and drop

  ```jsx
  it.only("Drag and drop", () => {
  	cy.visit("http://www.webdriveruniversity.com");

  	// scroll to the selector and then cick it
  	cy.get("#actions")
  		.scrollIntoView()
  		.invoke("removeAttr", "target")
  		.click({ force: true });

  	//  triggering mouse down event to trigger click event
  	cy.get("#draggable").trigger("mousedown", { which: 1 });

  	//  while click event is still running, moving the mouse to the selector (i.e dragging)
  	//  and then when the mouse is moved to desired location, trigger the mouseup
  	//  then it will ensure the drag and drop event as complete
  	cy.get("#droppable")
  		.trigger("mousemove")
  		.trigger("mouseup", { force: true });
  });
  ```

## 129. Double Click

- we use `dblclick()` method to perform double click event
- example:
  ```jsx
  cy.get("#double-click").dblclick();
  ```

## 130. Click, Hold & Assertions

- example:
  ```jsx
  cy.get("#click-box")
  	.trigger("mousedown", { which: 1 })
  	.then(($element) => {
  		expect($element).to.have.css("background-color", "rgb(0, 255, 0)");
  	});
  ```

`date: Thr, 4 Nov 2021`

# Section 38: Traversal

## 131. Traversal Prepration

- the section included the working file

## 132. children()

- we use `children()` method to get the list of children
- we will have to select the parent first and then use `.children()` property to select all the children
- example:
  ```jsx
  // traversing the children and then select child having particular class name and containing given text string
  cy.get(".traversal-breadcrumb")
  	.children(".active")
  	.should("contain", "Contact Us");
  ```

## 133. closest()

- is used to locate the closest ancestor of the selected element
- for this, we use `closest()` method
- example: to find an `ul` element closest to the element selected and verify with assertion to have the `ul` element particular class name
  ```jsx
  cy.get(".traversal-badge").closest("ul").should("have.class", "list-group");
  ```

## 134. eq()

- It gets a DOM element at a specific index in an array of elements
- Indexing works just like in other programming concepts
- example: to traverse through list of elements and then select an particular element and annotate to annotate that element contains text string
  ```jsx
  // select list, pick particular element and then make sure it contains the text
  cy.get(".traversal-drinks-list > *").eq(2).should("contain", "Milk");
  ```

## 135. filter()

- It retrieves DOM elements that match a specific selector
- example:
  ```jsx
  // get selector and select it's child and then filter out element which contains class of passed class
  cy.get(".btn-group-toogle > *")
  	.filter(".active")
  	.should("contain", "Button-1");
  ```

## 136. find()

- Get the descendent DOM elements of a specific selector
- example:
  ```jsx
  cy.get(".traversal-pagination").find("li").find("a").should("have.length", 7);
  ```

## 137. first()

- Get the first DOM element within a set of DOM elements
- example:
  ```jsx
  // get elements haivng childs and then access first element and asserting
  cy.get(".traversal-table > tbody > tr > td")
  	.first()
  	.should("contain", "Andy");
  ```

## 138. last()

- Get the last DOM element within a set of DOM elements
- example:
  ```jsx
  // get elements haivng childs and then access last element and asserting
  cy.get(".traversal-table > tbody > tr > td")
  	.last()
  	.should("contain", "Scott");
  ```

## 139. nextAll()

- Get all following siblings of each DOM element in a set of matched DOM elements
- example:
  ```jsx
  // get element haivng siblings and then access siblings element and asserting
  cy.get(".traversal-drinks-list")
  	.contains("Tea")
  	.nextAll()
  	.should("have.length", 3);
  ```

## 140. nextUntil()

- Get all following siblings of each DOM element in a set of matched DOM elements
  up to, but not including, the element provided
- example:
  ```jsx
  cy.get("div").nextUntil(".warning"); // Yield siblings after 'div' until '.warning'
  ```
- works like `nextUntil()` in jQuery

## 141. not()

- is used to exclude elements
- it works opposite of `filter()`
- example:
  ```jsx
  // selecting an element with childs and then apply the condition that the partiuclar class should not be included and then asserting that the class associated with not() is not present
  cy.get(".traversal-button-states > button")
  	.not(".disabled")
  	.should("not.have.class", "disabled");
  ```

## 142. parent()

- to get parent DOM element of elements
- example:
  ```jsx
  // selecting an element and tarageting parent and assert to make sure the parent contains partiuclar text
  cy.get(".traversal-mark ")
  	.parent()
  	.should("contain", "Lorem ipsum dolor sit amet, consectetur");
  ```

## 143. parents()

- Get the parent DOM elements of a set of DOM elements
- `.parents()` travels multiple levels up the DOM tree as opposed to the [.parent ()](https://docs.cypress.io/api/commands/parent) command which travels a single level up the DOM tree
- will mark all the parents of an elements

## 144. prev()

- Get the immediately preceding sibling of each element in a set of the elements
- example:
  ```jsx
  // selecting an element's previous element and asserting to make sure it contains text Espresso
  cy.get("#sugar").prev().contains("Espresso");
  ```

## 145. prevAll()

- Get all previous siblings of each DOM element in a set of matched DOM elements
- example:
  ```jsx
  // selecting an element and get all the previous siblings and asserting that they count as 2
  cy.get(".sales").prevAll().should("have.length", 2);
  ```

## 146. prevUntil()

- Get all previous siblings of each DOM element in a set of matched DOM elements up to, but not including, the element provided.
- example:
  ```jsx
  // get an element and get all the preceding siblings till #fruits and asserting that the siblings are in count of 5
  cy.get("#veggie").prevUntil("#fruits").should("have.length", 5);
  ```

## 147. siblings()

- Get sibling DOM elements
- example:
  ```jsx
  // selecting an element and get all the siblings and assert to verify that total sibligs are counted as 3
  		cy.get(".traversal-button-other-states .active")
  			.siblings()
  			.should("have.length", 3);
  	});
  ```

# Section 39: Handling Data from Tables

## 148. Handling Data - Example 1 - Part 1/3

- we sum the age of the all of the age of the users

## 151. Handling Data - Example 2 - Part 1/3

- validating age based on users last name

`date: Thr, 4 Nov 2021`

# Section 40: Handling Date Pickers

## 153. Handling Date Pickers - Part 1/5

- we add date count to the current date to make future date
- example: to add 5 days to the date

  ```jsx
  let date = new Date();

  // adding 1 to current day
  date.setDate(date.getDate() + 1);
  ```

## 156. Handling Date pickers - Part 4/5

- the main idea is to to able to pick the right place from where the date picker can be manipulated, date picker can vary from website to websites
- first get to the date picker and then have a function for creating a future or desired date and then run it to get the work done
- example:

  ```jsx
  /// <reference types="cypress" />

  describe("Test Date picker via webdriveruni", () => {
  	beforeEach(() => {
  		cy.visit("http://webdriveruniversity.com/");
  		cy.get("#datepicker")
  			.invoke("removeAttr", "target")
  			.click({ force: true });
  		// removing navbar element
  		cy.get(".navbar").invoke("remove");
  		cy.get("#datepicker").click();
  	});

  	it.only("select date from teh datepicker", () => {
  		let date = new Date();

  		// adding to current day
  		date.setDate(date.getDate() + 100);

  		let futureYear = date.getFullYear();
  		// formatting the month in proper way
  		let futureMonth = date.toLocaleString("defalut", { month: "long" });
  		let futureDay = date.getDate();

  		// logging info regarding future dates
  		cy.log("future year to select: " + futureYear);
  		cy.log("future month to select: " + futureMonth);
  		cy.log("future date to select: " + futureDay);

  		const selectMonthAndYear = () => {
  			cy.get(".datepicker-dropdown")
  				// selecting the date picker icon which is first one including the following class
  				.find(".datepicker-switch")
  				.first()
  				.then((currentDate) => {
  					// if the ui doesn't include the futureYear we have choose to then it will keep of clicking on the next icon untill it matches the year
  					if (!currentDate.text().includes(futureYear)) {
  						cy.get(".next").first().click();
  					}
  				})
  				.then((currentDate) => {
  					cy.get(".datepicker-dropdown")
  						.find(".datepicker-switch")
  						.first()
  						.then((currentDate) => {
  							// if the ui doesn't include the futureMonth we have choose to then it will keep of clicking on the next icon untill it matches the month
  							if (!currentDate.text().includes(futureMonth)) {
  								cy.get(".next").first().click();
  								selectMonthAndYear();
  							}
  						});
  				});
  		};

  		const seelctFutureDay = () => {
  			// picking or confirming the future date finally
  			cy.get('[class="day"]').contains(futureDay).click();
  		};

  		selectMonthAndYear();
  		seelctFutureDay();
  	});
  });
  ```

# Section 41: File Upload

## 158. Introduction and preparation

- we need to have dependency called `cypress-file-upload` which can be accessed through this [link](https://www.npmjs.com/package/cypress-file-upload)
- make sure to add the photos or files which has to be uploaded in the separate folder called `fixtures` since it contains the files and data while testing
- to access the files from the `fixtures` folder:
  ```jsx
  cy.fixture("<file_name>.format", "<type>");
  // to upload a png image:
  cy.fixture("laptop.png", "base64");
  ```
- on file being uploaded, we can see an alert message saying `your file has now been uploaded`

## 160. Uploading no File(s)

- it's just a simple scenario to see how things respond when no files are being uploaded and see how the site works
- example:
  ```jsx
  it("submiting without uploading a file ...", () => {
  		// clicking on the submit button without upolading
  		cy.get("#submit-button").click();
  ```

# Section 42: Hooks

## 161. Hooks - Documentation & Practical Example

- cypress comes pre-bundled with mocha
- hooks comes from mocha
- follow this link for more info on [hooks](https://docs.cypress.io/guides/core-concepts/writing-and-organizing-tests#Hooks)
- examples from doc:

  ```jsx
  before(() => {
  	// root-level hook
  	// runs once before all tests
  });

  beforeEach(() => {
  	// root-level hook
  	// runs before every test block
  });

  afterEach(() => {
  	// runs after each test block
  });

  after(() => {
  	// runs once all tests are done
  });

  describe("Hooks", () => {
  	before(() => {
  		// runs once before all tests in the block
  	});

  	beforeEach(() => {
  		// runs before each test in the block
  	});

  	afterEach(() => {
  		// runs after each test in the block
  	});

  	after(() => {
  		// runs once after all tests in the block
  	});
  });
  ```

`date: Thr, 4 Nov 2021`

# 43: Fixtures

## 165. Fixtures - Documentation

- Load a fixed set of data located in a file
- follow this [link](https://docs.cypress.io/api/commands/fixture#Syntax) for more informations
- instead of using all the hard typed values, we can actually use the data from the fixtures folder dynamically which can be used in test files
- example: to add data in the `example.json` file from `fixtures` directory

  - `example.json`

  ```jsx
  {
    "name": "Using fixtures to represent data",
    "email": "hello@cypress.io",
    "body": "Fixtures are a great way to mock data for responses to routes",
    "first_name" : "Joe",
    "last_name" : "blogs"
  }
  ```

  - `testfile.test.js`

  ```jsx
  before(() => {
  	// name of the file without extension
  	cy.fixture("example").then((data) => {
  		// both of the methods do work but if one fails other can be used
  		this.data = data;
  		globalThis.data = data;
  	});
  });

  it("test case", () => {
  	cy.get("#first_name").type(data.first_name);
  	cy.get("#last_name").type(data.last_name);
  });
  ```

## 168. Alias and Fixtures

- we can use alias for the fixtures as well
- to use alias with the fixtures, we need to use it like that
- example:

  ```jsx
  describe("Test Contact Us form via Automation Test Store", () => {
  	before(() => {
  		// importing userDetails file as alias of user
  		cy.fixture("userDetails").as("user");
  	});
  });

  it("test block", () => {
  	cy.get("#first_name").type(user.first_name);
  	cy.get("last_name").type(user.last_name);
  });
  ```

`date: Fri, 5 Nov 2021`

# Section 44: Custom Commands

## 169. Custom Commands - Documentation & Practical Example - Part 1/2

- follow the [link](https://docs.cypress.io/api/cypress-api/custom-commands) for documentation
- Programmer can use custom commands to override existing commands
- example:

  ```jsx
  Cypress.Commands.add("login", (email, pw) => {});

  Cypress.Commands.overwrite("visit", (orig, url, options) => {});
  ```

- custom commands are basically are just like functions
- commands are kept in `support > commands.js` file

`date: Mon, 8 Nov 2021`

# Section 45: Custom Commands & Fixtures - Wrap Up

## 175. Custom Commands and fixtures - Wrap Up - Part 1/3

- utilized previous knowledge on cyperss

# Section 46: Overriding Default Settings

## 178. cypress.config

- visit this [link](https://docs.cypress.io/guides/references/configuration#Global) for the related documentaion
- to override default cypress commands we should go to the `cypress.json` file and add the respective settings there
- example to disable `chromeWebSecurity` and change `defaultCommandTimeout`
  ```jsx
  {
      "chromeWebSecurity": false,
      "defaultCommandTimeout": 10000
  }
  ```
- all default and customized settings can be visited from `settings>configuration` in cypress client

## 179. Ignore files

- to ignore specific test files, we will have to specifically mention them in the `cypress.json` file.
- example to ignore all the files in the other directory:
  ```jsx
  {
  		"ignoreTestFiles" : "**/other/*"
  }
  ```
- on adding file or folder to the ignore list, it won't be visible in the test client as well

# Section 47: Environment & Global Variables

## 180. Prerequisites

- cypress by default runs headless and to run headed we have to use the command `--headed` for that
- learn more from this [link](https://docs.cypress.io/guides/guides/launching-browsers#Browsers)
- example:
  ```jsx
  npx cypress run --headed
  ```

## 181. Environment Variables

- must follow this [link](https://docs.cypress.io/guides/guides/environment-variables) for documentation for examples and learning
- In Cypress, "environment variables" are variables that are accessible via`Cypress.env`
- example:
  - declaration
  ```jsx
  {
  	"env": {
          "first_name": "Sam",
          "email": "sam_blogs@webdriveruni.com",
      }
  }
  ```
  - usage
  ```jsx
  cy.inputData(Cypress.env("first_name"));
  ```

`date: Wed, 10 Nov 2021`

## 182. Setting up a Base URL

- to setup base URL, we need to set up in the `cypress.json` file as:
  ```jsx
  "baseUrl": "http://www.webdriveruniversity.com"
  ```
- to access the base URL :
  ```jsx
  beforeEach(() => {
  	cy.visit("/");
  });
  ```
- once baseURL is created then it can be accessed in all of the files in the testing

## 183. Dynamic URL's

- dynamic URL are helpful when we have multiple base URL to test
- the URL has to be kept in the environment variable
- to create global URL:
  ```jsx
  // in cypress.json file:
  {
  	"env": {
  			"second_website_link": "https://google.com",
  	}
  }
  ```
- to access URL dynamically by appending routes :
  ```jsx
  beforeEach(() => {
  	cy.visit(Cypress.env("second_website_link") + "/contac_us");
  });
  ```
- there can be multiple `URL` inside of `env` scope inside of `cypress.json` file

# 184. Dynamic URL's & custom commands: Example 1/2

- to use custom command with base URL:
  - `cypress.json`
    ```jsx
    {
    	"baseUrl": "http://www.webdriveruniversity.com"
    }
    ```
  - `commands.js`
    ```jsx
    Cypress.Commands.add("navigateToHomePage", () => {
    	cy.visit("/");
    });
    ```
  - `testFile.test.js`
    ```jsx
    beforeEach(() => {
    	cy.navigateToHomepage();
    });
    ```

## 185. Dynamic URL's & custom commands: Example 2/2

- to visit specific route through dynamic link:
- `commands.js`
  ```jsx
  Cypress.Commands.add("navigateToContactUsPage", () => {
  	cy.visit("/" + "contact_us");
  });
  ```
- `testFile.test.js`
  ```jsx
  beforeEach(() => {
  	cy.navigateToContactUsPage();
  });
  ```

`date: Tue, 9 Nov 2021`

# Section 48: Page Object Modelling

- page object modeling is to model a part of website so that it can be used on other files as well so that we don't need to write lots of codes
- we can compare it just like components in react. Just to relate only though
- there is no difference in custom commands and Page Object Modelling it's just different way we are storing our files. Both are flexible and reusable
- for Page Object Modelling we need to create separate folder inside of `support` folder and create specific files on it. In section 48 we have `support > pageObject > webDriverUni > Homepage_PO.test.js`
- example:

  - `Homepage_PO.test.js`

    ```jsx
    class HomePage_PO {
    	// create command to visit webpage
    	visitHomepage() {
    		cy.visit(Cypress.env("webDriverHomePage"));
    	}

    	clickOn_ContactUs_Button() {
    		cy.get("#contact-us")
    			.invoke("removeAttr", "target")
    			.click({ force: true });
    	}
    }

    export default HomePage_PO;
    ```

  - `ContactUs_PO.test.js`

    ```jsx
    /// <reference types="cypress" />
    // _PO means page object

    class ContactUs_PO {
    	contact_Form_Submit() {
    		cy.get('[name="first_name"]').type("Pank");
    		cy.get('[name="last_name"]').type("Aj");
    		cy.get('[name="email"]').type("pank@pankmail.com");
    		cy.get("textarea.feedback-input").type(
    			"this is lorem ipsum equivalnet text which means these are texts but these are not the valid texts so we can't even see or read the contents and consider it as a valid text field "
    		);
    		cy.get('[type="submit"]').click();
    	}
    }

    export default ContactUs_PO;
    ```

  - `48 > contactUs.test.js`

    ```jsx
    /// <reference types="cypress" />

    import HomePage_PO from "../../support/pageObject/webDriverUni/Homepage_PO.test";
    import ContactUs_PO from "../../support/pageObject/webDriverUni/ContactUs_PO.test";

    describe("Test Contact Us form via WebdriverUni", () => {
    	// creating object from the page object modeling class
    	const homepage_PO = new HomePage_PO();
    	const contactUs_PO = new ContactUs_PO();

    	beforeEach(() => {
    		// accessing methods from the object
    		homepage_PO.visitHomepage();
    		homepage_PO.clickOn_ContactUs_Button();
    	});

    	it("Should be able to submit a successful submission via contact us form", () => {
    		// accessing methods from the object
    		contactUs_PO.contact_Form_Submit();
    	});
    });
    ```

# Section 49: Configuring & Handling Timeouts

## 192. URL Timeouts

- in cypress client the over-ridded values are highlighted in blue while default one will be marked in pink
- we can add timeout on specific commands as well
- follow this [link](https://docs.cypress.io/guides/references/configuration#Timeouts) for more information on timeouts
- example: add timeout of 9 secs to visit the URL
  ```jsx
  class HomePage_PO {
  	visitHomePage() {
  		cy.visit(Cypress.env("webdriveruni_homepage"), { timeout: 9000 });
  	}
  }
  ```

## 193. Explicit Timeouts

- we can give each test block timeout in the describe block which will make sure that the tests will run with that particular timeout
- example: to configure test block to be of 9 seconds
  ```jsx
  Cypress.config("defaultCommandTimeout", 9000);
  ```
- we can add timeout to the chained commands
- example: give timeout of 8 secs to the particular command
  ```jsx
  cy.get("#contact_us")
  	.invoke("removeAttr", "target")
  	.click({ force: true }, { timeout: 8000 });
  ```

## 194. Assertion Timeouts

- to add timeout in the assertions is quite same as to add timeout for chained commands
- example:
  ```jsx
  cy.get($selector).contains(TextToLocate, { timeout: 9000 });
  ```

## 195. Pause

- we can use `cy.pause()` to pause the command anywhere on test blocks. It can also be chained with the other commands
- pausing tests will help to debug
- on reaching to `cy.pause()` command it will stop all the executing commands for various interaction with the website
- example:
  ```jsx
  cy.get($selector).pause().contains(textToLocate, { timeout: 9000 });
  ```
  - the next command will be executed only after the pause will be resumed

## 196. Wait

- we use `cy.wait()` to wait for command for particular time in millisecond
- example: to wait for 3 seconds
  ```jsx
  cy.wait(3000);
  ```
- before using it make sure that when to use

# Section 50: Debugger

## 197. Cypress Debugger

- follow this [link](https://docs.cypress.io/guides/guides/debugging#Using-debugger) for documentation
- Cypress test code runs in the same run loop as your application. This means
  you have access to the code running on the page, as well as the things the
  browser makes available to you, like `document`, `window`, and `debugger`
- we can use `.debug()` command to run debugger to chain with the commands

## Section 51: Screenshots and Debugger

- cypress creates `screenshots` directory automatically
- follow this [link](https://docs.cypress.io/api/commands/screenshot) for documentation
- on headless running, it automatically snaps the screenshots of the failed test in the `screenshots` directory
- we can use `cy.screenshot()` in test block to take screenshot
- if a command will not run or fails to run then the code below that line will also not work and hence the screenshot command later on also doesn't work

## 199. Recording Videos

- follow this [link](https://docs.cypress.io/guides/guides/screenshots-and-videos#Videos) for documentation
- cypress records all of the videos of the headless execution until next time it will execute
- we can also configure the location of the video to be stored in `cypress.json` file
- also we can tweak into the compression mechanism of the video on the configuration file

`date: Thr, 11 Nov 2021`

# Section 52: Viewport - Altering Screen Sizes

## 200. Altering Viewports - Configuring Size and Orientation

- follow this [link](https://docs.cypress.io/api/commands/viewport) for documentation
- `viewportWidth`and `viewportHeight` can be configured globally as well
- example:
  ```jsx
  cy.viewport(550, 750); // Set viewport to 550px x 750px
  cy.viewport("iphone-6"); // Set viewport to 375px x 667px
  ```

# Section 53: Cookies and Local Storage

## 201. Clearing Cookies & Local Storage

- follow this [link](https://docs.cypress.io/api/cypress-api/cookies#Syntax) for the documentation
- `Cookies.debug()` enables you to generate logs to the console whenever any cookies are modified.
- example:
  ```jsx
  cy.clearLocalStorage(); // to clear localStorage
  cy.clearCookies(); // to clear cookies
  ```
- example:
  ```jsx
  cy.clearLocalStorage(); // to clear localStorage
  cy.clearCookies(); // to clear cookies
  ```

# Section 54: Cypress Dashboard

## 202. Cypress Dashboard - Practical Example Part 1

- The [Dashboard](https://on.cypress.io/dashboard) is a Cypress service that gives
  you access to tests you've recorded - typically when running Cypress tests fromyour [CI provider](https://docs.cypress.io/guides/continuous-integration/introduction). The Dashboard
  provides you insight into what happened during your tests run.

## 203. Cypress Dashboard - Practical Example Part 2

`date: Wed, 17 Nov 2021`

# Section 55: NPM scripts and NPX

## 205. Npx

- it simplifies the way we write commands
- go to this [link](https://www.npmjs.com/package/npx) for npm documentation

## 206. Npm scripts

- to create scripts within our test framework:
  - inside of package.json file we can customize the scirpts under `"scripts"` part
- example: to run test in headless and headed mode

```jsx
"scripts":{
	"triggerAllTests-headless":"npx cypress run",
	"triggerAllTests-headed":"npx cypress run --headed"

}
```

- to execute we need to do: `npm run <script_name>`
- example: to execute the custom script
  ```jsx
  1. npm run triggerAllTests-headless
  2. npm run triggerAllTests-headed
  ```

# Section 56: Reporting

## 208. JUnit Reporter

- we can enable to generate the reports
- follow this [link](https://docs.cypress.io/guides/tooling/reporters#Custom-reporter) for docs
- we can use JUnit for such
- we need to install the package externally for such like `cypress-multi-reporters` `mocha-junit-reporter` `mocha`
  ```jsx
  npm install --save-dev cypress-multi-reporters mocha-junit-reporter mocha
  ```
- Then add the separate `reporter-config.json` file (defined in your configuration) to enable `spec` and `junit` reporters and direct the `junit`reporter to save separate XML files.
  - spec means specific
  ```jsx
  {
    "reporterEnabled": "spec, mocha-junit-reporter",
    "mochaJunitReporterReporterOptions": {
      "mochaFile": "cypress/results/results-[hash].xml"
    }
  }
  ```
- Then add config scripts to the `cypress.json` file
  ```jsx
  {
  	  "reporter": "cypress-multi-reporters",
  	  "reporterOptions": {
  	    "configFile": "reporter-config.json"
  	  }
  }
  ```
- It will now create a report file for each of the test being executed as xml files

## 209. JUnit - Merging Reports

- to merge the reports into a separate files:
  - syntax
  ```jsx
  npx junit-merge -d <location_where_xml_files_are_stored> -o <location_for_merged_file_normally_in_same_directory>
  ```
  - example:
  ```jsx
  npx junit-merge -d cypress/results/junit -o cypress/results/junit/results.xml
  ```

## 210. Npm scripts - Merge & Delete JUnit Reports

- create custom script within framework to simplify the process to merge, delete, delete all files inside of `junit` directory
- we will go and create a new script now to do such inside of the script file
- example:

  ```jsx
  "junit-merge": "npx junit-merge -d cypress/results/junit -o cypress/results/junit/results.xml"

  "delete-junit-report": "rm -rf cypress/results/junit/results.xml"

  "delete-results": "rm -rf cypress/results/* || true"
  ```

  - to execute the command:

  ```jsx
  npm run junit-merge

  npm run delete-junit-report

  npm run delete-results
  ```

## 211. Mochawesome Reporter

- follow the [link](https://www.npmjs.com/package/mochawesome-report-generator) for package documentation
- follow the [link](https://docs.cypress.io/guides/tooling/reporters#Spec-to-STDOUT-produce-a-combined-Mochawesome-JSON-file) for cypress documentation on the package
- It creates the HTML report of the tests
- for that we need to add additional dependencies
  ```jsx
  npm install --save-dev mochawesome mochawesome-merge mochawesome-report-generator
  ```
- we need to setup specific config then inside of `reporter-config.json`
  ```jsx
  {
      "reporterEnabled": "spec, cypress-multi-reporters",
      "mochaJunitReporterReporterOptions": {
          "mochaFile": "cypress/results/junit//results-[hash].xml"
      },
      "reporterOptions": {
          "reporterEnabled": "mochawesome",
          "mochawesomeReporterOptions": {
              "reportDir": "cypress/results/mochawesome",
              "overwrite": false,
              "html": false,
              "json": true
          }
      }
  }
  ```
- the script will create various json files acc to the test cases insdie of the directory we specified in `reportDir`.

## 212. Mochawesome - Merging Reports

- to merge all the `.json` files inside of the `cypress/results/mochawesome` into the `mochawesome.json` and create HTML report after that from the `mochawesome.json` file
  ```jsx
  npx mochawesome-merge cypress/results/mochawesome/*.json > mochawesome.json && npx marge mochawesome.json
  ```

## 213. Npm Scripts - Merge & Delete Mochawesome Reports

- lecture contains the script to add custom commands
- example:

  ```jsx
  "mochawesome-merge": "npx mochawesome-merge cypress/results/mochawesome/*.json > mochawesome.json && npx marge mochawesome.json",

  "delete-mochawesome-reports": "rm -rf cypress/results/* mochawesome-report/* cypress/screenshots/*",

  "delete-videos": "rm -rf cypress/videos/*"
  ```

- commands can be executed with prefix of `npm run` as `npm run <command_name>`
- we can also execute the commands directly inside of the commands in chained way
  - example: run all the commands related to the `mochawesome` which includes `delete-videos-and-screenshoots`, `delete-mochawesome-reports`, `npx cypress run` and `mochawesome-merge-and-delete` . Some are custom written scripts while some are cypress in built through the single command `mochawesome-bundle-execution`
    - script
    ```jsx
    "mochawesome-bundle-execution": "npm run delete-videos-and-screenshoots && npm run delete-mochawesome-reports && npx cypress run && npm run mochawesome-merge-and-delete"
    ```
    - execute
    ```jsx
    npm run mochawesome-bundle-execution
    ```

# Section 57: Multiple Configuration Files

## 215. Custom config File - Overview & creation

- we can have multiple configuration files according to the environment like production, staging, development
- In the root directory we will then create `config` folder inside of which we will then keep all the custom config files. example: `staging.json`
- `staging.json`
  ```jsx
  {
  	"baseUrl" : "https://stage.automationstore.com/",
  	"env": {
  		"name": "Joe Blogs"
  	}
  }
  ```
- we can use methods to access particular config files then to read specific config file

  ```jsx
  function getConfigurationFile(file) {
  	const pathToConfigure = path.resolve("cypress", "config", `${file}.json`);

  	if (!fs.existsSync(pathToConfigFile)) {
  		console.log("no custom config file found");
  		return {};
  	}

  	return fs.readJson(pathToConfigure);
  }
  ```

`date: Wed, 17 Nov 2021`

## 217. Injecting Custom config file logic into our Framework

- to use particular config file while running test on cmd type:
  ```jsx
  npx cypress open --config-file cypress/config/<file_name>.json
  ```

## 218. Using custom config file settings during Runtime

- we can create our custom script to use particular config file
  ```jsx
  "triggerAllTests-Staging": "npx cypress run --config-file cypress/config/staging.json"
  ```

# Section 58: Cypress Retry

## 219. Adding Retry Logic to Framework

- follow this [link](https://docs.cypress.io/guides/guides/test-retries#How-It-Works) for doc
- It can be configured in `cypress.json` file
  ```jsx
  {
    "retries": {
      // Configure retry attempts for `cypress run`
      // Default is 0
      "runMode": 2,
      // Configure retry attempts for `cypress open`
      // Default is 0
      "openMode": 0
    }
  }
  ```
- we can also add it to each block of test codes
  ```jsx
  it(
  	"test block",
  	{
  		retries: {
  			runMode: 2,
  			openMode: 2,
  		},
  	},
  	() => {
  		//test cases
  	}
  );
  ```
- In headless mode, if we use command `CYPRESS_RETRIES=3` then it will override the parameter used with `runMode` in the configuration file
  ```jsx
  CYPRESS_RETRIES=3 npm run <custom_script>
  ```

# Section 59: Github -(source control)

## 222. Github

- using github will enable to do CI testings as well with tools like jenkins

## 223. Visual Studio Code & Github Setup

- install git and configure global username and email
- initalize git repo from the vscode itself
- add required folders for the gitignore
  ```jsx
  node_modules;
  results;
  screenshots;
  videos;
  mochawesome - report;
  package - lock.json;
  ```
-

# Section 60: Cross Browser Testing

## 229. NPM Scripts - Multi Browser Testing

- we can create a script in order to run the multi-browser testing
  - let's say we have a script called `runAllTestCases` for the cypress which will execute the tests in headless mode in electron browser then, we can use following method in order to add browser specific command in the script using npm
  ```jsx
  // adding the browser option using the external command in package.json file
  {
  	"customBrowsers":	"npm run runAllTestCases -- --browser edge --headed && npm run runAllTestCases -- --browser chrome64 --headed"
  }
  ```
  - note: since we are using npm commands, `--` (i.e double hyphen) is used in order to add the external commands. This is rule while specifying specific commands

## 230. Configuring Code & Tests for specific Browsers

- to make sure that a specific `it` block runs only for specific browser we can use the `{browser: '<broswerName>' }` in each test blocks
- exmaple
  ```jsx
  it("Download extension in Firefox", { browser: "firefox" }, () => {
  	cy.get("#dl-extension").should("contain", "Download Firefox Extension");
  });
  ```
- Also to run the command only after checking and verifying specific browser we can use following command

  ```jsx
  // Only run command in Chrome
  it("download extension link", () => {
  	// true when running in Firefox
  	if (Cypress.isBrowser("firefox")) {
  		cy.get("#dl-extension").should("contain", "Download Firefox Extension");
  	}

  	// true when running in Chrome
  	if (Cypress.isBrowser("chrome")) {
  		cy.get("#dl-extension").should("contain", "Download Chrome Extension");
  	}
  });
  ```

- Also to run the command for all browser except of specified:
  ```jsx
  // Run command in all browsers except Chrome
  it("warns to view page in Chrome browser", () => {
  	// true when running in Firefox, etc...
  	if (Cypress.isBrowser("!chrome")) {
  		cy.get(".browser-warning").should(
  			"contain",
  			"For optimal viewing, use Chrome browser"
  		);
  	}
  });
  ```

# Section 61: Jenkins (CI) - Continuous Integration

## 231. Jenkins (CI) - Overview

- Jenkins is used for CI automation testing

## 234. Jenkins - Download & Setup

- download Jenkins LTS from the [link](https://www.jenkins.io/download/)
-
