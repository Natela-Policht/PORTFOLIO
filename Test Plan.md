## 1. Introduction<br>
The purpose of this Test Plan is to define the strategy, scope, schedule, and responsibilities for the testing of the AirSerbia.com search engine component. The document contains key information about testing activities. It lists all software components that will be verified and the types of tests that will be performed.<br<

## 2. Scope of tests<br>
**In scope:**<br>
- Unit tests
- Functional testing: verification of filters, field validation, and search results display
- Performance tests: average and peak response time validation
- Cross-browser testing (Chrome, Firefox, Opera)

  **Out of Scope:**<br>
  - Automated testing (due to time and environment constraints)
  - Accessibility testing
  - Security and penetration testing
 
## 3. Test items<br>
  - Search engine module on the AirSerbia.com homepage
  - Filtering logic for flight parameters (dates, destinations, passenger count)
  - Validation of mandatory fields and result set accuracy

  ## 4. Entry criteria<br>
  - Search engine implementation completed and deployed to the test environment
  - Test data available and configured
  - Test environment stable and accessible
  - User stories and acceptance criteria approved by the Product Owner
 
  ## 5. Exit criteria<br>
  - All planned test cases executed
  - 95% of critical and high-severity test cases passed
  - No open critical or high-severity defects
  - Test summary report delivered and accepted by stakeholders
 
  ## 6. Test approach<br>
  **Functional testing:**<br>
  - Based on user stories and acceptance criteria
  - Manual test cases will be designed and executed in TestLink
  - Each failed case will be logged as a defect in Jira with appropriate severity and priority

  **Performance testing:**<br>
  - Conducted using JMeter
  - KPIs: Average response time ≤ 700 ms

  **Retesting and regression:**<br>
  - All fixed defects will be retested in the next test cycle
  - Regression testing will cover core functionality and critical business flows
