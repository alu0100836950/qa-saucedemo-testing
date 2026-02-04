# QA Automation Project – SauceDemo

## Overview
This project focuses on practicing QA fundamentals and automation using the SauceDemo web application.
The goal is to identify functional issues, document bugs, and build automated tests for critical flows
while applying professional QA methodology.

SauceDemo is an e-commerce demo site with user authentication, product browsing, cart management,
and checkout flows. It is ideal for practicing exploratory testing, automation, and data validation.

---

## Objectives
- Perform exploratory testing to detect functional and UI issues
- Design and document test cases and bug reports
- Automate critical user flows with Pytest + Playwright
- Validate data consistency between UI and backend (if applicable)
- Learn professional QA practices and documentation

---

## Application Under Test
- URL: [https://www.saucedemo.com](https://www.saucedemo.com)
- Features:
  - User login/logout
  - Product browsing and sorting
  - Cart management
  - Checkout workflow

---

## 🔍 Test Scope
**In scope:**
- User login/logout
- Product listing, sorting, and filtering
- Add/remove products from cart
- Checkout flows and form validation
- Automated UI and API tests

**Out of scope (for now):**
- Performance / load testing
- Security / penetration testing
- Cross-browser testing beyond Chrome/Edge
- Payment gateway internal logic (mocked or sandbox only)

---

## Test Types Applied
- Functional testing
- Exploratory testing
- Smoke testing
- Regression testing (manual and automated)
- Data validation (using Python / pandas)

---

## Bug Reporting Methodology
Bugs are documented individually under `bug-reports/` with the following structure:

```

Title: [BUG] 
Environment: Browser / OS / URL
Preconditions: Steps needed before reproduction
Steps to reproduce: Step-by-step instructions
Expected result: What should happen
Actual result: What actually happens
Severity: High / Medium / Low
Priority: High / Medium / Low
Attachments: Screenshot / video (optional)

```