# Lead Tracker Extension

A lightweight Chrome browser extension that helps you save and track leads efficiently. Capture important contact information and URLs directly from your browser with just one click.

## Features

- **Quick Lead Capture** - Save leads with a single click from the popup interface
- **Persistent Storage** - All saved leads are stored locally in your browser
- **Easy Organization** - View and manage all your leads in a clean, organized interface
- **Fast Access** - Quick access popup makes capturing leads seamless
- **No Account Required** - All data stored locally on your device

## Installation

1. Clone or download this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable **Developer mode** (toggle in the top right)
4. Click **Load unpacked** and select the extension folder
5. The Lead Tracker Extension will now appear in your Chrome extensions

## Usage

1. Click the Lead Tracker Extension icon in your Chrome toolbar
2. The popup will open with the extension interface
3. Enter lead information (name, email, phone, company, etc.)
4. Click **Save Lead** to store the information
5. View all your saved leads in the popup
6. Your leads are automatically saved to your browser's local storage

## Project Structure

```
Lead-Tracker-Extension/
├── manifest.json      # Extension configuration and metadata
├── index.html         # Popup interface HTML
├── script.js          # Main JavaScript functionality
├── styles.css         # Styling for the popup
├── icon.png          # Extension icon
└── package.json      # Project metadata
```

## File Descriptions

- **manifest.json** - Defines extension permissions, name, version, and entry points
- **index.html** - HTML structure for the popup interface where users interact with the extension
- **script.js** - Contains all JavaScript logic for saving, retrieving, and managing leads
- **styles.css** - CSS styling for the popup UI to make it visually appealing
- **icon.png** - The icon displayed in the Chrome extensions list and toolbar

## Technologies Used

- **HTML5** - Structure and markup
- **CSS3** - Styling and layout
- **JavaScript (ES6+)** - Core functionality and logic
- **Chrome Storage API** - Local data persistence

## How It Works

1. The extension creates a popup interface when clicked
2. Users can input lead information through the form
3. JavaScript handles form submission and data validation
4. Data is stored in Chrome's local storage using the Storage API
5. All leads are retrieved and displayed when the popup is opened
6. Users can view, manage, and interact with their saved leads

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub repository.

---

**Happy lead tracking!** 🚀