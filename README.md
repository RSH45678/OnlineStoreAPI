# 🛒 Online Store API Automation (User, Product & Cart)

## 🔍 Project Overview

This repository contains automated API testing for an **Online Store application**, covering **User, Product, and Cart modules**. The project ensures API reliability through structured test cases, validation scripts, and automated execution using multiple tools.

---

## 🚀 Key Features

* 🔹 Automated testing for **User, Product, and Cart APIs** using Postman
* 🔍 Validated **status codes, headers, response body, and schema**
* ⚙️ Executed tests using **Newman CLI, Postman CLI, and Jenkins**
* 🛡️ Ensured API reliability, stability, and proper error handling

---

## 📁 Project Structure

```id="repo-structure"
├── Cart.postman_collection.json        # Cart module API tests
├── Products.postman_collection.json    # Product module API tests
├── User.postman_collection.json        # User module API tests
├── products_data.csv                   # Test data for product APIs
├── workspace.postman_globals.json      # Global variables for Postman
├── newman/                             # Newman execution configs/scripts
├── results/                            # Test execution reports
└── README.md                           # Project documentation
```

---

## 🛠️ Tools & Technologies

* **Postman** – API test creation and automation
* **Newman CLI** – Command-line execution of Postman collections
* **Postman CLI** – Running collections and managing workflows
* **Jenkins** – Continuous Integration and automated execution
* **JavaScript** – Writing test scripts and validations

---

## 🧪 Test Coverage

* ✅ API endpoint validation
* ✅ HTTP status code checks
* ✅ Response header validation
* ✅ Response body verification
* ✅ Schema validation
* ✅ Error handling and edge case testing

---

## ▶️ Running Tests Locally

### Prerequisites

* Node.js installed
* Newman installed globally:

```bash id="install-newman"
npm install -g newman
```

### Execute a Collection

```bash id="run-tests"
newman run User.postman_collection.json
```

### Run with Data File

```bash id="run-data"
newman run Products.postman_collection.json -d products_data.csv
```

---

## 📊 Test Reports

* Execution results are stored in the **`results/`** folder
* Includes detailed logs of test cases, pass/fail status, and errors

---

## 🔄 CI/CD Integration

* Integrated with **Jenkins** for automated test execution
* Supports execution via:

  * Newman CLI
  * Postman CLI
* Enables continuous testing on build/deployment pipelines

---

## 🎯 Goals Achieved

* Improved API quality and reliability
* Automated repetitive testing workflows
* Ensured consistent validation across multiple modules

---

## 📌 Conclusion

This project demonstrates a robust API automation framework for an e-commerce system, combining Postman collections, scripting, and CI tools to deliver reliable and maintainable API testing.

---
