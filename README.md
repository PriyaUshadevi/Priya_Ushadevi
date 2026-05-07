<p align="center">
  <img src="ChatGPT Image May 7, 2026, 09_14_21 PM.png" alt="Priya Ushadevi – Senior Test Lead Banner" width="100%">
</p>

<p align="center">
  <!-- Tech Stack Badges -->
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white">
  <img src="https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=whit">
  <img src="https://img.shields.io/badge/Workday-005EB8?style=for-the-badge&logo=workday&logoColor=white">
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/TestNG-FF6F00?style=for-the-badge">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
</p>


# Hi, I'm Priya 👋  

**Senior Test Lead | Quality Engineering | Workday HCM | Test Automation | AI in QA**  

Based in the United Kingdom, I help organisations reduce delivery risk, improve release confidence, and build scalable QA practices through structured test strategy, automation, Workday HCM expertise, and practical adoption of AI‑assisted testing approaches.  

## 🌟 About Me

I am a **Senior Test Lead** with deep experience across:
    -End‑to‑end testing for enterprise systems
    -Workday HCM delivery
    -Test management & governance
    -UI + API automation
    -AI‑assisted quality engineering

My current areas of interest include AI-assisted quality engineering, RAG-based testing knowledge systems, LLM-based validation, and practical ways to combine modern AI tooling with established QA governance.

## 🚀 What I Do

    -Test strategy aligned to business risk & release criteria
    -Workday HCM test planning across payroll, compensation, integrations, security & reporting
    -UI & API automation frameworks (Java, Selenium, Playwright, REST APIs)
    -Test governance using Jira, Xray, Confluence
    -AI‑assisted QA (RAG, LLM validation, automated evidence review)

### 📌 Pinned Technical Projects (My Core Portfolio)

These are the 4 repositories that best represent my technical depth and leadership in QA engineering.

### 1️⃣ Java Testing Automation Framework
**Tech**: Java, TestNG, Selenium, Maven, Allure Reports, GitHub Actions
**Repo**: java-testing-automation-framework

### 🔍 Why this project matters
Most automation frameworks fail because they are not scalable, maintainable, or CI‑ready.
This framework demonstrates how I design enterprise‑grade automation that supports long‑term regression stability.

### 🧩 Architecture Diagram

┌──────────────────────────────┐
│        Test Runner           │
└───────────────┬──────────────┘
                │
┌───────────────▼──────────────┐
│     TestNG Test Suites       │
└───────────────┬──────────────┘
                │
┌───────────────▼──────────────┐
│   Page Objects / API Clients │
└───────────────┬──────────────┘
                │
┌───────────────▼──────────────┐
│     Core Utilities Layer     │
└──────────────────────────────┘
### 🎥 Demo GIF (placeholder)
/assets/java-framework-demo.gif

### 📊 Sample Report
/assets/allure-report-screenshot.png

### ⚙️ CI/CD Example (GitHub Actions)

name: Regression Suite
on: [push, pull_request]
jobs:
  run-tests:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Set up JDK
        uses: actions/setup-java@v3
        with:
          java-version: '17'
      - name: Run Tests
        run: mvn clean test

### 2️⃣ Test Management – Jira Integration Tool
**Tech**: Python/Java, Jira REST API, OAuth/Token Auth
**Repo**: test-management-jira-integration

### 🔍 Why this project matters
Large QA teams struggle with duplicated test cases, inconsistent updates, and manual effort.
This tool automates Jira test operations, improving traceability and reducing human error.

### 🧩 Architecture Diagram

User → CLI / UI → Integration Layer → Jira REST API → Xray / Test Issues

### 📸 Screenshots
Test case sync

Automated status update

Bulk creation flow

### 🎥 Demo GIF
/assets/jira-sync-demo.gif

### 3️⃣ Test Case Deduplication Tool
**Tech**: Python, NLP, Similarity Matching, CSV/JSON Processing
**Repo**: test-case-deduplication-tool

### 🔍 Why this project matters
Enterprises often have thousands of duplicated test cases across teams.
This tool identifies duplicates using similarity scoring, reducing maintenance cost and improving coverage clarity.

### 📊 Example Input/Output
Input:  1200 test cases  
Output: 312 duplicates flagged  

### 🧩 Architecture Diagram
Test Case Data → Preprocessing → Similarity Engine → Duplicate Report

### 📸 Screenshot
/assets/dedup-report.png

### 4️⃣ Selenium + Playwright Demo Suite
**Tech**: Selenium, Playwright, JavaScript/TypeScript, GitHub Actions
**Repo**: selenium-playwright-demo-suite

### 🔍 Why this project matters
Modern QA teams need hybrid automation skills.
This repo demonstrates my ability to work across both Selenium and Playwright, with CI‑ready examples.

### 🧩 Architecture Diagram
Selenium Suite → UI Regression  
Playwright Suite → Fast Parallel Tests  
Shared Utils → Reporting + Config

### 🎥 Demo GIF
/assets/playwright-vs-selenium.gif

### ⚙️ CI/CD Example
name: Cross-Framework Tests
on: push
jobs:
  playwright:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - run: npm install
      - run: npx playwright test
  selenium:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - run: mvn test

### 🧠 AI‑Assisted QA Concepts
I actively explore how AI can support quality engineering through:
    -LLM‑based validation
    -RAG‑based testing knowledge retrieval
    -Automated evidence review
    -AI‑generated test analysis

### 📚 Workday HCM Testing Expertise
I specialise in testing across:
    -Advance Comp
    -Payroll
    -Compensation
    -Integrations
    -Business processes
    -Security
    -Reporting

## Problem Statement

Many delivery teams struggle with fragmented testing knowledge, inconsistent test coverage, manual regression effort, and limited visibility into quality risks. This can slow releases, increase defect leakage, and make it difficult for stakeholders to understand whether a product is truly ready for production.

For Workday and enterprise transformation programmes, the challenge is even greater because testing must cover configuration, business processes, integrations, payroll, compensation, reporting, security, and downstream dependencies.

## Solution Approach

This portfolio presents my quality engineering focus and the types of solutions I build or lead:

- Test strategies that align business risk, delivery timelines, and release criteria.
- End-to-end test planning for Workday HCM modules and enterprise workflows.
- UI and API automation frameworks for faster regression feedback.
- Test management processes using tools such as Jira, Xray, and Confluence.
- AI-assisted testing concepts, including test validation, knowledge retrieval, and smarter coverage analysis.
- Clear QA reporting for delivery teams, business stakeholders, recruiters, and clients.

## Core Expertise

- Test strategy, planning, estimation, execution, and closure.
- Functional, regression, integration, system, UAT, and defect lifecycle management.
- Workday HCM testing, including compensation, payroll, integrations, and business process validation.
- Automation using Selenium, Playwright, API testing tools, and CI-ready test design.
- Test governance with Jira, Xray, Confluence, traceability, dashboards, and quality metrics.
- AI and QA exploration, including RAG concepts, LLM validation, and AI-assisted test optimisation.

## Featured Project Areas

### Test Automation Framework

Technology focus: Java, Playwright, Selenium, API testing, CI integration.

Purpose:

- Create maintainable automated regression coverage.
- Reduce repeated manual testing effort.
- Improve confidence before release sign-off.
- Support scalable UI and API validation.

### AI Validation Concept for QA

Technology focus: LLM evaluation, validation workflows, quality gates, test evidence review.

Purpose:

- Explore how AI can support test analysis and validation.
- Identify risks in AI-generated outputs.
- Improve QA productivity without removing human accountability.
- Build repeatable evaluation patterns for testing teams.

### Workday Test Strategy Samples

Domain focus: Workday HCM, payroll, compensation, integrations, business processes, security, reporting.

Purpose:

- Demonstrate structured Workday test planning.
- Show coverage across business-critical workflows.
- Support stakeholder review and test sign-off.
- Align testing with enterprise implementation milestones.

## Repository Contents

Current files:

- `README.md` - Professional profile, project positioning, setup guidance, verification notes, and showcase documentation.

No application source code, test automation framework, executable scripts, package manifest, CI configuration, or sample reports are currently included in this repository.

## Prerequisites

This repository is currently a portfolio and documentation repository. No runtime prerequisites are required to view the content.

For future runnable project examples, typical prerequisites may include:

- Git.
- Java JDK for Java-based automation projects.
- Node.js for Playwright or JavaScript/TypeScript tooling.
- Maven or Gradle for Java dependency management.
- A supported IDE such as IntelliJ IDEA, VS Code, or Eclipse.
- Access to the relevant test environment, test data, and tool credentials.

## Installation

No installation is required for the current repository because it contains showcase documentation only.

To clone and view the repository locally:

```bash
git clone <repository-url>
cd PriyaUshadevi
```

Open `README.md` in GitHub, VS Code, or any Markdown viewer.

## Configuration

No configuration is required for the current repository.

For future automation projects, configuration would normally include:

- Environment URLs.
- Browser settings.
- API base URLs.
- Test user credentials stored securely through environment variables or secret managers.
- Test data files.
- CI pipeline variables.
- Reporting output locations.

Sensitive values should never be committed to the repository.

## How to Run

There is no runnable application or automated test suite in this repository at the moment.

If runnable automation examples are added later, this section should be updated with exact commands such as:

```bash
npm install
npm test
```

or:

```bash
mvn test
```

## Testing and Verification

Current repository verification completed:

- Repository structure reviewed.
- README encoding issues fixed.
- Recruiter/client-facing documentation expanded.
- Prerequisites, installation, configuration, run instructions, problem statement, and solution approach added.
- No source code, package manifest, test framework, or runnable application currently exists to execute.

Because this repository currently contains documentation only, there are no automated tests to run.

## Code Review Result

Review outcome for the current repository:

- No broken source code was found because no source code is present.
- No failing tests were found because no test suite is present.
- No installation or runtime defects were found because there is no runnable application in this repository.
- README content has been corrected, expanded, and structured for recruiter and client review.
- Project status has been documented honestly to avoid presenting a documentation repository as a completed software product.

## Acceptance Criteria

For the current documentation-only repository, the following criteria are met:

- README is readable and professional.
- Problem statement and solution approach are documented.
- Prerequisites, installation, configuration, and run guidance are documented.
- Testing and verification status is documented.
- Current limitations are clearly stated.
- Recruiters and clients can understand the profile, expertise, and intended project direction.

For a runnable software project, the following criteria are not yet met because implementation artifacts are missing:

- Source code is available.
- Dependencies are declared.
- Application or test framework can be installed.
- Application or tests can be executed locally.
- Automated tests pass.
- Build or CI pipeline is configured.

## Current Project Status

Status: Documentation-ready portfolio repository.

This repository is in a clean working condition for its current purpose: presenting a professional profile and project focus areas to recruiters and clients.

It should not yet be described as a completed runnable software project because no implementation files, automated tests, or executable project artifacts are present.

## Closure Decision

Can this repository be marked as closed and passed?

Yes, for the current scope of a professional profile and documentation showcase.

No, if the expected scope is a complete runnable software project. To mark it as a completed software project, implementation files, installation commands, executable tests, and passing verification evidence must be added.

## Recommended Next Steps

To make this repository stronger as a technical showcase, add one or more complete sample projects:

- A Playwright or Selenium automation framework with example tests.
- API automation examples with reports.
- Workday test strategy sample documents with anonymised content.
- AI-assisted QA proof of concept with architecture, prompts, evaluation flow, and test results.
- Screenshots, diagrams, sample reports, or demo videos.

## Connect

LinkedIn: <https://www.linkedin.com/in/priyaushadevi/>

Location: United Kingdom

Focus: Quality Engineering, Workday HCM, Automation, and AI transformation in testing.
