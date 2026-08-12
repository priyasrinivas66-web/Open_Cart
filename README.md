# Open_Cart
Manual test cases and Selenium (Java) test automation framework for the OpenCart e-commerce demo application.

Overview

This repository demonstrates an end-to-end QA workflow for OpenCart:

Manual test cases covering core storefront and admin flows
Automated regression tests built with Selenium WebDriver + Java, using the Page Object Model (POM)
CI pipeline via GitHub Actions that runs the automation suite on every push

Repository Structure

opencart-testing-showcase/
├── manual-testcases/
│   ├── login_testcases.md
│   ├── registration_testcases.md
│   ├── checkout_testcases.md
│   └── ...
├── automation/
│   ├── src/
│   │   ├── main/java/          # framework utilities (driver factory, config reader, etc.)
│   │   └── test/java/
│   │       ├── pages/          # Page Object classes
│   │       ├── tests/          # TestNG test classes
│   │       └── utils/          # test data, waits, helpers
│   ├── pom.xml
│   └── testng.xml
├── .github/
│   └── workflows/
│       └── selenium-tests.yml  # CI pipeline
└── README.md
