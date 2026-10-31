# Privacy Policy for NanoEvent

**Last Updated**: October 31, 2026

## Overview

NanoEvent ("we", "our", or "the extension") turns text and images you select into calendar events. This policy explains what the extension sends, where it goes, and what it does not do.

## What NanoEvent processes

- **Text you select**: when you highlight text and choose "Extract Event with NanoEvent", that text is used to find the event's title, date, time and location.
- **Images you select or crop**: when you right-click an image or use the crop tool, that image is used the same way.

NanoEvent does not read pages you don't extract from.

## Where your content is sent

NanoEvent reads event details with a cloud AI model (Google Gemini). When you run an extraction, and only then:

1. The selected text or image is sent over HTTPS to the developer's AI server (`aistudio.share.zrok.io`), which passes it to the AI model and returns the event details.
2. If that server is unavailable, the same request is sent to **OpenRouter** (`openrouter.ai`), which routes it to a Google Gemini model. OpenRouter's handling is covered by its own privacy policy: https://openrouter.ai/privacy

Your content is used only to return the event details. The developer does not store it, and it is not used for advertising or any other purpose.

## Anonymous usage counts

So the developer can tell whether NanoEvent works for people, it sends a small anonymous report to `extstats.share.zrok.io` when it is installed, when you send an event to Google Calendar, and when an error happens. A report contains only the extension's public ID and version, the event, and for errors a shortened error message with file names, web addresses, numbers and quoted text removed. It never contains the text or images you select, event details, your emails or calendar, or any identifier for you or your browser. The server keeps daily totals only and doesn't store IP addresses.

## What we do NOT collect

- No account, name, email address or other personal identification.
- No browsing history or tracking. The only usage data are the anonymous counts above.
- No storage of your events, emails or schedules on any server.
- No sale or sharing of data with advertisers or data brokers.

## Permissions

- **activeTab**: reads the text or image you select on the current tab when you run the extension.
- **contextMenus**: adds "Extract Event with NanoEvent" to the right-click menu.
- **storage**: saves your preferences (such as the theme) in your browser.
- **scripting**: runs the selection and crop helper on the page where you start an extraction.
- **Host permission** (`https://openrouter.ai/*`): sends the extraction request to the fallback AI endpoint described above.

Calendar export happens in your browser: Google Calendar and Outlook links open in a new tab, and .ics files are created locally and downloaded.

## Payments

NanoEvent is free. It has no subscriptions, trials or payment processing.

## Your choices

- Nothing is sent unless you run an extraction.
- You can remove the extension or its permissions at any time in Chrome's extension settings.

## Changes

If this policy changes, the "Last Updated" date above will change too.

## Contact

Questions or requests: https://github.com/wihoho/privacy/issues
