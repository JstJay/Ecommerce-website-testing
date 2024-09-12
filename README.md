# Big Basket Web Application Testing

## Overview

This repository outlines the testing plan for the Big Basket web application ([https://www.bigbasket.com](https://www.bigbasket.com)). The aim is to ensure the functionality and quality of the application through comprehensive testing strategies.

## Objectives

The primary goal is to validate the core functionalities of the Big Basket application and ensure it meets quality standards across various environments.

## Scope of Testing

### Included Features

- **User Management**:
  - Register
  - Login & Logout
  - Forgot Password
- **Product Interaction**:
  - Search
  - Product Compare
  - Product Display Page
  - Add to Cart
  - Wish List
- **Shopping and Checkout**:
  - Shopping Cart
  - Home Page
  - Checkout Page
- **Account Management**:
  - My Account Page
  - Order History Page
- **Customer Interaction**:
  - Contact Us Page
- **Navigation**:
  - Menu Options
  - Footer Options
  - Category Pages

### Excluded Features

- Features not listed in the inclusions
- Third-party features and payment gateways

## Test Environments

Testing will be conducted on the following platforms and browsers:
- **Windows 10**: Chrome, Firefox, Edge
- **Mac OS**: Safari
- **Linux Ubuntu**: Firefox

## Test Strategy

### Approach

1. **Test Case Development**
   - Develop test scenarios and cases using techniques like Equivalence Class Partition, Boundary Value Analysis, Decision Table Testing, State Transition Testing, and Use Case Testing.
   - Employ Error Guessing and Exploratory Testing.

2. **Testing Process**
   - **Smoke Testing**: Initial testing to check core functionalities.
   - **Sanity Testing**: Detailed testing on stable builds.
   - **Types of Testing**:
     - Smoke Testing
     - Sanity Testing
     - Regression Testing
     - Retesting
     - Usability Testing
     - UI Testing
     - Accessibility Testing

3. **Best Practices**
   - Conduct Exploratory Testing in addition to formal test cases.
   - Perform End-to-End Flow Testing to simulate real user scenarios.

## Problem Tracking

### Defect Reporting

- Record deviations, usability issues, or questions discovered during testing.
- Document defects with steps to reproduce and retest to ensure reproducibility.
- Provide daily updates on defects and observations.

### Documentation

- Defects are logged in a Word document.
- Test scenarios and cases are documented in an Excel spreadsheet.

## Methodology

1. **Requirements Analysis**: Review and analyze functional and non-functional requirements.
2. **Test Planning**: Define test objectives, scope, approach, and scenarios.
3. **Test Design**: Create test cases, scripts, and test data.
4. **Test Execution**: Execute test cases, record results, and report defects.
5. **Test Reporting**: Prepare test reports, defect logs, and perform metrics analysis.
6. **Test Closure**: Review test results, document findings, and capture lessons learned.

## Criteria

- **Entry Criteria**: Requirements, test environment setup, test data, and resources must be available.
- **Exit Criteria**: Completion of test execution, achievement of test objectives, resolution of critical defects, and stakeholder approval.

## Suspension and Resumption Criteria

- **Suspension**: Based on client decisions.
- **Resumption**: Resources will be adjusted based on client needs.

## Tools

- **Jira**: Bug tracking tool
- **Mind Map Tool**: For planning and organizing test cases
- **Spreadsheet Documents**: For documenting test scenarios and cases
- **Spring Tool Suite**: For executing automated scripts

## Risks and Mitigations

- **Non-Availability of a Resource**: Backup resource planning in place.
- **Build URL Issues**: Resources will be allocated to other tasks.
- **Less Time for Testing**: Adjust resource allocation dynamically based on client needs.

## Approvals

- Documents requiring client approval:
  - Test Plan
  - Test Scenarios
  - Test Cases
  - Reports

Testing will proceed to the next steps only after receiving the necessary approvals.

