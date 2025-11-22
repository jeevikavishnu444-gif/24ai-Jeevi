- Add the “On Form Submission” node
    This triggers the workflow whenever someone submits the form.
- Add the AI Agent node
    Connect the form trigger → AI Agent.
- Add the Google Gemini Chat Model node
    Set your Gemini API key and choose the model (e.g., gemini-1.5-flash).
- Connect Gemini → AI Agent
   Drag the output of the Gemini node into the AI Agent → Chat Model input.
- Add Send a message (Gmail)
    Connect AI Agent → Gmail node → then Save & Activate the workflow.

 #Screenshort:
<img width="1170" height="536" alt="Screenshot 2025-11-22 150418" src="https://github.com/user-attachments/assets/16677413-62ce-40ca-952b-7dcb09042614" />
