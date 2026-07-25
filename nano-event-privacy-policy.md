# Privacy Policy for NanoEvent - AI Calendar Assistant

**Last Updated**: July 25, 2026

## Overview

NanoEvent ("we", "our", or "the extension") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and protect information when you use our Chrome extension. NanoEvent is a privacy-first utility designed to extract event details from web pages, text selection, and images, and format them for calendar export.

## Information We Collect & Process

### Content You Choose to Process
- **Selected Text & Content**: When you select text or an image on a webpage and choose "Extract Event with NanoEvent", the extension temporarily accesses that content to parse dates, times, locations, and titles.
- **Image Content**: If you select an image (such as an event flyer), the extension processes the image data to perform text extraction (OCR).

### Information We Do NOT Collect
- We do not collect or store personal identification information.
- We do not collect or track your browsing history or web activity.
- We do not access tab content unless you explicitly select it and run the extension action.
- We do not store your extracted calendar events, emails, or scheduling data on our servers.

## How We Use Information

### Content Processing
- **Local AI Execution (Default)**: NanoEvent is designed around on-device processing. Whenever possible, date and event extraction is done locally in your browser using Chrome's built-in Gemini Nano model. No data is transmitted to external servers for this local extraction.
- **Optional Fallback Cloud AI API**: If you choose to configure a fallback provider (such as OpenRouter), the selected text is transmitted to the API endpoint you configure. This data is subject to the terms and privacy policy of that third-party provider (e.g., OpenRouter).
- **Payment & License Verification**: We use ExtensionPay (ExtPay) to manage subscriptions ($5.99/mo with a free trial). License checks are handled securely via ExtPay's servers, which process billing and trial data.

### Permissions Usage
- **activeTab**: Used to access selected text/images on your active page when you trigger the extension action.
- **contextMenus**: Adds the right-click option "Extract Event with NanoEvent" to webpage context menus.
- **storage**: Used to store your extension preferences, calendar choice, and optional API keys locally.
- **downloads**: Used to save generated `.ics` calendar files directly to your machine.
- **scripting**: Used to run the extraction helper script on the webpage you explicitly trigger it on.
- **tabs**: Used to open calendar export links (like Google Calendar or Outlook Web) in a new browser tab.
- **Host Permissions (`https://extensionpay.com/*`, `https://openrouter.ai/*`)**: Used to process payments/subscription status and route optional fallback AI requests.

## Data Sharing

- **ExtensionPay**: Security token and subscription identifier are shared with ExtensionPay for license validation.
- **No Third-Party Sharing**: We do not sell, rent, or share your data with advertisers, third-party brokers, or anyone else. 

## Data Security

- All configuration data, API keys, and settings are stored locally on your device using Chrome's secure storage API.
- All network communications (such as payment verification or optional fallback API calls) are encrypted using HTTPS.

## Your Rights and Controls

- You have full control over when the extension accesses page content by initiating the highlight or right-click action.
- You can uninstall the extension or revoke any permissions at any time through Chrome's extension manager.
- You can clear your API key settings or reset settings inside the extension popup options.

## Changes to Privacy Policy

We may update this Privacy Policy occasionally. When we do, we will update the "Last Updated" date at the top of this document.

---

**Summary**: NanoEvent processes text and image selections locally using on-device AI. We do not track you, collect personal data, or sell your information. Subscription billing is handled securely via ExtensionPay, and optional cloud fallbacks are fully controlled by you.
