# Privacy Policy for Screenshot Search

**Last Updated: December 28, 2024**

## Overview

Screenshot Search is a Chrome extension that helps users capture screenshots and search them on Google Images. This privacy policy explains how the extension handles your data.

## Data Collection

**Screenshot Search does NOT collect, store, or transmit any personal data.**

## How the Extension Works

1. **Screenshot Capture**: When you click the extension icon, it captures a screenshot of the visible portion of your current browser tab using Chrome's built-in `chrome.tabs.captureVisibleTab` API.

2. **Local Processing**: The screenshot is processed entirely in your browser. You select a region, and the extension crops the image locally.

3. **Google Images Upload**: The cropped screenshot is automatically uploaded to Google Images (images.google.com) using their standard upload mechanism. This is equivalent to manually uploading an image to Google Images yourself.

## Data Storage

- **No Data Storage**: The extension does not store any screenshots, browsing history, or personal information.
- **No External Servers**: All processing happens locally in your browser.
- **No Analytics**: We do not use any analytics or tracking services.

## Permissions Explained

The extension requests the following permissions:

- **activeTab**: Required to capture screenshots of the current tab you're viewing
- **scripting**: Required to inject the selection overlay onto the webpage
- **offscreen**: Required to crop images using HTML5 Canvas API
- **tabs**: Required to create a new tab for Google Images search results
- **host_permissions (*.google.com)**: Required to automatically upload screenshots to Google Images

## Third-Party Services

The only third-party service the extension interacts with is **Google Images** (images.google.com). When you complete a screenshot selection:

1. The extension opens Google Images in a new tab
2. The cropped screenshot is uploaded using Google's standard upload mechanism
3. Google's privacy policy applies to this upload: https://policies.google.com/privacy

The extension does not control how Google processes your uploaded images. Please refer to Google's privacy policy for information on how they handle image uploads.

## Data Security

- All screenshot processing happens locally in your browser
- Screenshots are only sent to Google Images when you complete a selection
- No data is sent to any other servers or third parties

## Children's Privacy

This extension does not knowingly collect information from children under 13. The extension does not collect any personal information from any users.

## Changes to This Policy

We may update this privacy policy from time to time. Any changes will be reflected in the "Last Updated" date above.

## Contact

If you have questions about this privacy policy, please contact:
- GitHub Issues: [Create an issue on our repository]
- Email: [Your email address]

## Consent

By using Screenshot Search, you consent to this privacy policy.
