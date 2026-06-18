# QA82_FirstCucumber – My First Cucumber + Selenium Project


# QA82_FirstCucumber – My First BDD Automation Framework

A learning project implementing **Behavior-Driven Development (BDD)** automation tests for the PhoneBook web application (https://contacts-app.tobbymarshall815.vercel.app/) using **Cucumber**, **Selenium WebDriver**, and **Page Object Model (POM)** in Java with Gradle.

## Project Description
- Automated scenarios: login, navigation, adding/editing contacts.
- Written in Gherkin for readability and collaboration.
- Uses clean POM for maintainable, reusable code.

## Technologies
- Java 11+(21.x)
- Cucumber 7.x
- Selenium WebDriver 4.x
- Gradle 8.x
- WebDriverManager (recommended)

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/DInnaD/QA_82PhoneBook_New.git

Run tests:bash

./gradlew clean test

Cucumber reports will appear in build/reports/ or configured target folder.

Structuresrc/main/java/com/ait/pages/ → Page Objects (BasePage, LoginPage, ContactPage, etc.)
src/test/resources/features/ → Gherkin feature files
src/test/java/com/ait/stepDefinitions/ → Step definition classes
src/test/java/com/ait/TestRunner.java → Cucumber runner

Planned: Add HTML reports (Cucumber plugin), tags (@smoke
, @regression
), Hooks for driver management.

Minor Enhancements:Reports: Add Cucumber HTML reporter plugin in TestRunner @CucumberOptions.
Hooks: Create a Hooks class for @Before
/@After
 (driver init/close, screenshots on failure).
Tags: Add @smoke
, @regression
 to features/scenarios.
GitHub Description: Add a short summary in repo settings.




This is a learning project focused on automating web application testing using **Cucumber (BDD)**, **Selenium WebDriver**, and the **Page Object Model (POM)** in Java with Gradle.

https://rahuldkjain.github.io/gh-profile-readme-generator/
https://github.com/kefranabg/readme-md-generator/blob/master/CONTRIBUTING.md
