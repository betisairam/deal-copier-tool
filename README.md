Deal Copier Tool
A simple web-based tool to automatically replace Amazon affiliate tags and copy the modified content to your clipboard. It also clears the pasted content after a delay and automatically focuses back to the textarea.

Features
Automatic Tag Replacement: Replaces the tag (prolooterzz-21) with dealmatch-21 in pasted URLs.

Clipboard Copy: Copies the modified content to the clipboard automatically.

Content Clearing: Clears the pasted content after 7 seconds.

PWA Support: Install the tool on mobile or desktop for offline use.

Toast Notifications: Displays toast messages for successful actions like copying and clearing.

Demo
You can try out the tool directly by accessing it in your browser.

Example Flow:
Paste your deal content.

The tool automatically replaces affiliate tags in the URLs.

The modified content is copied to the clipboard.

The content is cleared after 7 seconds, and the cursor focuses back for the next action.

Installation
To use this project locally or deploy it:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/deal-copier-tool.git
cd deal-copier-tool
Open the index.html file in any modern web browser.

For local development, you may want to run it using a local server:

bash
Copy
Edit
python -m http.server 8000
Deploy it to any static hosting platform (e.g., GitHub Pages, Netlify, Vercel).

How to Use
Paste your deal text into the textarea on the homepage.

The tool will automatically modify any Amazon product URL by replacing the tag parameter.

Once processed, the modified text will be copied to your clipboard.

After 7 seconds, the content will be cleared, and the textarea will be ready for the next deal.

Technologies Used
HTML: For the structure.

CSS: For styling.

JavaScript: For the clipboard functionality and dynamic behavior.

Service Worker: For PWA (Progressive Web App) functionality, allowing offline usage.

Manifest: Allows the app to be installed on mobile or desktop devices.

PWA Features
Installable as a standalone app.

Works offline.

Simple and fast to use directly from your phone or desktop.

License
This project is open-source and available under the MIT License. See the LICENSE file for more details.

Contributing
Fork the repository.

Create a new branch (git checkout -b feature/your-feature).

Commit your changes (git commit -am 'Add your feature').

Push to the branch (git push origin feature/your-feature).

Open a pull request.