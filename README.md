Sauce Demo Automation Framework

Overview
This repository contains an automation framework for the Sauce Demo website using Cucumber BDD, Page Object Model (POM), and Extent Report. The framework is designed to automate key scenarios of the Sauce Demo application and provides detailed test results in Extent Reports.

Table of Contents
Prerequisites
Getting Started
Project Structure
Configuration
Running Tests
Generating Extent Reports
Contributing
License
Prerequisites
Ensure you have the following installed on your machine:

Java (version X.X)
Maven (version X.X)
WebDriver (e.g., ChromeDriver, GeckoDriver) compatible with your browser
Getting Started
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/sauce-demo-automation.git
Navigate to the project directory:

bash
Copy code
cd sauce-demo-automation
Install dependencies:

bash
Copy code
mvn clean install
Project Structure
The project follows the standard structure of a Cucumber and Page Object Model (POM) framework. Key directories include:

src/test/java: Contains test scenarios and step definitions.
src/main/java: Includes page objects and utility classes.
src/test/resources: Contains feature files and configuration files.
target: Default directory for compiled classes and generated reports.
Configuration
Update the configuration files in the src/test/resources directory to set up your test environment. Key configuration files include:

config.properties: Configure browser, application URL, etc.
extent-config.xml: Customize Extent Report settings.
Running Tests
Execute the following command to run the tests:

bash
Copy code
mvn clean test
Specify the browser and other configurations in the config.properties file.

Generating Extent Reports
Extent Reports are automatically generated after each test run. Access the reports in the target/reports directory.
