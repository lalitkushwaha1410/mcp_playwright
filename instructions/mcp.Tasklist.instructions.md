**TASK: Execute Test Scenario from Excel using MCP Tools**
 
**OBJECTIVE:**
Execute a specific test scenario from an Excel file and update the test status, using **only MCP tools** (no custom automation scripts).
 
**REQUIREMENTS:**
 
1. **Browser Navigation:**
   - Navigate to: https://authoring.systest.cha.rbxd.ds/review-requests/
   - Use credentials:
     - Username: SptCmsTestEditor@cha.rbxd.ds
     - Password: Passw0rd
   - Mode: Headful (visible browser)
   - Tool: Use Playwright MCP
 
2. **Write Scenerios to Excel:**
   - File: `Tasklist-scenarios.xlsx`
   - Path: `C:\Nagarro_data\MCP-Server\MCP-output\New scenarios.xlsx`
   - Action: Generate test scenarios for the provided application
   - Output: Write the **10 most appropriate test scenarios** to the **"Test Scenario"** column in the Excel file
 
3. **Read from Excel:**
   - File: `Tasklist-scenarios.xlsx`
   - Path: `C:\Nagarro_data\MCP-Server\MCP-output\New scenarios.xlsx`
   - Action: Read the scenario from the specified row under the **"Test Scenario"** column
 
4. **Write Status to Excel:**
   - File: `Tasklist-scenarios.xlsx`
   - Path: `C:\Nagarro_data\MCP-Server\MCP-output\New scenarios.xlsx`
   - Action: Write the **execution status** to the **"Test Status"** column in the same row
 
 
5. **Execution Flow:**
   a. Open the browser in **headful** mode  
   b. Navigate to the application using the provided credentials  
   c. Analyze functionalities to be tested  
   d. List down all possible test scenarios for the application  
   e. Select the 10 most appropriate test scenarios  
   f. Write them to the **"Test Scenario"** column in the Excel file  
   g. Execute the test scenario specified in the Excel file  
   h. Update the execution status in the **"Test Status"** column  
   i. Provide **detailed logs** of the test execution in the chat  
   j. Take a **screenshot** of the application state during execution ,create a screenshot folder in the same directory and store in it. 
   k. Close the browser after test execution  
 
**CONSTRAINTS:**
   - Use **only** MCP tools (Playwright, Excel, Filesystem)
   - **Do not** use any custom automation scripts
   - Only write test scenarios when prompted to do so
   - Handle all errors gracefully and report them clearly
   - Document each step taken and its result
 
**DELIVERABLES:**
- Confirmation of successful navigation
- Screenshot of application state
- Updated Excel file with test status
- Summary of actions performed