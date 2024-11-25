# NNOS Browser

NNOS Browser is a simple browser interface designed with HTML, CSS, and JavaScript. It features a customizable theme, tab management, bookmarks, and an extension store. This browser UI is not a fully functional browser but a frontend interface meant for educational purposes or as a starting point for a more advanced project.

## Features

- **Tab Management**: Open, switch, and close multiple tabs.
- **Bookmarks**: Add and manage bookmarks easily.
- **Theme Customization**: Switch between light, dark, and colorful modes.
- **Extension Store**: A demo section for installing hypothetical extensions.
- **URL Navigation**: Navigate to valid URLs or perform a search if the input is not a URL.
- **Persistent Data**: Tabs, bookmarks, and settings are stored in `localStorage`.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/natuworkguy/nnos-browser.git
   cd nnos-browser
   ```
2. Open `[VERSION]/index.html` in any modern web browser.

## Usage

### Navigation
1. Enter a URL in the address bar and click "Go" to load the page.
2. Use "Back" and "Forward" buttons to navigate through the tab history.

### Tabs
- Click "New Tab" to create a new tab.
- Click on a tab name to switch to it.
- Close a tab by clicking the "X" on the tab.

### Bookmarks
- Click "Bookmark" to save the current URL.
- View and manage bookmarks in the bookmarks section.

### Themes
- Open the settings menu using the "Settings" button.
- Toggle between dark, light, or colorful themes.

## Code Structure

- **HTML**: Defines the layout and structure.
- **CSS**: Includes themes and responsive design.
- **JavaScript**: Implements functionality like tab navigation, bookmarks, and theme toggles.

## Customization

1. **Themes**: Modify `:root` variables in the CSS for custom themes.
2. **Extensions**: Add new entries to the extension store in the HTML and implement related functionality in the JavaScript.

## Limitations

- **No Real Browsing**: The `iframe` element is used for displaying content, but it cannot replicate a full browser's capabilities.
- **Security**: Does not handle HTTPS certificates or advanced security features.
- **Limited Search**: Redirects invalid URLs to a placeholder search engine.

## Contribution

Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
