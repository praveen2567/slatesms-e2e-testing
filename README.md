<!-- LOGO & BADGES -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/6bb375d8-7085-4199-b107-533531912555" width="300" alt="SlateSMS Dashboard"/>
</p>

<p align="center">
  <a href="https://github.com/praveen2567/slatesms-e2e-testing/actions">
    <img src="https://img.shields.io/github/workflow/status/praveen2567/slatesms-e2e-testing/Playwright%20CI?logo=github&style=flat-square" alt="CI Status"/>
  </a>
  <a href="https://www.npmjs.com/package/playwright">
    <img src="https://img.shields.io/badge/Playwright-Test-blue?logo=playwright&style=flat-square" alt="Playwright"/>
  </a>
  <a href="https://nodejs.org/">
    <img src="https://img.shields.io/badge/Node.js-18+-green?logo=node.js&style=flat-square" alt="Node.js"/>
  </a>
  <a href="https://github.com/praveen2567/slatesms-e2e-testing/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/praveen2567/slatesms-e2e-testing?style=flat-square" alt="License"/>
  </a>
</p>

<h1 align="center">✨ SlateSMS E2E Testing Framework ✨</h1>

<p align="center">
  <b>AI-powered school management, now with robust automated testing!</b>
</p>

---

## 📚 Table of Contents

- [📝 Project Overview](#-project-overview)
- [🚀 Key Features](#-key-features)
- [💰 Pricing Tiers](#-pricing-tiers)
- [👥 Who It's For](#-who-its-for)
- [⚡ Getting Started](#-getting-started)
- [📁 Project Structure](#-project-structure)
- [🧑‍💻 Roles & Responsibilities](#-roles--responsibilities)
- [🛠️ Tech Stack](#tech-stack)
- [🏆 Key Achievements](#-key-achievements)
- [💼 Business Impact](#-business-impact)
- [🔄 Running Tests in CI/CD](#-running-tests-in-cicd)
- [📈 Reporting](#-reporting)
- [⚙️ Configuration](#configuration)
- [🧪 Writing New Tests](#-writing-new-tests)
- [🤝 Contribution](#-contribution)
- [🆘 Support](#-support)
- [🔗 Links](#-links)




---

## 📝 Project Overview

> **SlateSMS** is an <b>AI-powered school management platform</b> that streamlines operations, enhances learning, and improves communication for educational institutions. This repo houses the end-to-end (E2E) Playwright automation suite ensuring the highest product reliability.

As part of the QA Automation team, I contributed to building and maintaining the test infrastructure for modules like:

- **Admissions & Enrollment**: Online forms, document uploads, tracking
- **Fee Management**: Digital invoicing, payment integration, reminders
- **Smart Scheduling**: AI-driven timetable optimization
- **Learning & Assessment**: LMS tools, quizzes, progress tracking
- **Communication**: Parent portals, mobile apps, AI chatbots

---

## 🚀 Key Features

<details>
<summary><b>🔒 Infrastructure & Security</b></summary>

- ☁️ **Cloud-native platform:** Access from anywhere, any device  
- 🛡️ **Enterprise-grade security:** Protects sensitive data  
- 🔑 **Role-based access control:** Custom permissions for each user type  
- 📜 **Audit logs & compliance:** Supports FERPA, GDPR  
- 🌎 **Multi-tenant & multi-language:** For districts & diverse communities  
</details>

<details>
<summary><b>🏫 School Management</b></summary>

- 👨‍🏫 Staff & student directories  
- 📝 Online admissions & enrollment  
- 💳 Fee management (payment gateway)  
- 🗓️ AI-powered scheduling  
- 📆 Event & calendar coordination  
</details>

<details>
<summary><b>🎓 Learning & Assessment</b></summary>

- 📚 Built-in LMS for materials & quizzes  
- 📊 Assessment tools with analytics  
</details>

<details>
<summary><b>📊 Analytics & Reporting</b></summary>

- 📈 Student performance dashboards  
- 🤖 Predictive analytics  
- 🧩 Custom report builder  
</details>

<details>
<summary><b>💬 Communication</b></summary>

- 📱 Parent portal & mobile app  
- 🤖 AI chatbots  
</details>

<details>
<summary><b>⭐ Premium Add-ons</b></summary>

- 🏆 Gamification modules  
- 🎓 AI-powered career counseling  
- 🔌 3rd-party integrations (Zoom, Google Classroom, MS Teams)  
</details>

---

## 💰 Pricing Tiers

| 🏷️ Plan        | Ideal For         | Key Highlights                        |
|:--------------:|:----------------:|:--------------------------------------:|
| 🟢 **Basic**       | Small schools     | Free forever, up to 100 students       |
| 🟡 **Pro**         | Growing schools   | $5/user/month, advanced analytics      |
| 🔵 **Enterprise**  | Large institutions| Custom pricing, full customization     |

---

## 👥 Who It's For

SlateSMS offers tailored solutions for:

- **Administrators:** Dashboards, budgeting, compliance
- **Teachers:** Lesson planning, grading, performance tracking
- **Parents & Students:** Progress tracking, scheduling, communication

---

## ⚡ Getting Started

> **🛠️ Quickstart**

```bash
# 1️⃣ Clone the repository
git clone https://github.com/praveen2567/slatesms-e2e-testing.git
cd slatesms-e2e-testing

# 2️⃣ Install dependencies
npm install

# 3️⃣ Install Playwright browsers (optional)
npx playwright install

# 4️⃣ Run the tests
npx playwright test

# 5️⃣ View the HTML report
npx playwright show-report
```

---

## 📁 Project Structure

```tree
slatesms-e2e-testing/
├── tests/           # Feature-based test specs
│   ├── login.spec.js
│   ├── dashboard/
│   └── admissions/
├── pages/           # Page Object Model (POM) classes
├── data/            # Test data (JSON, CSV)
├── fixtures/        # Reusable fixtures/mocks
├── utils/           # Helpers, custom commands
├── config/          # Environment configs
├── reports/         # Test reports, traces
├── .github/workflows/
│   └── playwright-ci.yml
├── playwright.config.js
├── package.json
├── README.md
└── .env             # Secrets (not committed)
```

---

## 🧑‍💻 Roles & Responsibilities

- 🚦 Designed BDD-driven Playwright framework from scratch
- 🏗️ Developed scalable **POM** structure
- 🧪 Automated **100+ regression & smoke tests** (UI + API)
- 🔗 Integrated with **GitHub Actions** for CI/CD
- 📊 Configured **Allure Reports** for traceability
- ⚡ Enabled parallel test execution
- 🤝 Collaborated for shift-left testing
- 🛠️ Maintained test data & configs
- 🔁 Troubleshot & stabilized flaky tests
- 🚀 Participated in Agile ceremonies & process improvement

---
<a name="tech-stack"></a>
## 🛠️ Tech Stack

| Category          | Tools & Tech                                  |
|-------------------|-----------------------------------------------|
| Language          | ![JS](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat-square) |
| Automation        | ![Playwright](https://img.shields.io/badge/-Playwright-green?logo=playwright&style=flat-square) |
| Test Runner       | Playwright Test, Mocha                        |
| Framework         | POM, BDD                                      |
| Reporting         | Allure, HTML, Mochawesome                     |
| CI/CD             | GitHub Actions                                |
| API Testing       | Postman, Playwright APIRequestContext         |
| Data              | JSON, CSV, dynamic generators                 |
| Browsers          | Chromium, Firefox, WebKit                     |
| Management        | Jira, Zephyr, Agile tools                     |

---

## 🏆 Key Achievements

- 🧪 Automated **100+ test scenarios**
- ⏱️ Reduced manual regression time by **70–80%**
- 📈 Achieved **85% pass rate** in regression pipelines
- 🚀 Delivered **95% defect-free releases** over 5 sprints
- 🔎 Detected **15+ critical defects** early via API validations

---

## 💼 Business Impact

- ✅ Improved release confidence for stakeholders
- 🚀 Faster go-to-market with reliable automation
- 🤝 Enhanced dev-QA collaboration (shift-left)
- 💰 Reduced production defects (cost & time savings)
- ♻️ Created a reusable, extensible automation framework

---

## 🔄 Running Tests in CI/CD

- CI pipeline triggered on every **push** or **pull request**
- Runs all Playwright tests, generates reports, and posts results in GitHub UI

> See `.github/workflows/playwright-ci.yml` for workflow details.

---

## 📈 Reporting

- **Allure Reports** for clear test results  
- Trends, execution history, pass/fail stats  
- Screenshots and traces attached for failures

---
<a name="configuration"></a>
## ⚙️ Configuration

> **Tip:** Store secrets & env variables in `.env` (not committed)!

**Example `.env`:**
```env
BASE_URL=https://test-env.example.com
USERNAME=testuser
PASSWORD=supersecret
```

**Load variables in code:**
```js
require('dotenv').config();
const baseURL = process.env.BASE_URL;
```

> Make sure `.env` is in your `.gitignore`!

---

## 🧪 Writing New Tests

Add JavaScript test files under `tests/` using Playwright syntax:

```js
// tests/example.spec.js
const { test, expect } = require('@playwright/test');

test('homepage loads', async ({ page }) => {
  await page.goto(process.env.BASE_URL);
  await expect(page).toHaveTitle(/SlateSMS/);
});
```

---

## 🤝 Contribution

> **Note:** Source code is private, but you can contribute to documentation and strategy!

**How to contribute (if/when open):**
1. Fork and clone this repo  
2. Create a feature branch  
3. Add your changes / tests  
4. Run `npx playwright test`  
5. Open a PR with a clear description

**Guidelines:**
- Follow code style and write maintainable tests
- Pass linting & formatting checks
- Ensure coverage for new features/bugs
- Suggest improvements via Issues/Discussions

---

## 🆘 Support

Questions or need help?
- Open an [issue](https://github.com/praveen2567/slatesms-e2e-testing/issues)
- Visit: [slateedutech.com](https://www.slateedutech.com)

---

## 🔗 Links

- 📄 [Resume](./MT_Praveen_Kumar_QA_Automation.pdf)
- 💼 [LinkedIn](https://www.linkedin.com/in/mtpraveenkumar/)
- 🐙 [GitHub](https://github.com/praveen2567/slatesms-e2e-testing)
- 📧 **Email:** [praveenmt.kumar@gmail.com](mailto:praveenmt.kumar@gmail.com)
- 📱 **Mobile:** [+91-9390660259](tel:+919390660259)

---

<p align="center">
  <b>Made with ❤️ by Praveen Kumar & SlateSMS QA Team</b>
</p>
