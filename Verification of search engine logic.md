### Verification of search engine logic<br>

**Preconditions:**
- The tester has access to a stable internet connection
- The tester has a valid Windows 11 operating system
- The following web browsers are installed and updated to the latest version:
  - Google Chrome
  - Mozilla Firefox
  - Microsoft Edge
  - Opera
- Browser cache and cookies are cleared before testing
- The tester has access to the airserbia.com website
- The tester is not logged into any user account (unless specified otherwise in the test steps)(br)

<table aria-label="Tabela przykładowa">
  <thead>
    <tr>
      <th>Test case ID</th>
      <th>Step actions</th>
      <th>Expected results</th>
      <th>Execution status</th>
    </tr>
  </thead>
  <tbody>
    <!-- Wiersze 1–10: po 4 komórki -->
    <tr><td>1</td><td>Visit airserbia.com website.</td><td>The search engine loads successfully.</td><td>Passed</td></tr>
    <tr><td>2</td><td>In the “From” field, enter the location “Tirana.”</td><td>The location “Tirana” appears in the first position in the suggestion.</td><td>Passed</td></tr>
    <tr><td>3</td><td>In the "To" field, enter the location "Athens".</td><td>The location "Athens" appears in the first position in the suggestion.</td><td>Passed</td></tr>
    <tr><td>4</td><td>Click on the date field.</td><td>A date picker appears with the available time range.</td><td>Passed</td></tr>
    <tr><td>5</td><td>Select the available range from the date picker.</td><td>The range has been correctly entered into the date field.</td><td>Passed</td></tr>
    <tr><td>6</td><td>Click on the “Passengers” field.</td><td>A pop-up appears with the option to select the number of passengers in the age group: adults, children, infants.</td><td>Passed</td></tr>
    <tr><td>7</td><td>Increase the number of passengers in each age group to 2 passengers.</td><td>The number of passengers is correctly calculated in each age group and in the “Passengers” field.</td><td>Passed</td></tr>
    <tr><td>8</td><td>Enter the numbers “1234” in the “Promo code” field.</td><td>It is possible to enter numbers in the “Promo code” field.</td><td>Passed</td></tr>
    <tr><td colspan="2">Execution type:</td><td colspan="2">Manual</td></tr>
    <tr><td colspan="2">Priority</td><td colspan="2">Medium</td></tr>
    <tr><td colspan="2"><b>Execution details<b></td><td colspan="2"></td></tr>
    <tr><td colspan="2">Build</td><td colspan="2">0.0.9</td></tr>
    <tr><td colspan="2">Tester</td><td colspan="2">Natela</td></tr>
    <tr><td colspan="2">Execution result</td><td colspan="2">Passed</td></tr>
    <tr><td colspan="2">Execution duration</td><td colspan="2">30.00</td></tr>
  </tbody>
</table>

