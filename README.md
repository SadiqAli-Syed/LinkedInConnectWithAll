# LinkedInConnectWithAll

**LinkedInConnectWithAll** is a browser extension that automates the process of sending connection requests to all suggested profiles on LinkedIn's "My Network" page. With a single click, users can efficiently connect with multiple people, streamlining the networking process.

## Features

- **One-Click Connections**: A floating button labeled "Connect with All" appears on the bottom right of the LinkedIn "My Network" page. Clicking it will automatically send connection requests to all suggested people.
- **Smart Delays**: The extension uses asynchronous requests with built-in delays to mimic human behavior, preventing potential issues with LinkedIn's activity monitoring.
- **Modern Tech Stack**: Built using the WXT framework, React, and TypeScript for a responsive and efficient extension experience.

## How It Works

1. The extension injects a floating button on LinkedIn’s "My Network" page.
2. Upon clicking the button, it finds all "Connect" buttons on the page and clicks them one by one.
3. Delays are added between each request to prevent overloading LinkedIn’s system and avoid detection as automated behavior.

## Installation

### Steps:

1. **Download the Latest release**
2. **Extract the Files for Zip File**
3. **Load(UnPacked) the extracted folder in chrome://Extentions as a Developer**
4. **You are ready to go!.**
