# HTML CSV Link Viewer

## Overview

The HTML CSV Link Viewer is a simple, browser-based tool that displays links from a CSV file, organized into groups. It automatically reads a local CSV file named `data.csv` and renders the contents as clickable links, grouped by categories.

## Features

- Automatically loads and parses a CSV file named `data.csv`
- Groups links by category for easy navigation
- Responsive design for comfortable viewing on various devices
- Opens links in new tabs when clicked
- Supports CSV fields that contain commas (when enclosed in quotes)
- Alphabetical sorting of groups
- Error handling for file access and formatting issues

## Requirements

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A CSV file named `data.csv` in the same directory as the HTML file

## CSV File Format

The `data.csv` file must include three columns with the following headers:

- `url`: The web address the link should point to
- `description`: The text that will be displayed for the link
- `group`: The category name for grouping the link

Example CSV content:

```csv
url,description,group
https://example.com,Example Website,Work
https://github.com,GitHub,Development
https://docs.python.org,Python Documentation,Development
https://news.ycombinator.com,Hacker News,Tech News
https://stackoverflow.com,Stack Overflow,Development
```

## How to Use

1. Ensure you have both the `index.html` and `data.csv` files in the same directory
2. Edit your `data.csv` file to include the links you want to display
3. Open the `index.html` file in a web browser
4. The links will be automatically loaded and displayed, grouped by their categories

## Customization

You can customize the appearance of the page by modifying the CSS styles in the `<style>` section of the HTML file.

## Troubleshooting

If your links don't appear:

- Check that your CSV file is named exactly `data.csv` and is in the same directory as the HTML file
- Ensure your CSV file has the correct headers: `url`, `description`, and `group`
- Verify that your CSV file is properly formatted
- Check the browser console for any JavaScript errors

## License

This tool is provided as-is for personal and educational use.

