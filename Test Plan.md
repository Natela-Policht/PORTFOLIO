## 1. Introduction<br>
The purpose of this Test Plan is to define the strategy, scope, schedule, and responsibilities for the testing of the AirSerbia.com search engine component. The document contains key information about testing activities. It lists all software components that will be verified and the types of tests that will be performed.<br>

## 2. Scope of tests<br>
**In scope:**<br>
- Unit tests
- Functional testing: verification of filters, field validation, and search results display
- Performance tests: average and peak response time validation
- Cross-browser testing (Chrome, Firefox, Opera)

**Out of scope:**<br>
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

 ## 7. Test deliverables<br>
 - Test cases in TestLink
 - Test execution results
 - Defect reports in Jira
 - Performance test results (JMeter reports)
 - Final Test Summary Report

## 8. Test environment<br>
<table border="1">
  <tr>
    <th>Component</th>
    <th>	Specification</th>
  </tr>
  <tr>
    <td>OS</td>
    <td>Windows 11 Pro 64-bit</td>
  </tr>
  <tr>
    <td>Browsers</td>
    <td>Chrome (latest), Firefox (latest), Opera (latest)</td>
  </tr>
  <tr>
    <td>Test Tools</td>
    <td>JMeter, TestLink, Jira, BrowserStack</td>
  </tr>
  <tr>
    <td>Test Data</td>
    <td>Configured manually based on valid and invalid inputs</td>
  </tr>
</table>

## 9. Test data<br>
- Test data sets will be created manually according to business rules
- Data examples include valid/invalid dates, city codes, and passenger combinations
- Sensitive production data will not be used in any test environment

## 10. Schedule<br>
<table border="1">
  <tr>
    <th>Activity</th>
    <th>Responsible</th>
    <th>Duration</th>
    <th>Dates</th>
  </tr>
  <tr>
    <td>Test case design</td>
    <td>N. Policht</td>
    <td>1 day</td>
    <td>07.10.2025</td>
  </tr>
  <tr>
    <td>Functional testing</td>
    <td>N. Policht</td>
    <td>2 days</td>
    <td>08–09.10.2025</td>
  </tr>
  <tr>
    <td>Performance testing</td>
    <td>N. Policht</td>
    <td>1 day</td>
    <td>10.10.2025</td>
  </tr>
  <tr>
    <td>Retesting & regression</td>
    <td>N. Policht</td>
    <td>1 day</td>
    <td>11.10.2025</td>
  </tr>
  <tr>
    <td>Reporting</td>
    <td>N. Policht</td>
    <td>0.5 day</td>
    <td>12.10.2025</td>
  </tr>
  <tr>
    <td>
  </table>

  ## 11. Defect management<br>
  - All defects are logged in Jira with the following details:
      - Summary, environment, steps to reproduce, actual vs. expected result, severity, and priority
  - Defects are triaged daily during the testing period
  - Lifecycle: Open → In Progress → Fixed → Retest → Closed / Reopened
  - Defects are linked to relevant test cases and user stories


 ## 12. Reporting<br>
 - Daily reports: Short progress update in Jira/Slack channel
 - Final Test Summary Report: Delivered after completion of all testing activities, including:
      - Execution statistics (pass/fail/blocked)
      - Defect summary by severity
      - Performance metrics
      - Release readiness assessment

## 13. Roles and responsibilities<br>
<table border="1">
  <tr>
    <th>Role</th>
    <th>Name</th>
    <th>Responsibilities</th>
  </tr>
  <tr>
    <td>QA Engineer</td>
    <td>Nateła Policht</td>
    <td>Test design, execution, defect reporting, retesting, reporting</td>
  </tr>
  <tr>
    <td>Developer</td>
    <td>TBD</td>
    <td>Fixing defects, supporting testing</td>
  </tr>
  <tr>
    <td>Product Owner</td>
    <td>TBD</td>
    <td>Requirement clarification, acceptance of final results</td>
  </tr>
</table>

## 14. Approval<br>
<table border="1">
  <tr>
    <th>Name</th>
    <th>Role</th>
    <th>Signature</th>
    <th>Date</th>
  </tr>
  <tr>
    <td>QA Engineer</td>
    <td>Nateła Policht</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Product Owner</td>
    <td>TBD</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Project Manager</td>
    <td>TBD</td>
    <td></td>
    <td></td>
  </tr>
</table>

 
 





 
