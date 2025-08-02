**TASK: Execute Test Scenario from JIRA using MCP Tools**
 
**OBJECTIVE:**
Execute a specific test scenario from the JIRA ticket and update the test status, using **only MCP tools** (no custom automation scripts).
 
**REQUIREMENTS:**
 
1. **Browser Navigation:**
   - Navigate to: https://www.saucedemo.com/v1/index.html
   - Use credentials:
     - Username: standard_user
     - Password: secret_sauce
   - Mode: Headful (visible browser)
   - Tool: Use Playwright MCP
 
2. **Read the scenerio from JIRA**
   - JIRA ticket: https://lalitkush14.atlassian.net/browse/SCRUM-3
   - Tool: Use Atlassian MCP
   - Action: Read the description to understand the scenario
   - Output: Once executed, Write the status in the comment section of the JIRA ticket
 
3. **Execution Flow:**
   a. Access the JIRA ticket to analyze the requirement
   b. Open the browser in **headful** mode
   c. Navigate to the application using the provided credentials
   d. Analyze functionalities to be tested
   e. List down all possible test scenarios for the application
   f. Select the 3 most appropriate test scenarios for testing
   g. Write them to the comment section of the JIRA ticket with screenshots attached.
   h. Execute the specified test scenario from the JIRA ticket
   i. Update the execution status in front of the test scenario in the JIRA comment section
   j. Provide **detailed logs** of the test execution in the chat
   k. Take a **screenshot** of the application state during execution
   l. Close the browser after test execution
 
**CONSTRAINTS:**
   - Use **only** MCP tools (Playwright, Atlassian)
   - **Do not** use any custom automation scripts
   - Only write test scenarios when prompted to do so
   - Handle all errors gracefully and report them clearly
   - Document each step taken and its result
 
**DELIVERABLES:**
- Confirmation of successful navigation
- Screenshot of application state
- Updated JIRA ticket with test status
- Summary of actions performed
 
Using instructions,,analyse the requirement from the JIRA ticket and execute the same.