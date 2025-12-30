# Browser Context AI Research Assistant

A Chrome extension with a backend service that provides AI-generated, citation-backed answers based on the content of active browser tabs.

## Features

- AI-generated answers grounded in active tab content
- Highlight-to-explain functionality for selected text
- Quoted citations sourced directly from the webpage
- Backend support for context management and response logging

## Instructions for Use

### Load the Chrome Extension

This extension is not published on the Chrome Web Store and must be loaded manually.

1. Clone the repository:
   `git clone https://github.com/kkeahi/Browser-Context-AI.git`

2. Open Chrome and navigate to:
   chrome://extensions

3. Enable Developer mode

4. Click Load unpacked

5. Select the directory containing the Chrome extension source

### Run the Backend Service

1. Navigate to the backend directory

2. Start the backend service:
   `mvn spring-boot:run`

3. Keep the backend running while using the extension

## Using the Extension

1. Navigate to any webpage

2. Open the extension from the Chrome toolbar

3. Enter a prompt related to the current page to receive an AI-generated response with quotes and citations

4. Highlight text on the page to trigger the highlight-to-explain functionality
