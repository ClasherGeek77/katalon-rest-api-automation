# UNI Katalon REST API Automation 🔌
A comprehensive demonstration of RESTful API Automation using **Katalon Studio**. This repository provides an end-to-end framework pattern for validating JSON payloads, HTTP status codes, and multi-step API workflows.

## 🎯 Objective
To demonstrate an API-first testing approach that bypasses the UI layer for ultra-fast execution, validating core business logic, status codes, and contract integrity.

## 🏗 Architecture & Technologies
- **Test Engine**: Katalon Studio (API/Web Services module)
- **Target**: RESTful Endpoints (GET, POST, PUT, DELETE)
- **Validation**: JSON Path assertions, Groovy scripting

## ⚙️ Key Concepts Demonstrated
1. **Object Repository (API)**: Centralized management of endpoint URLs, Headers, Authorization tokens, and Body payloads.
2. **Chained Requests**: Extracting a token/ID from a POST response and passing it dynamically to a subsequent GET/PUT request via Global Variables.
3. **Data-Driven Execution**: Testing multiple users/scenarios via external datasets.
4. **Environment Profiles**: Seamlessly switching between QA, Staging, and Production API environments using Katalon Execution Profiles.

## 🚀 Getting Started
1. Clone this repository.
2. Open the project folder in **Katalon Studio**.
3. Select an execution profile (`Staging` / `Production`).
4. Run the Test Suite to execute the API workflows.

> *"I don't just automate tests. I build testers."* — Teddy Lioner
