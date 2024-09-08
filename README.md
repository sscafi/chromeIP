
# IP Address Monitor Chrome Extension
## Overiew

The **IP Address Monitor** Chrome extension allows users to monitor IP addresses associated with resources loaded by the current website. It logs the IP addresses and displays them in an extension popup, helping users identify foreign IP addresses for enhanced security.


## Features

- Monitors network requests of the current page.
- Resolves IP addresses of the requested resources using a web-based API.
- Logs the IP addresses with associated URLs and timestamps.
- Provides a popup interface to view the logs.
- 
## Installation
 **Download or Clone the Repository**

   -bash
   git clone https://github.com/sscafi/chromeIP.git
## Prerequisites

-Google Chrome browser


## Configuration

-API Key
The extension uses a web-based API to resolve IP addresses. Replace YOUR_API_KEY in background.js with a valid API key from a suitable IP geolocation or domain-to-IP resolution service.

Example API Services:

-IP Geolocation API
-WhoisXML API
-IPinfo
## Usage/Examples

1.Access a Website
Navigate to any website you want to monitor in Chrome.

2.View Logs
Click on the IP Address Monitor extension icon in the Chrome toolbar.
Click the "Refresh Logs" button in the popup to view the IP addresses logged during your browsing session.


## Files
- **`manifest.json`**: Defines the extension’s metadata and permissions.
- **`background.js`**: Handles web request monitoring and IP address logging.
- **`content.js`**: (Optional) Injects JavaScript into web pages if needed.
- **`popup.html`**: Provides the HTML structure for the extension’s popup.
- **`popup.js`**: Manages interactions with the popup and displays logs.
## Contributing

Contributions are always welcome!

Please adhere to this project's `code of conduct`.

