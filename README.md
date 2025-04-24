Cypress + TypeScript + Cucumber and HTML Reporting
 
Cypress/Typrescript/Cucumber/ Project runbook:
-----------------

This project is a Cypress automation framework using TypeScript and Cucumber for Behavior-Driven Development (BDD). It includes support for generating detailed HTML reports with multiple-cucumber-html-reporter.

**PreRequisites:**
--> install Node latest version 13.X

**Installation & Setup**

1️⃣ **Clone the Repository**

git clone https://github.com/kurrt9/VK_25_APR.git

cd VK_25_APR

2️⃣ **Install Dependencies**

npm install

Running Tests:
--------------

Run Cypress in Interactive Mode

  **npm run cypress:open**

Run Cypress in Headless Mode

  **npm run cypress:run**

Generating HTML Reports:
-----------------------

1️) Run Cypress Tests

Ensure test execution generates JSON reports.

  **npm run cypress:run**

2️) Generate HTML Report

  **npm run generate-report**

3) Run Tests in parallel (Feature File wise)

  **node run-parallel.js**

4) Run Tests based on Cucumber Tags

  **npx cypress run --env tags="@Test"**

