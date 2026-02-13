# Enterprise-Style BDD Automation Framework (OpenCart)

## 📌 Project Overview

This project demonstrates an enterprise-level Behavior Driven Development (BDD) automation framework built using **Cucumber, Java, Selenium WebDriver, and Maven**.

The framework is designed to reflect real-world QA automation practices including:
- Scalable architecture
- Maintainable test design
- Business-readable feature files
- Reusable step definitions
- CI-ready execution structure
- Reporting and logging integration

The automation is implemented against a public OpenCart sample e-commerce application to simulate real-world web application testing.

---

## 🚀 Objectives

- Demonstrate strong understanding of BDD principles
- Showcase automation framework design skills
- Implement maintainable Page Object Model architecture
- Apply industry-level QA best practices
- Enable scalable and reusable automation structure

---
## 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| Java | Programming Language |
| Selenium WebDriver | UI Automation |
| Cucumber | BDD Framework |
| Maven | Build & Dependency Management |
| JUnit/TestNG | Test Runner |
| WebDriverManager | Driver Management |
| Extent Reports / Cucumber Reports | Reporting |
| Git | Version Control |

---

## 🧠 Key Features

✔ Behavior Driven Development using Cucumber  
✔ Gherkin feature files mapped to business requirements  
✔ Page Object Model (POM) design pattern  
✔ Reusable step definitions  
✔ Centralized WebDriver management  
✔ Test data handling strategy  
✔ Configurable environment setup  
✔ Maven build lifecycle integration  
✔ Detailed test reporting  
✔ CI-ready framework structure  

---
## 🏗 Framework Architecture

src
├── main
│   ├── java
│   │   ├── pages
│   │   ├── utilities
│   │   └── drivers
├── test
│   ├── java
│   │   ├── stepdefinitions
│   │   ├── runners
│   ├── resources
│   │   ├── features
│   │   └── config.properties


### Architecture Design Principles

- **Separation of Concerns**
- **Reusable Components**
- **Low Maintenance Structure**
- **Scalable for Large Test Suites**
- **Business-Readable Test Scenarios**

---
## 🔧 Prerequisites

Ensure the following are installed:

- Java JDK 8 or higher
- Maven
- IDE (IntelliJ / Eclipse)
- Git
- Chrome/Edge browser
- Internet connection

---
## ⚙ Installation

1. Clone the repository:

   git clone https://github.com/your-username/project-name.git

2. Navigate to the project directory:

   cd project-name

3. Install dependencies:

   mvn clean install
---
## ⚙ Configuration

The framework uses a config.properties file to manage:

- Base URL
- Browser type
- Environment
- Timeout values

This enables easy environment switching without code changes.

---

## ▶ How to Run Tests

### Run All Tests

mvn clean test

### Run by Tags

mvn test -Dcucumber.filter.tags="@smoke"

### Run in Headless Mode

mvn test -Dbrowser=chrome -Dheadless=true

---
## 🧵 Parallel Execution

Framework supports parallel execution via Maven Surefire plugin configuration.
---
## 📊 Reporting

After test execution, HTML reports are generated providing:

- Scenario-level execution status
- Pass/Fail summary
- Execution logs
- Failure screenshots (if configured)

Reports help stakeholders quickly assess build health and test coverage.

---
## 📖 Sample Feature File (BDD Example)

```gherkin
Feature: User Login Functionality

  Scenario: Valid user should login successfully
    Given User is on the login page
    When User enters valid username and password
    And User clicks on login button
    Then User should be redirected to the account dashboard
```
---

## 👩‍💻 Author

**Pragya Sharma**  
Software QA Engineer 

📧 Email: sharmapragya312@gmail.com  
🔗 GitHub: [pragyasharmaqa](https://github.com/pragyasharmaqa)


