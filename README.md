# PetStore API Testing Framework
## Project Overview
This project implements a comprehensive testing framework for the PetStore Swagger API, including manual testing, automation, CI/CD integration, and containerization.

## Tools & Technologies

* API Testing: Postman, Swagger UI
* Automation: SoapUI
* CI/CD: Jenkins
* Containerization: Docker

## Repository Structure

* PAIM-Project-soapui-project.xml: SoapUI project file
* Testplan_APITesting.xlsx: Detailed test cases and results
* TestResultsDocument_PAIM: Screenshots and logs from manual tests

## Setup & Execution

* Clone the repository
* Install SoapUI, Jenkins, and Docker
* Import the SoapUI project file
* Configure Jenkins job using the provided Jenkinsfile
* Run the Jenkins job to execute tests and generate reports

## Test Suites

* EverythingAboutPets
* AccessToPetStoreOrders
* OperationsAboutUser

## Key Features

* CRUD operation testing
* Performance testing with 50 threads for 300 seconds
* Automated test execution via Jenkins
* Dockerized test environment

## Contribution
For any improvements or issues, please open a pull request or issue in this repository.