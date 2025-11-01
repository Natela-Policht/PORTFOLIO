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
    <tr><td>1</td><td>1. Open a web browser and navigate to https://www.airserbia.com.<br>
2. Check if the flight search engine is visible on the page.<br>
3. Verify that the search engine fields are active and clickable.<br>
4. Check if there are any visible error messages for the search engine.<br></td><td>1. The homepage loads successfully without any errors.<br>
2. The flight search engine is displayed with fields: "From", "To", "Date range", "Passengers" and "Promo code".<br>
3. All fields respond to clicks and allow data input.<br>
4. No error messages or broken components are visible. The search engine loads completely.</td><td>Passed</td></tr>
    <tr><td>2</td><td>1. Open a web browser and navigate to https://www.airserbia.com.<br>
2. Make sure you are in the “Round trip” section.<br>
3. Leave the “From,” “To,” and “Date range” fields empty.<br>
4. Click on the “Show flights” button.</td><td>1. The homepage loads successfully with the flight search engine visible.<br>
2. The button “Round trip” is active and highlighted in blue.<br>
3. Fields remain empty.<br>
4. Validation messages appear next to fields that are mandatory.</td><td>Passed</td></tr>
    <tr><td>3</td><td>1. Open a web browser and navigate to https://www.airserbia.com.<br>
2. Make sure you are in the “Round trip” section.<br>
3. The "From", "To" and "Date range" fields are not filled in.<br>
4. Click on the "Show flights" button.<br>
5. Fill in the required fields "From", "To" and "Date range".</td><td>1. The homepage loads successfully with the flight search form visible.<br>
2. The button “Round trip” is active and highlighted in blue.<br>
3. Fields remain blank.<br>
4. Validation messages appear next to the mandatory fields “From,” “To,” and “Date range”.<br>
5. Validation messages should disappear after completing the required fields.</td><td>Passed</td></tr>
    <tr><td>4</td><td>1. Open a web browser and navigate to https://www.airserbia.com.<br>
2. Make sure you are in the “Round trip” section.<br>
3. Fill in the “From,” “To,” and “Date range” fields.<br>
4. Click the “Find flights” button.</td><td>1. The home page loads successfully with the flight search form visible.<br>
2. The button is active and highlighted in blue.<br>
3. The fields “From,” “To,” and “Date range” are filled in correctly.<br>
4. Flight details are loading correctly. </td><td>Passed</td></tr>
    <tr><td>5</td><td>1. Open a web browser and navigate to https://www.airserbia.com.<br>
2. Make sure you are in the “Round trip” section.<br>
3. Click on the “Date range” calendar field to open the calendar date picker.<br>
4. Observe all dates earlier than today's date in the date picker.</td><td>1. The homepage loads successfully with the flight search form visible.<br>
2. The button is active and highlighted in blue.<br>
3. The calendar widget opens displaying available dates.<br>
4. All dates in the date picker earlier than today are blocked.</td><td>Passed</td></tr>
    <tr><td colspan="2">Execution type:</td><td colspan="2">Manual</td></tr>
    <tr><td colspan="2">Priority</td><td colspan="2">Medium</td></tr>
    <tr><td colspan="2"><b>Execution details<b></td><td colspan="2"></td></tr>
    <tr><td colspan="2">Build</td><td colspan="2">0.0.9</td></tr>
    <tr><td colspan="2">Tester</td><td colspan="2">Natela</td></tr>
    <tr><td colspan="2">Execution result</td><td colspan="2">Failed</td></tr>
    <tr><td colspan="2">Execution duration</td><td colspan="2">30.00</td></tr>
  </tbody>
</table>

