# UI Test Automation Framework 
(.NET | C# | Selenium | API | SpecFlow BDD)

## Overview

This project is a test automation framework built with .NET and C#, designed to validate both UI and API layers of modern web applications and test writted in Guerkin syntax (BDD)
It follows best practices such as Page Object Model (POM), modular architecture, and reusable components to ensure scalability, maintainability, and reliability of automated tests.
The framework supports end-to-end testing, covering user workflows from UI interactions to backend API validations.

## 🛠 Tech Stack
*   **Language**: C#
*   **Behavior Driven Development**: [SpecFlow](https://specflow.org/)
*   **UI Automation**: [Selenium WebDriver](https://selenium.dev)
*   **API Testing**: [RestSharp](https://restsharp.dev) / [HttpClient](https://microsoft.com)
*   **Test Runner**: [xUnit](https://xunit.net) / [NUnit](https://nunit.org)
*   **Design Pattern**: Page Object Model (POM)
*   **Build Tool**: .NET CLI

## Architecture
The framework is structured to separate concerns and promote reusability:

UI-test-framework

├── Pages   → Page Objects (UI interactions)
├── Tests   → Test cases (UI & API)
├── API     → API clients and services
├── Models  → Data models / DTOs
├── Utils   → Helpers, utilities, configuration
├── Drivers → WebDriver setup and management
└── Config  → Environment configuration


 Key Principles:
*  Separation of concerns
*  Reusable components
*  Readable and maintainable tests
*  Scalable for enterprise-level projects

## Future Improvements
*  CI/CD integration (GitHub Actions / Azure DevOps)
*  Test reporting (Allure / ExtentReports)
*  Parallel execution
*  Cross-browser testing
*  Test data management strategy
