## Workflow 4


- Start with “On Form Submission” – when someone fills and submits the form, the workflow begins.
- The submitted form data is added to your Google Sheet using the Append Row in Sheet node.
- The Google Sheets Trigger watches the sheet and detects whenever a new row is added.
- When a new row appears, the trigger sends that data to the Send a Message (Gmail) node.
- Gmail automatically sends you an email notifying that a new entry was added in your sheet.
- When you click Execute Workflow, you can test the entire flow and see the email instantly.


## Screenshot

<img width="1919" height="895" alt="Screenshot 2025-11-22 123723" src="https://github.com/user-attachments/assets/1bacdcfd-f0e7-41e5-899e-7821c0a67b7c" />
