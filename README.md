# Project Amazon

## Description
This GitHub repository contains a Java Maven project for automated testing using Selenide, WebDriverManager, and Allure reporting. The project is integrated with Jenkins for continuous integration and automated test execution.

## Features
- Automated web testing with Selenide.
- Easy browser setup and management using WebDriverManager.
- Detailed test reports and visualization with Allure.
- Continuous integration and automated testing with Jenkins.

## Prerequisites
Before running the tests, make sure you have the following prerequisites installed:
- Java
- Maven
- Selenide
- WebDriverManager
- Allure
- Jenkins (for CI/CD)

## Installation
1. Clone this repository to your local machine.
2. Make sure you have all the prerequisites installed.
3. Configure your test environment and URLs in the appropriate configuration files.
4. Run the tests using Maven: mvn clean test
5. Generate Allure reports: allure generate allure-results --clean -o allure-report
6. View the test reports in the `allure-report` directory.

## Usage
- Customize and expand the existing test suites to suit your project's needs.
- Integrate this repository with your Jenkins server for automated test runs.

## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and contributions are highly appreciated.
  
## Contact
If you have questions or need further assistance, please contact Serhii at s.polishevskyi@gmail.com

Happy testing! 🚀
