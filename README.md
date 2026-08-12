# Open_Cart
Manual test cases and Selenium (Java) test automation framework for the OpenCart e-commerce demo application.

Overview

This repository demonstrates an end-to-end QA workflow for OpenCart:

Manual test cases covering core storefront and admin flows
Automated regression tests built with Selenium WebDriver + Java, using the Page Object Model (POM)
CI pipeline via GitHub Actions that runs the automation suite on every push

Modules Automated
User Login & Registration
Product Search & Filter
Add to Cart / Update Cart
Checkout Flow (Guest & Registered)

Automation Framework
Aspect	Details
Language	Java 17
Build Tool	Maven
Test Runner	TestNG
Design Pattern	Page Object Model (POM) + Page Factory
Browser Driver	Selenium WebDriver 4.x (WebDriverManager for driver binaries)
Reporting	TestNG HTML reports / ExtentReports
Waits	Explicit waits (WebDriverWait) — no hardcoded Thread.sleep()


