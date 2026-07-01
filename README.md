# 🚀 Hybrid Automation Framework

A scalable, enterprise-ready Hybrid Test Automation Framework built using **Java, Selenium WebDriver, TestNG, Rest Assured, Maven, and Jenkins**. The framework supports both **UI Automation** and **API Automation** while following clean architecture, reusable utilities, and industry best practices.

---

# 📌 Features

## ✅ UI Automation

* Selenium WebDriver
* Java 17
* TestNG
* Page Object Model (POM)
* ThreadLocal Driver Management
* Cross Browser Support
* Headless Execution
* Explicit Wait Utilities
* JavaScript Utilities
* Screenshot Utility
* Retry Analyzer
* Extent Reports
* Log4j2 Logging

---

## ✅ API Automation

* REST Assured
* GET API Testing
* POST API Testing
* PUT API Testing
* PATCH API Testing
* DELETE API Testing
* Authentication Framework
* Request Specifications
* Response Specifications
* JSON Schema Validation
* Path Parameters
* Query Parameters
* Serialization
* Deserialization
* Reusable API Validator

---

## ✅ Data-Driven Testing

* TestNG DataProvider
* External JSON Test Data
* Jackson ObjectMapper
* Reusable JSON Data Reader

---

## ✅ CI/CD & DevOps

* Maven
* Jenkins Freestyle Jobs
* Jenkins Pipeline
* GitHub Integration

---

# 🏗️ Project Structure

```text
src
├── main
│   └── java
│       ├── api
│       │   ├── auth
│       │   ├── endpoints
│       │   ├── models
│       │   ├── specs
│       │   └── utils
│       ├── base
│       ├── drivers
│       ├── factory
│       ├── listeners
│       ├── pages
│       └── utilities
│
└── test
    ├── java
    │   ├── tests
    │   ├── utilities
    │   └── testdata
    │
    └── resources
        ├── config
        ├── schemas
        └── testdata
```

---

# 🧪 Framework Highlights

### UI Framework

* Hybrid Framework Design
* Page Object Model (POM)
* Thread-safe DriverFactory
* Cross Browser Execution
* Environment Configuration
* Rich Reporting
* Logging
* Utility Classes

### API Framework

* Modular API Endpoints
* Authentication Layer
* Centralized Request Specification
* Centralized Response Specification
* Generic API Validation
* JSON Schema Validation
* Data-Driven API Testing
* Externalized Test Data

---

# ▶️ Running the Framework

## Run Complete Test Suite

```bash
mvn clean test
```

## Run UI Test Suite

Execute:

```text
testng.xml
```

## Run API Test Suite

Execute:

```text
testng-api.xml
```

---

# 📊 Reporting

The framework generates:

* Extent Reports
* TestNG Reports
* Console Logs
* Log4j2 Logs

---

# 🔄 CI/CD

The framework is integrated with:

* Jenkins Freestyle Jobs
* Jenkins Pipeline
* GitHub

---

# 🚀 Upcoming Enhancements

* Generic JSON Data Reader
* Docker Integration
* Docker Compose
* Selenium Grid
* Parallel Execution
* GitHub Actions
* Dynamic Test Data Generation
* Allure Reporting

---

# 🛠️ Technology Stack

| Category        | Technologies       |
| --------------- | ------------------ |
| Language        | Java 17            |
| UI Automation   | Selenium WebDriver |
| API Automation  | REST Assured       |
| Test Framework  | TestNG             |
| Build Tool      | Maven              |
| Reporting       | Extent Reports     |
| Logging         | Log4j2             |
| CI/CD           | Jenkins            |
| Version Control | Git & GitHub       |
| Data Format     | JSON               |
| JSON Library    | Jackson            |

---

# 👨‍💻 Author

**Alok Patel**

Software QA Engineer | SDET