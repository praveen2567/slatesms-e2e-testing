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
- [Getting Started](#getting-started)
- [Contribution](#contribution)
- [License](#license)
- [Who It's For](#who-it's-for)

# SlateSMS - School Management System

# PROJECT OVERVIEW

SlateSMS is an AI-powered school management platform designed to help educational institutions streamline operations, enhance learning, and improve communication. It’s built for scalability, security, and customization—ideal for schools, districts, and networks.

As part of the QA Automation team, I contributed to building and maintaining the test infrastructure that ensured product reliability across modules such as:

Admissions & Enrollment: Online forms, document uploads, and automated tracking

Fee Management: Digital invoicing, payment gateway integration, and reminders

Smart Scheduling: AI-driven timetable optimization

Learning & Assessment: LMS tools, quizzes, and progress tracking

Communication: Parent portals, mobile apps, and AI chatbots

# KEY FEATURES
# Infrastructure & Security
1. Cloud-native platform: Access from any device, anywhere.

2. Enterprise-grade security: Protects sensitive data.

3. Role-based access control: Custom permissions for admins, teachers, parents, and students.

4. Audit logs & compliance: Supports FERPA and GDPR standards.

5. Multi-tenant & multi-language support: Ideal for districts and diverse communities.

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

1. Administrators: Dashboards, budgeting, compliance

2. Teachers: Lesson planning, grading, performance tracking

3. Parents & Students: Progress tracking, communication, scheduling

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

**Tip:**  
You can customize test execution with Playwright CLI options. For example, to run a specific test file:
```bash
npx playwright test tests/example.spec.ts
```
## Project Structure

- `tests/` – All Playwright end-to-end test cases (JavaScript)
- `playwright.config.js` – Playwright configuration file
- `utils/` – Utility/helper functions (if any)
- `reports/` – Test result reports (auto-generated)

---

## Running Tests in CI/CD

Tests can be automatically run in CI/CD pipelines (e.g., GitHub Actions).  
On every push or pull request, the workflow in `.github/workflows/` triggers the tests.

To run tests locally:
```bash
npx playwright test
```

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

We welcome contributions!  
To contribute:

1. Fork this repository and clone your fork
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Add your tests or changes
4. Run tests locally with `npx playwright test`
5. Open a Pull Request with a clear description

Please follow our code style and write clear, maintainable tests.

---

## License

This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.

---

## Support

For questions or support, open an [issue](https://github.com/praveen2567/slatesms-e2e-testing/issues).
