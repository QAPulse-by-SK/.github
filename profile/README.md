<div align="center">

<img src="https://img.shields.io/badge/QA%20Pulse%20by%20SK-Test%20Automation%20Hub-3b82f6?style=for-the-badge&logoColor=white" height="35"/>

<br/><br/>

# QA Pulse by SK

### *Production-grade Test Automation Tools — Free & Open Source*

**Fork a boilerplate. Install a package. Ship quality faster.**

<br/>

[![Website](https://img.shields.io/badge/🌐_Website-skakarh.com-3b82f6?style=for-the-badge)](https://www.skakarh.com)
[![Products](https://img.shields.io/badge/📦_Products-skakarh.com/products-22c55e?style=for-the-badge)](https://www.skakarh.com/products/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-QAPulse-0077b5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/company/qapulsebysk)
[![npm](https://img.shields.io/badge/npm-QAPulseSK-cb0000?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/search?q=qapulsesk)
[![Email](https://img.shields.io/badge/Email-contact@skakarh.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@skakarh.com)

<br/>

> *"Quality is not an act, it is a habit."* — Aristotle

</div>

---

## 🎯 What We Build

Two categories of free, open-source QA tooling — everything you need to go from zero to a production-grade test suite.

| Category | What | Purpose |
|---|---|---|
| **Boilerplates** | Clone & fork | Production-ready frameworks — everything wired up |
| **npm Packages** | Install & import | Utility libraries that plug into any existing suite |

**→ See everything at [skakarh.com/products](https://www.skakarh.com/products/)**

---

## 🎭 Playwright Boilerplate

[![Playwright Tests](https://github.com/QAPulse-by-SK/playwright-boilerplate/actions/workflows/playwright.yml/badge.svg)](https://github.com/QAPulse-by-SK/playwright-boilerplate/actions/workflows/playwright.yml)
[![Stars](https://img.shields.io/github/stars/QAPulse-by-SK/playwright-boilerplate?style=social)](https://github.com/QAPulse-by-SK/playwright-boilerplate/stargazers)
[![Forks](https://img.shields.io/github/forks/QAPulse-by-SK/playwright-boilerplate?style=social)](https://github.com/QAPulse-by-SK/playwright-boilerplate/network/members)

| | |
|---|---|
| **Languages** | TypeScript (`master`) · JavaScript (`javascript`) · Packages (`with-packages`) |
| **Test Types** | E2E · API · Visual Regression · Accessibility · Component |
| **Reporters** | HTML · Allure · JUnit · JSON · qapulsesk-report |
| **CI/CD** | GitHub Actions (sharded + Pages) · Jenkins · Azure DevOps |
| **Highlights** | POM · Auth State · A11yHelper · Faker.js DataFactory · Slack notifications |

```bash
git clone https://github.com/QAPulse-by-SK/playwright-boilerplate.git               # TypeScript
git clone -b javascript https://github.com/QAPulse-by-SK/playwright-boilerplate.git  # JavaScript
git clone -b with-packages https://github.com/QAPulse-by-SK/playwright-boilerplate.git # + QAPulseSK packages
```

**[→ View Playwright Boilerplate](https://github.com/QAPulse-by-SK/playwright-boilerplate)**

---

## 🌲 Cypress Boilerplate

[![Cypress Tests](https://github.com/QAPulse-by-SK/cypress-boilerplate/actions/workflows/cypress.yml/badge.svg)](https://github.com/QAPulse-by-SK/cypress-boilerplate/actions/workflows/cypress.yml)
[![Stars](https://img.shields.io/github/stars/QAPulse-by-SK/cypress-boilerplate?style=social)](https://github.com/QAPulse-by-SK/cypress-boilerplate/stargazers)
[![Forks](https://img.shields.io/github/forks/QAPulse-by-SK/cypress-boilerplate?style=social)](https://github.com/QAPulse-by-SK/cypress-boilerplate/network/members)

| | |
|---|---|
| **Languages** | TypeScript (`master`) · JavaScript (`javascript`) · Packages (`with-packages`) |
| **Test Types** | E2E · API · Visual Regression · Accessibility · Component |
| **Reporters** | Mochawesome · Allure · JSON · qapulsesk-report |
| **CI/CD** | GitHub Actions (multi-browser + Pages) · Jenkins · Azure DevOps |
| **Highlights** | 12 Custom Commands · cy.session() Auth · cypress-grep Tags · Slack notifications |

```bash
git clone https://github.com/QAPulse-by-SK/cypress-boilerplate.git               # TypeScript
git clone -b javascript https://github.com/QAPulse-by-SK/cypress-boilerplate.git  # JavaScript
git clone -b with-packages https://github.com/QAPulse-by-SK/cypress-boilerplate.git # + QAPulseSK packages
```

**[→ View Cypress Boilerplate](https://github.com/QAPulse-by-SK/cypress-boilerplate)**

---

## 📦 npm Packages

Three framework-agnostic packages that plug into any existing test suite — Playwright, Cypress, Jest, Vitest or WebdriverIO.

---

### qapulsesk-assert

[![npm](https://img.shields.io/npm/v/qapulsesk-assert?color=3b82f6&logo=npm&label=qapulsesk-assert)](https://www.npmjs.com/package/qapulsesk-assert)
[![npm downloads](https://img.shields.io/npm/dm/qapulsesk-assert?color=22c55e)](https://www.npmjs.com/package/qapulsesk-assert)

One assertion library that works identically in Playwright, Cypress, Jest, Vitest and WebdriverIO. No more relearning assertions when switching frameworks.

| Feature | What it does |
|---|---|
| `assertFuzzyMatch` | Handles typos, capitalisation, minor copy changes |
| `assertSchema` | Validates full API response schema in one call |
| `assertResponseTime` | SLA-based performance assertions |
| `toBeAccessible` | Zero-config WCAG 2.1 accessibility check |
| `assertObjectContains` | Partial object matching, works in any framework |
| `toMean / satisfiesRule` | AI semantic assertions via Claude *(optional)* |

```bash
npm install qapulsesk-assert
```

**[→ npm](https://www.npmjs.com/package/qapulsesk-assert)** · **[→ GitHub](https://github.com/QAPulse-by-SK/QAPulseSK-assert)** · **[→ Demo tests](https://github.com/QAPulse-by-SK/playwright-boilerplate/tree/with-packages/tests/packages)**

---

### qapulsesk-report

[![npm](https://img.shields.io/npm/v/qapulsesk-report?color=a78bfa&logo=npm&label=qapulsesk-report)](https://www.npmjs.com/package/qapulsesk-report)
[![npm downloads](https://img.shields.io/npm/dm/qapulsesk-report?color=22c55e)](https://www.npmjs.com/package/qapulsesk-report)

One reporter package for all frameworks. Generates a dark-theme HTML dashboard after every test run — pass rate ring chart, trend history, Slack/Teams webhooks, and optional AI failure analysis.

| Feature | What it does |
|---|---|
| Dark-theme HTML report | Professional, shareable, zero config |
| Pass rate ring chart | Visual percentage at a glance |
| Trend chart | Pass rate history across multiple runs |
| Slack / Teams webhooks | Pass/fail alerts after every run |
| AI failure analysis | Plain-English explanation of failures *(optional)* |

```bash
npm install qapulsesk-report
```

**[→ npm](https://www.npmjs.com/package/qapulsesk-report)** · **[→ GitHub](https://github.com/QAPulse-by-SK/QAPulseSK-report)** · **[→ Live report](https://qapulse-report-sk.surge.sh)**

---

### qapulsesk-gen

[![npm](https://img.shields.io/npm/v/qapulsesk-gen?color=f59e0b&logo=npm&label=qapulsesk-gen)](https://www.npmjs.com/package/qapulsesk-gen)
[![npm downloads](https://img.shields.io/npm/dm/qapulsesk-gen?color=22c55e)](https://www.npmjs.com/package/qapulsesk-gen)

Record in Chrome DevTools → export as HAR → generate Playwright or Cypress tests in 2ms. No AI key needed.

| Input | Output | Time |
|---|---|---|
| HAR file | Playwright TS/JS or Cypress TS/JS | ~2ms |
| Playwright recording | Clean spec file | ~2ms |
| Plain English | AI-generated tests | ~3s *(API key required)* |

```bash
npm install -g qapulsesk-gen

npx qapulsesk-gen from-har login.har --framework playwright --language typescript
npx qapulsesk-gen from-har login.har --framework cypress   --language javascript
```

**[→ npm](https://www.npmjs.com/package/qapulsesk-gen)** · **[→ GitHub](https://github.com/QAPulse-by-SK/QAPulseSK-gen)** · **[→ Demo tests](https://github.com/QAPulse-by-SK/playwright-boilerplate/tree/with-packages/tests/packages)**

---

## 🗺️ Roadmap

| Product | Status | Description |
|---|---|---|
| 🎭 Playwright Boilerplate | ✅ **Live** | TypeScript + JavaScript + with-packages |
| 🌲 Cypress Boilerplate | ✅ **Live** | TypeScript + JavaScript + with-packages |
| ✅ qapulsesk-assert v1.0.5 | ✅ **Live** | Cross-framework assertions |
| 📊 qapulsesk-report v1.0.5 | ✅ **Live** | Dark-theme HTML reports |
| 🤖 qapulsesk-gen v1.0.3 | ✅ **Live** | HAR → tests in 2ms |
| 🤖 Selenium + Java | 🔜 Coming Soon | Maven + TestNG + Allure |
| 🚀 WebdriverIO | 🔜 Coming Soon | TypeScript + Mocha |
| 📦 More npm Packages | 🔜 Coming Soon | Expanding the QAPulseSK ecosystem |

---

## 💡 Why QA Pulse by SK?

```
✅ Production-grade    — patterns from real e-commerce, ERP, telecoms, travel projects
✅ Dual language       — TypeScript + JavaScript for every framework
✅ Cross-framework     — npm packages work in Playwright, Cypress, Jest, Vitest, WebdriverIO
✅ Complete            — not skeletons, fully wired with working tests
✅ Honest docs         — comparison tables showing where we add value vs standard tools
✅ CI/CD ready         — GitHub Actions, Jenkins, Azure DevOps out of the box
✅ Community first     — MIT licensed, PRs welcome, issues answered within 48h
```

---

## 📊 Stats

<div align="center">

![Boilerplates](https://img.shields.io/badge/Boilerplates-2_Live-22c55e?style=for-the-badge)
![Packages](https://img.shields.io/badge/npm_Packages-3_Live-3b82f6?style=for-the-badge)
![Tests](https://img.shields.io/badge/Tests_Passing-149-a78bfa?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge)

</div>

---

## 🤝 Contributing

| Branch | PR target |
|---|---|
| TypeScript fixes | `master` |
| JavaScript fixes | `javascript` |
| Package integration | `with-packages` |

Every repo has a `CONTRIBUTING.md`. PRs reviewed within 48 hours.

---

## 📬 Contact

| | |
|---|---|
| 🌐 **Website** | [www.skakarh.com](https://www.skakarh.com) |
| 📦 **Products** | [skakarh.com/products](https://www.skakarh.com/products/) |
| 📧 **Email** | [contact@skakarh.com](mailto:contact@skakarh.com) |
| 💼 **LinkedIn** | [company/qapulsebysk](https://linkedin.com/company/qapulsebysk) |
| 🐦 **Twitter/X** | [@qapulsesk](https://twitter.com/qapulsesk) |

---

<div align="center">

**If our tools saved you time, please ⭐ the repos — it helps others find them!**

<br/>

*Built with ❤️ by [QA Pulse by SK](https://www.skakarh.com)*

</div>
