## **💻 Project: Product Catalog Microservice – TDD & BDD (IBM DevOps Specialization)**

### **Summary**

> **Engineered a production-style microservice with 95%+ automated test coverage, combining TDD/BDD, Selenium UI automation, and robust API development to deliver a highly reliable and maintainable backend system.**

---
**Role:** QA / Test Automation / DevOps Engineer
**Tech:** Python, Flask, TDD/BDD, Nose, Selenium, Behave, GitHub, CI practices, Mocking & Fixtures
**Focus:** Automated Testing • API Quality • Systems Integration • Software Engineering

---

### **TDD for API Development (STAR)**

**Situation —** Needed to build a stable, scalable REST API microservice for an eCommerce product catalog capable of frequent updates without regressions.

**Task —** Implement all CRUD + search endpoints using strict TDD, targeting **95%+ code coverage** and zero linting issues.

**Action —**

* Applied full **Red → Green → Refactor** cycle for every API function.
* Built comprehensive **unit, integration, and system tests** using Nose; used **fixtures & mocking** to isolate components.
* Completed all missing business logic and finalized Create/Read/Update/Delete/List endpoints.

**Result —** Delivered a **highly maintainable** API with **95%+ test coverage**, all tests green, clean linting, and significantly reduced defect risk during future iterations.

---

### **BDD for UI Validation (STAR)**

**Situation —** After API completion, the system needed validation from the admin user’s perspective to ensure UI + backend behaviors matched business rules.

**Task —** Define and automate **BDD scenarios** to validate CRUD and search workflows from the UI.

**Action —**

* Authored **7 BDD scenarios** (CRUD, search by category/name/availability) using *Given–When–Then*.
* Set up BDD test environment with **Behave + Selenium**, including automated service data loading per scenario.
* Implemented reusable step definitions and stable automated flows.

**Result —** All scenarios passed, confirming end-to-end correctness. Delivered business-readable acceptance tests and ensured UI/API alignment for real user workflows.

---
