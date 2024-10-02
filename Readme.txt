Amera Exports Pvt. Ltd. - Material Outward Record Form
Overview
This project is an HTML-based form designed to record material outward details for Amera Exports Pvt. Ltd. It features a user-friendly interface that allows users to input, preview, and submit bulk item outward records. The form is integrated with Google Apps Script for handling form submissions and updating Google Sheets with the data.

Features:
Tabbed Interface: Three main sections:
Outward Form: Fill in the required details.
Preview Data: Review your input before submitting.
Last Data: View your last submitted record.
Data Preview: Users can preview the data before submitting, ensuring accuracy.
Editable Fields: If the user detects any errors in the preview, they can go back and edit the form.
Reset Option: A reset button is provided to clear all fields and start fresh.
Submit Functionality: Submits data to a Google Apps Script that writes the data into a Google Sheets document.
Project Structure
bash
Copy code
.
├── index.html           # The main HTML file containing the form and preview tabs
├── img/
│   ├── onlylogo.png     # Company logo used in the sidebar
├── README.md            # Documentation of the project
HTML File Breakdown
Sidebar: A fixed navigation bar on the left side of the page that contains links to navigate through the form, preview, and last data tabs.

Tabs:

Outward Form: This section includes fields like Dispatch Date, Invoice Date, Docket No., Courier Name, and others. The form is designed for bulk item outward records.
Preview Data: After filling the form, users can preview their data in this tab to ensure everything is correct before submission.
Last Data: This tab displays the last submitted record for reference.
Form Validation: Ensures that all required fields are filled out before the form can be previewed.

Preview Functionality: JavaScript is used to display the form data in the preview tab and allows the user to return to the form to edit if needed.

Google Apps Script Integration: The form submission is handled via Google Apps Script, which writes the form data to a Google Sheets document.