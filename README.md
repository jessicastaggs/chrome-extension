# Leads Tracker Chrome Extension

The Leads Tracker Chrome extension allows you to save and manage leads you find online. It's a useful tool for anyone who needs to keep track of potential clients, job opportunities, or any other important links. This project was developed following Scrimba's "Learn JavaScript - Build a Chrome Extension" course. 

## Features

* Save the current tab's URL as a lead.

* View a list of saved leads.

* Delete individual leads or clear all leads.

* Data persistence using 'localStorage".

---------------------------------

## Concepts Learned

1. DOM Manipulation:

    * I used 'document.getElementById' to access HTML elements by their IDs and manipulate them.

    * I dynamically updated the HTML content using 'innerHTML'.

2. Event Handling:

    * I attached event listeners to buttons using 'addEventListener' to handle clicks and double-clicks.

    * I handled user input and actions, such as clicking buttons to add, delete, or save leads.

3. Local Storage:

    * I used 'localStorage' to persist data across browser sessions.

    * I stored and retrieved data as JSON strings using 'JSON.stringify' and 'JSON.parse'.

4. Functions:

    * I created and used fuctions, such as the 'render' function, to encapsulate and reuse code.

    * I passed parameters to functions and manipulated them within.

5. Template Literals:

    * I used template literals (backticks `) to create multi-line strings and embed expressions within them using '${}'.

6. Chrome Tabs API:

    * I used the 'chrome.tabs.query' method to interact with the browser's tab system.

7. Conditional Statements:

    * I used 'if' statements to check conditions, such as whether there are leads stored in 'localStorage'.

8. Loops:

    * I used a 'for' loop to iterate over the 'leads' array and generate list items dynamically.

---------------------------------

## Upcoming Enhancements

Here are some planned improvements and new features I would love to add to this extension in the future:

1. Search Functionality:

    * Implement a search bar to quickly find specific leads.

    * Add advanced search options to filter leads by date, tags, or other criteria.

2. Notes and Comments:

    * Allow users to add notes or comments to each lead for additional context.

    * Implement a rich text editor for better formatting of notes.

3. Lead Import/Export:

    * Add the ability to import leads from CSV or Excel files.

    * Allow users to export their leads to CSV or other formats for backup or sharing.

4. Mobile Responsiveness:

    * Ensure the application is fully responsive and works well on mobile devices.

    * Consider creating a mobile app version for easier access on smartphones.

5. Integration with Other Tools:

    * Integrate with other tools like CRM systems, email marketing platforms, or social media.

    * Use APIs to sync leads between different applications.

6. User Interface Improvements:

    * Enhance the user interface with a more modern design and improved usability.

    * Add drag-and-drop functionality for easier lead management.

---------------------------------

## Instructions to Clone and Run Repository

1. Open the Terminal (for macOS or Linux) or Command Prompt (on Windows).

2. Navigate to the desired directory where you want to clone the repository, use 'cd' command to navigate to directory.

3. Clone the repository. Use 'git clone' command followed by the repository URL to set up repository.

4. Open Chrome and navigate to chrome://extensions.

5. Enable "Developer mode" by toggling the switch in the top right corner.

6. Click on the "Load upacked" button and select the directory where you cloned/downloaded the project.

---------------------------------

## Technical Information

The Scrimba "Learn JavaScript - Build a Chrome Extension" course can be found [here.](https://scrimba.com/learn-javascript-c0v/~03i)