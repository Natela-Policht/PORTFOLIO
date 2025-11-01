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
- The tester is not logged into any user account (unless specified otherwise in the test steps)

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
2. Check if there are any visible error messages for the search engine.</td><td>1. The homepage loads successfully without any errors.<br>
2. No error messages or broken components are visible. The search engine loads completely.</td><td>Passed</td></tr>
    <tr><td>2</td><td>1. Open a web browser and navigateIn to https://www.airserbia.com.<br>
2. Make sure you are in the “Round trip” section.<br>
3. In the “From” field, enter the location “Tirana.”<br>
4. Select “Tirana” from the drop-down list.</td><td>1. The homepage loads successfully without any errors.<br>
2. The button “Round trip” is active and highlighted in blue.<br>
3. The field allows data input and the location “Tirana” appears in the first position in the suggestion.<br>
4. It is possible to select “Tirana” from the drop-down list.</td><td>Passed</td></tr>
    <tr><td>3</td><td>1. Open a web browser and navigate to https://www.airserbia.com.<br>
2. Make sure you are in the “Round trip” section.<br>
3. In the "To" field, enter the location "Athens".<br>
4. Select “Athens” from the drop-down list.</td><td>1. The homepage loads successfully without any errors.<br>
2. The button “Round trip” is active and highlighted in blue.<br>
3. The field allows data input and the location “Athens” appears in the first position in the suggestion.<br>
4. It is possible to select “Athens” from the drop-down list.</td><td>Passed</td></tr>
    <tr><td>4</td><td>1. Open a web browser and navigate to https://www.airserbia.com.<br>
2. Make sure you are in the “Round trip” section.<br>
3. Click on the "Date range".<br>
4. Select the date range.</td><td>1. The homepage loads successfully without any errors.<br>
2. The button “Round trip” is active and highlighted in blue.<br>
3. A date picker appears with the available time range.<br>
4. The selected dates are visible in the “Date range” field.</td><td>Passed</td></tr>
    <tr><td>5</td><td>1. Open a web browser and navigate to https://www.airserbia.com.<br>
2. Make sure you are in the “Round trip” section.<br>
3. Click on the “Passengers” field.<br>
4. Select passengers: 1 adult, 1 child, and 1 infant.</td><td>1. The homepage loads successfully without any errors.<br>
2. The button “Round trip” is active and highlighted in blue.<br>
3. The passenger selection dialog box opens correctly.<br>
4. It is possible to choose the passengers: 1 adult, 1 child, and 1 infant.</td><td>Passed</td></tr>
    <tr><td>6</td><td>1. Open a web browser and navigate to https://www.airserbia.com.<br>
2. Make sure you are in the “Round trip” section.<br>
3. Click the "Promo code" field.<br>
4. Enter the numbers “1234” in the “Promo code” field.</td><td>1. The homepage loads successfully without any errors.<br>
2. The button “Round trip” is active and highlighted in blue.<br>
3. The field responds to clicks.<br>
4. The field allows data input.</td><td>Passed</td></tr>
    <tr><td>7</td><td>1. Open a web browser and navigate to https://www.airserbia.com.<br>
2. Make sure you are in the “Round trip” section.<br>
3. In the "From field, enter the location "Tirana".<br>
4. In the "To" field, enter the location "Athens".<br>
5. In the "Date range" field, enter the dates from available time range.<br>
6. Click "Show flights".</td><td>1. The homepage loads successfully without any errors.<br>
2. The button “Round trip” is active and highlighted in blue.<br>
3. It is possible to select "Tirana" from the drop-down list.<br>
4. It is possible to select "Athens" from the drop-down list.<br>
5. It is possible to select the dates from available time range.<br>
6. The page is loading results for the selected flight criteria.</td><td>Passed</td></tr>
    <tr><td colspan="2">Execution type:</td><td colspan="2">Manual</td></tr>
    <tr><td colspan="2">Priority</td><td colspan="2">Medium</td></tr>
    <tr><td colspan="2"><b>Execution details<b></td><td colspan="2"></td></tr>
    <tr><td colspan="2">Build</td><td colspan="2">0.0.9</td></tr>
    <tr><td colspan="2">Tester</td><td colspan="2">Natela</td></tr>
    <tr><td colspan="2">Execution result</td><td colspan="2">Passed</td></tr>
    <tr><td colspan="2">Execution duration</td><td colspan="2">30.00</td></tr>
  </tbody>
</table>

