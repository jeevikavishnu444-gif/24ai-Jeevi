- Execute Trigger
     Use “When clicking ‘Execute workflow’” to manually start the workflow for testing.
- Read Data From Sheet
     Connect it to “Get row(s) in sheet” to fetch all existing rows from the Google Sheet.
- Add IF Condition
     Use an IF node to check a specific column or value (e.g., count, status, match, etc.).
- True Path → Append to Sheet A
     If the condition is true, send the data to “Append row in sheet” (first Google Sheet).
- False Path → Append to Sheet B
     If the condition is false, send the data to “Append row in sheet1” (second Google Sheet).


#ScreenShort: 
<img width="1337" height="527" alt="Screenshot 2025-11-23 100526" src="https://github.com/user-attachments/assets/b0e02353-ffd2-4fa2-a74b-ddf50957718c" />
