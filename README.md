# Hi, I'm Reuben Silerio 👋

**QA Engineer · Manual & Cross-Platform Testing · UI Automation & API Testing Portfolio**

📍 Philippines

[Selenium Portfolio](https://github.com/siler1o/selenium-qa-automation-portfolio) · [Postman API Portfolio](https://github.com/siler1o/postman-api-testing-portfolio) · [Live Allure Report](https://siler1o.github.io/selenium-qa-automation-portfolio/) · [Test Case Tracker](https://docs.google.com/spreadsheets/d/1E-rbgsHj4jv7pamglMdsREiQnfcl-aHWACqrRmAwD3w/edit?usp=drivesdk)

## 👨‍💻 About Me

I'm a QA Engineer with professional experience in manual testing, cross-platform validation, defect management, and QA team coordination. My work has covered PC/Web, Android, iOS, and mobile web (H5), from pre-production checks to production validation.

I'm building on that foundation through personal projects in **UI automation with Python, Selenium WebDriver, and Pytest**, and **API testing with Postman and JavaScript**. I focus on understanding what a test proves, writing meaningful assertions, and making results easy for others to review.

## 🧪 What I Bring to QA

- **Team coordination:** coordinated a six-person QA team, assigned testing work, followed up on defects, and communicated testing progress and release risks.
- **Test documentation:** created and maintained **400+ test cases** and authored **100+ SOPs** to support consistent testing and team workflows.
- **Functional and release testing:** hands-on experience with smoke, regression, exploratory, UAT, QAT, blue-green deployment validation, and pre-production/production checks.
- **Cross-platform coverage:** validated web and mobile experiences across browsers, Android, iOS, and H5 environments.
- **Defect follow-through:** documented reproduction steps and expected results, retested fixes, and coordinated with developers and operations teams.

These highlights describe my professional QA background. The UI automation and API testing work below comes from personal portfolio projects documenting my continued learning.

## 🛠️ Tools & Practices

### Hands-on Portfolio Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-166534?style=for-the-badge&logo=selenium&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A6B8A?style=for-the-badge&logo=pytest&logoColor=white)
![Allure](https://img.shields.io/badge/Allure-6F42C1?style=for-the-badge)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-C73A24?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

- **UI automation:** Page Object Model (POM), shared Pytest fixtures, reusable locators, and explicit waits with `WebDriverWait` and Expected Conditions.
- **API validation:** Postman requests, environment variables, form-data bodies, JSON parsing, and JavaScript assertions for status codes, messages, and returned data.
- **Test data:** UUID-based registration emails in Selenium and timestamp-based test emails in Postman.
- **Reporting and CI:** Allure steps and metadata, pytest-html summaries, Postman execution screenshots, and a GitHub Actions workflow for Selenium execution and Allure report publication.

### Professional QA Workflow

**Lark · Meegle · TestFlight · Google Play Console**

Test-case design, bug reporting, retesting, release-readiness communication, and Agile/Kanban collaboration.

## 🚀 Featured Projects

### [Selenium QA Automation Portfolio](https://github.com/siler1o/selenium-qa-automation-portfolio)

UI automation for the public **Automation Exercise** practice website, connecting documented test cases with executable checks and reviewable evidence.

**Current scope: 19 automated UI scenarios out of 26 planned.**

[![Selenium CI/CD](https://github.com/siler1o/selenium-qa-automation-portfolio/actions/workflows/selenium-ci.yml/badge.svg?branch=main)](https://github.com/siler1o/selenium-qa-automation-portfolio/actions/workflows/selenium-ci.yml)

**Verified on September 28, 2026:** [all 19 tests passed in GitHub Actions, and Allure report deployment succeeded](https://github.com/siler1o/selenium-qa-automation-portfolio/actions/runs/36410035949).

- Registration, valid/invalid login, logout, and duplicate-email validation.
- Contact-form submission with an attachment and confirmation checks.
- Test Cases navigation, product listing, and product-detail validation.
- Product search with non-empty results and a relevance check for every returned card.
- Homepage and cart subscriptions, multi-product cart validation, and product-quantity checks.
- Checkout and order placement through registration during checkout, registration before checkout, and login before checkout.
- Delivery and billing address checks, payment-form submission, and order confirmation.
- Product removal with empty-cart verification, plus category and brand navigation with visible product listings.

Tests use reusable page objects, explicit waits, and shared browser fixtures. Product names and prices are captured before cart validation, and registration flows use unique test emails. The login-before-checkout scenario creates its own account, signs out, then signs back in before ordering.

GitHub Actions runs the Selenium suite in headless Chrome on pull requests and pushes to `main`. Successful `main` runs generate and deploy the Allure report to GitHub Pages. Raw test results are retained as downloadable workflow artifacts, including when tests fail.

[Browse the code](https://github.com/siler1o/selenium-qa-automation-portfolio) · [Explore the report](https://siler1o.github.io/selenium-qa-automation-portfolio/) · [View CI workflow](https://github.com/siler1o/selenium-qa-automation-portfolio/blob/main/.github/workflows/selenium-ci.yml)

### [Postman API Testing Portfolio](https://github.com/siler1o/postman-api-testing-portfolio)

Functional API testing against the public **Automation Exercise** practice API, with **14 positive and negative scenarios** and JavaScript after-response assertions.

- Product and brand retrieval, product search, login verification, and unsupported-method checks.
- GET, POST, PUT, and DELETE requests using query parameters and form-data bodies.
- Environment variables and dynamic registration emails for disposable test accounts.
- Separate validation of HTTP status and the application-level `responseCode` in JSON, plus response fields and expected values.
- Account lifecycle checks: create, update, retrieve the changed details, then delete the test account.
- Documented test cases and screenshots connecting expected results with observed responses.

[Browse the collection and sample environment](https://github.com/siler1o/postman-api-testing-portfolio/tree/main/postman) · [View test cases](https://github.com/siler1o/postman-api-testing-portfolio/tree/main/test-cases) · [View execution screenshots](https://github.com/siler1o/postman-api-testing-portfolio/tree/main/screenshots)

## 🌱 Currently Working On

- Completing the remaining seven Selenium scenarios, starting with product search and cart persistence after login (TC020).
- Strengthening checkout assertions, including order totals and more precise address validation.
- Strengthening Python and JavaScript fundamentals, reusable test code, and clear failure messages.
- Preparing repeatable Postman collection runs and learning command-line API execution with Newman.
- Improving failure-evidence capture and test-account setup and cleanup.

## 🤝 Professional Focus

I'm interested in **QA Engineer opportunities** where I can contribute manual testing, test design, and team coordination while continuing to grow in UI automation and API testing.

I enjoy turning a test case into a check I can explain—and sharing the evidence behind the result.
