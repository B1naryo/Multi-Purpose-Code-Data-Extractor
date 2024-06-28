# Multi-Purpose Code Data Extractor

This HTML file contains a script to extract various types of data (URLs, emails, hashes, sensitive keywords) from code snippets entered into a textarea. It provides a dropdown menu for selecting the type of data to extract, including JSON, HTML (links and script content), JavaScript, emails, hashes, and sensitive keywords like passwords and admin credentials.

## Usage

1. **Select Data Type**: Choose the type of data you want to extract from the dropdown menu (`<select>`):
   - JSON: Extracts URLs from JSON objects.
   - HTML (tags 'a' and 'script'): Extracts URLs from `<a>` tags and script content from `<script>` tags.
   - JavaScript: Extracts URLs using a regular expression from JavaScript code.
   - Emails: Extracts email addresses from any text.
   - Hashes: Extracts hash values (e.g., MD5 hashes) from any text.
   - Sensitive Keywords: Extracts sensitive keywords like passwords, admin, etc., from any text.

2. **Paste Code**: Paste your code snippet into the textarea (`<textarea>`).

3. **Extract Data**: Click the "Extract Data" button (`<button>`) to initiate the extraction process.

4. **View Results**: Extracted data will be displayed below the textarea in a formatted list (`<ul>`). If no data is found, it will show "No data found."

## Features

- Supports extraction of URLs from JSON objects, HTML `<a>` tags, and JavaScript code.
- Extracts email addresses, hash values, and sensitive keywords from any text input.
- Handles parsing errors and displays appropriate error messages if the input format is incorrect.

## Error Handling

If there are any errors during the data extraction process (e.g., invalid JSON format, incorrect HTML structure), the script will display an error message indicating the issue.

## Compatibility

This script runs entirely on the client-side using JavaScript and HTML, making it compatible with most modern web browsers without any additional dependencies.



