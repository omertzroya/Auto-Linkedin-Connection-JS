# LinkedIn Connection Automation Script

This script automates the process of sending connection requests on LinkedIn. It scrolls through the search results, identifies "Connect" buttons, and sends connection requests with or without a personalized note.

## Configuration

The script configuration is defined in the `Linkedin.config` object. Below are the configurable parameters:

- `scrollDelay`: Delay (in milliseconds) before scrolling to the top or bottom of the page.
- `actionDelay`: Delay (in milliseconds) between actions like clicking buttons.
- `nextPageDelay`: Delay (in milliseconds) before moving to the next page.
- `maxRequests`: Maximum number of connection requests to send. Set to -1 for no limit.
- `totalRequestsSent`: Counter for the total number of requests sent.
- `addNote`: Set to `true` to add a personalized note to connection requests, `false` to skip.
- `note`: The personalized note to send with connection requests. Use `{{name}}` to include the recipient's first name.

## Usage

To use this script, follow these steps:

1. Open LinkedIn and perform a search for people you want to connect with.
2. Open the browser's Developer Tools (usually by pressing `F12` or `Ctrl+Shift+I`).
3. Go to the "Console" tab.
4. Copy and paste the entire script into the console.
5. Press `Enter` to run the script.
