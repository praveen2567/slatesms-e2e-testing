## Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Infrastructure & Security](#infrastructure--security)
- [School Management](#school-management)
- [Learning & Assessment](#learning--assessment)
- [Analytics & Reporting](#analytics--reporting)
- [Communication](#communication)
- [Premium Add-ons](#premium-add-ons)
- [Pricing Tiers](#pricing-tiers)
- [Who It's For](#who-its-for)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Roles & Responsibilities](#roles--responsibilities)
- [Tech Stack & Prerequisites](#tech-stack)
- [Key Achievements](#key-achievements)
- [Business Impact](#business-impact)
- [Running Tests in CI/CD](#running-tests-in-cicd)
- [Reporting](#reporting)
- [Configuration](#configuration)
- [Writing New Tests](#writing-new-tests)
- [Contribution](#contribution)
- [Support](#support)
- [Links](#links)

# SlateSMS - School Management System

# PROJECT OVERVIEW

SlateSMS is an AI-powered school management platform designed to help educational institutions streamline operations, enhance learning, and improve communication. It’s built for scalability, security, and customization ideal for schools, districts, and networks.

As part of the QA Automation team, I contributed to building and maintaining the test infrastructure that ensured product reliability across modules such as:

**Admissions & Enrollment:** Online forms, document uploads, and automated tracking

**Fee Management:** Digital invoicing, payment gateway integration, and reminders

**Smart Scheduling:** AI-driven timetable optimization

**Learning & Assessment:** LMS tools, quizzes, and progress tracking

**Communication:** Parent portals, mobile apps, and AI chatbots

# KEY FEATURES
# Infrastructure & Security
1. **Cloud-native platform:** Access from any device, anywhere.

2. **Enterprise-grade security:** Protects sensitive data.

3. **Role-based access control:** Custom permissions for admins, teachers, parents, and students.

4. **Audit logs & compliance:** Supports FERPA and GDPR standards.

5. **Multi-tenant & multi-language support:** Ideal for districts and diverse communities.

# School Management
1. Staff & student directories

2. Online admissions & enrollment

3. Fee management with payment gateway integration

4. AI-powered scheduling

5. Event & calendar coordination

# Learning & Assessment
1. Built-in LMS for course materials, assignments, and quizzes

2. Assessment tools with analytics and reporting

# Analytics & Reporting
1. Student performance dashboards

2. Predictive analytics

3. Custom report builder with drag-and-drop interface

# Communication
1. Parent portal & mobile app with real-time updates

2. AI chatbots for instant support

# Premium Add-ons
1. Gamification modules for engagement

2. Career counseling powered by AI

3. Third-party integrations (Zoom, Google Classroom, Microsoft Teams)

# Pricing Tiers  

| Plan       | Ideal For        | Key Highlights                        |
|------------|------------------|---------------------------------------|
| **Basic**      | Small schools     | Free forever, up to 100 students       |
| **Pro**        | Growing schools   | $5/user/month, advanced analytics      |
| **Enterprise** | Large institutions| Custom pricing, full customization     |

# Who It's For
SlateSMS offers tailored solutions for:

1. **Administrators:** Dashboards, budgeting, compliance

2. **Teachers:** Lesson planning, grading, performance tracking

3. **Parents & Students:** Progress tracking, communication, scheduling

## Getting Started

Follow these steps to set up the project and run the Playwright automation tests:

1. **Clone the repository**
   ```bash
   git clone https://github.com/praveen2567/slatesms-e2e-testing.git
   cd slatesms-e2e-testing
   ```

2. **Install dependencies**  
   Make sure you have [Node.js](https://nodejs.org/) installed (v18+ recommended).
   ```bash
   npm install
   ```

3. **Install Playwright Browsers**  
   (If not handled automatically by `npm install`)
   ```bash
   npx playwright install
   ```

4. **Run the tests**
   ```bash
   npx playwright test
   ```

5. **View test results**  
   After tests complete, you can view the HTML report:
   ```bash
   npx playwright show-report
   ```

---


## Project Structure

```
slatesms-e2e-testing/
│
├── tests/                      # Feature-based test specs
│   ├── login.spec.js
│   ├── dashboard/
│   │   └── dashboard.spec.js
│   └── admissions/
│       └── admissions.spec.js
│
├── pages/                      # Page Object Model (POM) classes
│   ├── LoginPage.js
│   ├── DashboardPage.js
│   └── AdmissionsPage.js
│
├── data/                       # Test data for data-driven testing
│   ├── loginData.json
│   ├── studentProfiles.json
│   └── feeScenarios.csv
│
├── fixtures/                   # Reusable fixtures and mock setups
│   ├── baseFixture.js
│   └── apiMocks.js
│
├── utils/                      # Helper functions, custom commands
│   ├── generateTestUser.js
│   ├── apiClient.js
│   └── logger.js
│
├── config/                     # Environment configs (dev, staging, prod)
│   ├── dev.env.js
│   ├── staging.env.js
│   └── prod.env.js
│
├── reports/                    # Auto-generated test reports
│   ├── allure-results/
│   ├── html-report/
│   └── traces/
│
├── .github/
│   └── workflows/
│       └── playwright-ci.yml   # GitHub Actions for CI/CD
│
├── playwright.config.js        # Core Playwright config
├── package.json                # Dependencies & scripts
├── README.md                   # Project overview and instructions
└── .env                        # Secrets and environment variables
```



---

## Roles & Responsibilities
- Designed and built **BDD-driven Playwright framework** from scratch.  
- Developed and maintained **Page Object Model (POM)** for scalability.  
- Automated **100+ regression & smoke test cases** (UI + API).  
- Integrated framework with **GitHub Actions** for CI/CD pipelines.  
- Configured **Allure Reports** for test visibility and traceability.  
- Implemented **parallel execution** for faster test runs.  
- Collaborated with developers & QA team for **shift-left testing**.  
- Maintained **test data and environment configurations**.  
- Troubleshot flaky tests and applied **retry logic**.  
- Participated in **Agile ceremonies (sprint planning, retrospectives, daily stand-ups)**.  

---

## Tech Stack
To build and execute this framework, the following tools and setup were used:

- **Programming Language:** JavaScript (ES6+)
- **Automation Tool:** Playwright
- **Test Runner:** Mocha, Playwright Test
- **Framework Pattern:** Page Object Model (POM)
- **Reporting:** Allure Reports
- **CI/CD:** GitHub Actions
- **Other Tools:** Node.js, npm, Git, GitHub, Postman, Jira
- **Browsers:** Chromium, Firefox, WebKit

---

## Key Achievements
- Automated **100+ test scenarios** (UI + API).  
- Reduced **manual regression time by 70–80%**.  
- Achieved **85% pass rate** in regression pipelines.  
- Delivered **98% defect-free releases across 5 sprints**.  
- Accelerated feedback cycle with **CI/CD automation**.  
- Detected **15+ critical defects early** using API validations.

---

## Business Impact
- Improved **release confidence** for stakeholders.  
- Faster go-to-market with **reliable automation pipelines**.  
- Enhanced **developer collaboration** via shift-left testing.  
- Reduced **production defects**, saving cost & time.  
- Created a **reusable automation framework** that can be extended to future projects.
  
---

## Running Tests in CI/CD

This project is integrated with **GitHub Actions** for automated test execution.

### CI/CD Workflow
- On every **push** or **pull request**, the workflow in `.github/workflows/playwright-ci.yml` is triggered.
- It runs all Playwright tests, generates reports, and provides feedback directly in the GitHub UI.

### Running Tests Locally
To execute tests on your local machine:

```bash
npx playwright test
```
---

## Reporting
- **Allure Reports** integrated for clear test results:  
- Test pass/fail trends.  
- Execution history.  
- Attachments/screenshots for failures.

---

## Configuration

You can set environment variables in a `.env` file (not committed to git) for things like base URLs or credentials.  
Example `.env`:
```
BASE_URL=https://test-env.example.com
USERNAME=testuser
PASSWORD=supersecret
```
> Use [dotenv](https://www.npmjs.com/package/dotenv) or similar to load these variables in your Playwright setup if needed.

---

## Writing New Tests

Add new JavaScript test files in the `tests/` directory.

Example:
```javascript
// tests/example.spec.js
const { test, expect } = require('@playwright/test');

test('homepage loads', async ({ page }) => {
  await page.goto(process.env.BASE_URL);
  await expect(page).toHaveTitle(/SlateSMS/);
});
```

---

## Contribution

This project is currently under development and actively maintained.  
We welcome contributions to improve and expand the test coverage!

To contribute:

1. Fork this repository and clone your fork  
2. Create a feature branch (`git checkout -b feature/my-feature`)  
3. Add your tests or changes  
4. Run tests locally with `npx playwright test`  
5. Open a Pull Request with a clear description

Please follow our code style and write clear, maintainable tests.

---

## Support

For questions or support, open an [issue](https://github.com/praveen2567/slatesms-e2e-testing/issues)  
or visit our website: [https://www.slatesms.com](https://www.slatesms.com)

## Links
- [Resume](./MT_Praveen_Kumar_QA_Automation.pdf) 
- [LinkedIn](https://www.linkedin.com/in/mtpraveenkumar/)
- [GitHub](https://github.com/praveen2567)
- **Email:** praveenmt.kumar@gmail.com
- **Mobile:** +91-9390660259  
