# smugglo

An easy-to-use script for wrapping files into self-dropping HTML payloads to bypass content filters.

**Version:** 1.0.0

## Features

- **One-file payload:** Wrap any file into a single self-contained HTML file
- **Automatic extraction:** The generated HTML auto-extracts and downloads the file when opened (no clicks needed)
- **Data hiding options:** Supports XOR obfuscation, AES-GCM encryption, Base64 or hex encoding to conceal content
- **Stealth injection:** Option to stash file data in CSS variables for extra sneakiness
- **Bypass filters:** Slip past content filters and sandboxes by masquerading as a harmless HTML page (classic HTML smuggling trick)

## How It Works

1. **Select a file:** Use the file input to choose any file from your system.
2. **Choose a method:** Pick one of the embedding methods:
   - **CSS Encoding**
   - **XOR Encryption**
   - **AES Encryption**
   - **Base64 Encoding**
   - **Hex Encoding**
3. **Generate HTML:** Click the button and smugglo wraps your file into a self-contained HTML file.
4. **Automatic Extraction:** When the HTML payload is opened in a browser, it automatically decodes/decrypts the embedded file and triggers its download.

## Live Demo

Try smugglo directly in your browser:

[https://b3rito.github.io/smugglo/](https://b3rito.github.io/smugglo/)

## Author

Written by **b3rito** at mes3hacklab & **GioPpeTto**
