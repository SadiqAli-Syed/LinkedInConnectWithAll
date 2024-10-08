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

1. **Clone the repository**

2. **cd LinkedInConnectWithAll**

3. **npm install**

4. **npx wxt build -b chrome**

5. **Load the extension to your Browser**

6. **Visit www.Linkedin.com/mynetwork and click the "Connect with All" Button**

7. And the **Holy Grail**, this stuff **works on my machine**,
8. The above steps were not verified on a different PC so, You may need to configure your machine on your end, maybe **check/reinstall** packages and **ask** ChatGPT!.

