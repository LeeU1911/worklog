# Worklog

Worklog is a simple, elegant, and efficient web-based tool for maintaining your daily work log. It's designed to be lightweight, easy to use, and requires no backend server or database.

## Features

- Single-page application built with HTML, CSS, and JavaScript
- Clean, minimalist interface inspired by Basecamp's aesthetic
- Easy input of work items with automatic date grouping
- Entries displayed in reverse chronological order
- Data persists in the browser using localStorage
- Fully client-side, can be hosted on GitHub Pages

## How to Use

1. Visit the deployed Worklog page (or open the HTML file in your browser).
2. Type your work item in the input field.
3. Press Enter to save the item.
4. Your entry will be saved and displayed under today's date.
5. Previous entries are grouped by date in reverse chronological order.

## Local Development

To run Worklog locally:

1. Clone this repository:
`git clone https://github.com/leeu1911/worklog`

2. Navigate to the project directory:
`cd worklog`

3. Open `index.html` in your web browser.

## Deployment

Worklog can be easily deployed using GitHub Pages:

1. Push your changes to your GitHub repository.
2. Go to your repository's Settings.
3. Scroll down to the "GitHub Pages" section.
4. In the "Source" dropdown, select "main" branch and "/root" folder.
5. Click Save.

Your Worklog will now be available at `https://leeu1911.github.io/worklog/`.

## Privacy and Data Storage

Worklog uses your browser's localStorage to save entries. This means:

- Your data stays on your device and is not sent to any server.
- Clearing your browser data will erase your Worklog entries.
- Different devices or browsers will have separate Worklog data.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
