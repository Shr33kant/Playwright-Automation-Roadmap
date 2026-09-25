# 🎭 Playwright Automation — Beginner to Advanced
A practical, hands-on learning repository for mastering **Playwright Automation Testing** from fundamentals to real-world framework development.

> **Goal:** Learn Playwright by understanding the concepts, writing automation code, building a maintainable framework, integrating API testing and CI/CD, and documenting practical projects.

**Language:** TypeScript
**Automation Tool:** Playwright
**Test Framework:** Playwright Test
**Focus:** UI Automation • API Testing • Framework Design • CI/CD • Real-World Projects

## 📚 Table of Contents

* [🎯 Learning Objectives](#-learning-objectives)
* [🧩 Prerequisites](#-prerequisites)

  * [Software Testing Fundamentals](#1-software-testing-fundamentals)
  * [Web Fundamentals](#2-web-fundamentals)
  * [HTML](#3-html)
  * [CSS Selectors](#4-css-selectors)
  * [JavaScript / TypeScript](#5-javascript--typescript)
  * [Tools](#6-tools)
    
* [🗺️ Learning Roadmap](#️-learning-roadmap)

  * [Phase 1 — Testing & Web Fundamentals](#-phase-1--testing--web-fundamentals)
  * [Phase 2 — JavaScript / TypeScript](#-phase-2--javascript--typescript-for-automation)
  * [Phase 3 — Playwright Fundamentals](#-phase-3--playwright-fundamentals)
  * [Phase 4 — Real-World UI Automation](#-phase-4--real-world-ui-automation)
  * [Phase 5 — Playwright Test Framework](#-phase-5--playwright-test-framework)
  * [Phase 6 — Advanced Playwright](#-phase-6--advanced-playwright)
  * [Phase 7 — Debugging, Reporting & CI/CD](#-phase-7--debugging-reporting--cicd)
  * [Phase 8 — Real-World Automation Project](#-phase-8--real-world-automation-project)
  * [Phase 9 — Interview Preparation](#-phase-9--interview-preparation)
* [🏗️ Target Framework Structure](#️-target-framework-structure)
* [🚀 Learning Approach](#-learning-approach)
* [🎯 Final Objective](#-final-objective)

## 🎯 Learning Objectives
This repository covers the journey from **Playwright beginner to job-ready automation engineer**.

By completing the roadmap, the target capabilities are:

* Understand software testing and web application fundamentals
* Write automation using JavaScript / TypeScript
* Build UI automation with Playwright
* Use reliable locators and assertions
* Handle authentication, forms, tables, frames, tabs and dynamic elements
* Design maintainable automation frameworks
* Implement Page Object Model and fixtures
* Perform API testing using Playwright
* Handle network interception and mocking
* Execute tests across multiple browsers
* Debug failures using traces, screenshots and reports
* Integrate automation with Git and CI/CD
* Build and document a real-world automation project
* Prepare for Playwright automation interviews

## 🧩 Prerequisites

### 1. Software Testing Fundamentals

* SDLC
* STLC
* Test Scenarios
* Test Cases
* Test Data
* Defects / Bugs
* Severity & Priority
* Functional Testing
* Regression Testing
* Smoke Testing
* Sanity Testing

### 2. Web Fundamentals

* Client & Server
* Browser
* Frontend & Backend
* URL / Domain
* HTTP & HTTPS
* HTTP Methods
* HTTP Status Codes
* Request & Response
* Cookies
* Sessions
* Local Storage
* Session Storage

### 3. HTML
Basic understanding of:

```text
input
button
a
form
table
select
div
span
```

Common attributes:

```text
id
class
name
type
value
placeholder
href
```

### 4. CSS Selectors

```text
#id
.class
element
attribute selectors
parent / child
descendant
nth-child
```

### 5. JavaScript / TypeScript

Automation-focused programming knowledge:

```text
Variables
Data Types
Operators
Conditions
Loops
Functions
Arrays
Objects
Classes
Modules
JSON
Error Handling
Promises
async / await
```

### 6. Tools

* VS Code
* Terminal / Command Line
* Node.js
* npm
* Git
* GitHub

> Advanced programming or web-development knowledge is not required. The required concepts are covered from an automation perspective.

## 🗺️ Learning Roadmap

### 🟢 Phase 1 — Testing & Web Fundamentals

Build the foundation required for understanding automated web testing.

**Topics:**

* Software Testing Fundamentals
* SDLC & STLC
* Test Scenarios & Test Cases
* Defect Lifecycle
* Functional Testing
* Regression / Smoke / Sanity Testing
* Web Application Architecture
* HTML
* CSS Selectors
* HTTP Basics

**Hands-on:**

* Inspect real web applications
* Identify HTML elements
* Create CSS selectors
* Identify automation scenarios
* Write basic test cases

### 🟢 Phase 2 — JavaScript / TypeScript for Automation

Learn the programming concepts required to write Playwright tests.

**Topics:**

* Variables & Data Types
* Operators
* Conditions
* Loops
* Functions
* Arrays & Objects
* Array Methods
* Classes
* Modules
* JSON
* Error Handling
* Promises
* async / await
* Node.js
* npm
* TypeScript fundamentals

**Hands-on:**

* Build small JavaScript programs
* Process test data
* Work with JSON
* Implement reusable functions
* Practice asynchronous programming

### 🟢 Phase 3 — Playwright Fundamentals

Learn the core Playwright API and test execution model.

**Topics:**

* Playwright Architecture
* Installation & Setup
* Browser
* Browser Context
* Page
* Locators
* Actions
* Assertions
* Auto-Waiting
* Timeouts
* Debugging

**Important Locators:**

```text
getByRole()
getByText()
getByLabel()
getByPlaceholder()
getByTestId()
locator()
```

**Common Actions:**

```text
click()
fill()
check()
uncheck()
selectOption()
hover()
press()
upload()
download()
```

**Assertions:**

```text
toBeVisible()
toHaveText()
toContainText()
toHaveValue()
toHaveURL()
toHaveTitle()
toBeEnabled()
toBeDisabled()
```

**Hands-on:**

* Login automation
* Registration automation
* Search
* Forms
* Checkboxes
* Radio buttons
* Dropdowns

### 🟡 Phase 4 — Real-World UI Automation

Move beyond basic scripts and automate realistic application scenarios.

**Topics:**

* Forms
* Dynamic Elements
* Tables
* Pagination
* Filtering
* Sorting
* Frames / iFrames
* Multiple Tabs
* Popups
* Alerts
* Cookies
* Local Storage
* Session Storage
* Authentication
* `storageState`

**Hands-on scenarios:**

```text
Login
Registration
Search
Filter
Product Selection
Add to Cart
Checkout
Logout
```

### 🟡 Phase 5 — Playwright Test Framework

Learn how to build a maintainable automation framework.

**Topics:**

* Playwright Test Runner
* Test Suites
* Hooks
* Fixtures
* Configuration
* `playwright.config.ts`
* Page Object Model
* Reusable Components
* Test Data
* Parameterization
* Environment Variables

**Objective:**

> Move from writing individual automation scripts to developing a structured and maintainable automation framework.

### 🟠 Phase 6 — Advanced Playwright

Expand Playwright skills into API, network and execution capabilities.

**API Testing:**

```text
GET
POST
PUT
PATCH
DELETE
Headers
Query Parameters
Path Parameters
Request Body
Response
Status Codes
```

**Playwright API:**

```text
request.get()
request.post()
request.put()
request.delete()
```

**API + UI Automation:**

```text
Create User → API
      ↓
Login → UI
      ↓
Verify User → UI
      ↓
Delete User → API
```

**Network:**

* Request interception
* Response interception
* Mocking
* `route()`
* Network debugging

**Cross-Browser:**

```text
Chromium
Firefox
WebKit
```

**Execution:**

* Workers
* Parallel Tests
* Projects
* Retries
* Basic Sharding

### 🔵 Phase 7 — Debugging, Reporting & CI/CD

Learn how automation is executed, investigated and integrated into development pipelines.

**Debugging:**

* Playwright Inspector
* Debug Mode
* Screenshots
* Video
* Trace Viewer
* Console Logs
* Network Logs

**Reporting:**

* HTML Reports
* Test Results
* Failure Analysis
* Trace Investigation

**Git:**

```text
clone
status
add
commit
push
pull
branch
merge
```

**CI/CD:**

* GitHub Actions
* Jenkins
* Automated test execution
* Report publishing
* CI failure investigation

**Typical Pipeline:**

```text
Git Push
   ↓
CI Pipeline
   ↓
Install Dependencies
   ↓
Install Playwright
   ↓
Run Tests
   ↓
Generate Report
   ↓
Publish Results
```

### 🔴 Phase 8 — Real-World Automation Project

Build a complete automation framework demonstrating the concepts learned throughout the roadmap.

**Project:** E-Commerce Automation Framework

**UI Coverage:**

```text
Login
Registration
Product Search
Product Filter
Product Details
Add to Cart
Remove from Cart
Checkout
Logout
```

**Framework Features:**

```text
TypeScript
Playwright
Page Object Model
Fixtures
Test Data
Authentication
API Testing
API + UI
Assertions
Reusable Utilities
Environment Variables
HTML Reports
Screenshots
Trace
CI/CD
```

The project will demonstrate how individual Playwright concepts come together to form a practical automation framework.

### 🔴 Phase 9 — Interview Preparation

Prepare to explain both Playwright concepts and the automation framework developed in this repository.

**Core Interview Topics:**

* What is Playwright?
* Playwright vs Selenium
* Browser vs BrowserContext vs Page
* Locators
* Auto-Waiting
* Assertions
* Fixtures
* Hooks
* Page Object Model
* Authentication
* `storageState`
* API Testing
* Network Interception
* Mocking
* Parallel Execution
* Retries
* Projects
* Configuration
* Trace Viewer
* CI/CD

**Project Discussion:**

```text
Requirements
     ↓
Test Scenarios
     ↓
Framework Design
     ↓
Page Objects
     ↓
Test Data
     ↓
Test Execution
     ↓
Reports
     ↓
CI/CD
```

## 🏗️ Target Framework Structure

The final project will follow a structure similar to:

```text
playwright-automation/
│
├── tests/
│   ├── login.spec.ts
│   ├── product.spec.ts
│   ├── cart.spec.ts
│   └── checkout.spec.ts
│
├── pages/
│   ├── LoginPage.ts
│   ├── HomePage.ts
│   ├── ProductPage.ts
│   ├── CartPage.ts
│   └── CheckoutPage.ts
│
├── fixtures/
│   └── test.ts
│
├── test-data/
│   ├── users.json
│   └── products.json
│
├── utils/
│   ├── apiUtils.ts
│   └── dataUtils.ts
│
├── playwright.config.ts
├── package.json
└── README.md
```

## 🚀 Learning Approach

Each topic in this repository follows a practical learning cycle:

```text
Concept
   ↓
Practical Example
   ↓
Hands-on Practice
   ↓
Assignment
   ↓
Debugging
   ↓
Interview Questions
   ↓
Real-World Application
```

> **Learning principle:** Focus not only on *what* Playwright does, but also *why*, *when* and *where* each feature is used in a real automation framework.

## 🎯 Final Objective

The objective of this repository is to document a practical journey from **Playwright fundamentals to real-world automation framework development**.

The final outcome is a portfolio demonstrating:

* Automation fundamentals
* Playwright UI testing
* API testing
* Framework design
* Page Object Model
* Fixtures and test data
* Debugging and reporting
* Cross-browser testing
* Git and CI/CD integration
* Real-world automation practices

**Learn → Practice → Build → Debug → Automate → Document**
