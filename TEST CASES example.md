### Validation verification<br>

**Preconditions:**
- The tester has access to a stable internet connection
- The tester has a valid Windows 11 operating system
- The following web browsers are installed and updated to the latest version:
    - Google Chrome
    - Mozilla Firefox
    - Microsoft Edge
    - Opera
- The airserbia.com website is accessible and fully loaded
- Browser cache and cookies are cleared before testing
- The tester is on the Flight Search page (homepage or flight booking section)
- No flight search form fields are pre-filled
- The tester is not logged into any user account (unless required for the scenario)<br>


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
    <tr><td>2</td><td>The “From,” “To,” and “Date range” fields are not filled in, click on the “Show flights” button.</td><td>Validation messages appear next to fields that are mandatory.</td><td>Passed</td></tr>
    <tr><td>3</td><td>The "From", "To" and "Date range" fields are not filled in, click on the "Show flights" button. Fill in the required fields "From", "To" and "Date range".</td><td>Validation messages should disappear after completing the required fields.</td><td>Failed</td></tr>
    <tr><td>4</td><td>The “From,” “To,” and “Date range” fields are filled in. Click the “Find flights” button.</td><td>- A page with available search results appears.<br>- After selecting the class and clicking on the “Select” button, the flight details page loads. </td><td>Passed</td></tr>
    <tr><td>5</td><td>Click on the “Departing date” calendar.</td><td>All dates in the date picker earlier than today are blocked.</td><td>Passed</td></tr>
    <tr><td>6</td><td>Click on the “Returning date” calendar.</td><td>All dates in the date picker earlier than today are blocked.</td><td>Passed</td></tr>
    <tr><td>7</td><td>Click on the calendar in the “Round trip” section and select the date range.</td><td>Dates on which flights are unavailable are blocked in the date picker.</td><td>Failed</td></tr>
    <tr><td>8</td><td>In the search engine component, click on the “One-way” or “Multi-city” buttons.</td><td>The “One-way” and “Multi-city” buttons are visible and clickable.</td><td>Passed</td></tr>
    <tr><td colspan="2">Execution type:</td><td colspan="2">Manual</td></tr>
    <tr><td colspan="2">Priority</td><td colspan="2">Medium</td></tr>
    <tr><td colspan="2"><b>Execution details<b></td><td colspan="2"></td></tr>
    <tr><td colspan="2">Build</td><td colspan="2">0.0.9</td></tr>
    <tr><td colspan="2">Tester</td><td colspan="2">Natela</td></tr>
    <tr><td colspan="2">Execution result</td><td colspan="2">Failed</td></tr>
    <tr><td colspan="2">Execution duration</td><td colspan="2">30.00</td></tr>
  </tbody>
</table>

