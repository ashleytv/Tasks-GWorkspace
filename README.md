# Tasks-GWorkspace
Scripts used to connect the Sheets, Calendar, Tasks, and Forms applications to manage the list of tasks to be performed using Apps Script.

Setup and Configuration
To get this project running correctly, please follow these steps:

1. Update Script Constants
Calendar API: Open CalendarApp.gs and update the email variable on line 1 with your Google Calendar ID (usually your Gmail address).

Tasks API:

Open TasksApp.gs.

Run the getTaskLists() function first. Check the Execution Log to find your specific Task List IDs.

Update the constants on lines 1 and 2 with the IDs you obtained.

2. Enable Services and Permissions
Enable Tasks API: You must manually add the Tasks Service in the Apps Script editor (click on the "+" next to Services and select Tasks API).

Authorization: Run each main function at least once directly from the Apps Script editor. This will trigger the OAuth dialog so you can review and accept the necessary access permissions.
