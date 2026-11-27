# Privacy Policy - ChatGPT for Google Calendar

**Effective date**: 27 November 2026 (version 2.0)

> Since 29 October 2026 this extension's Chrome Web Store listing delivers **NanoEvent – AI Event Creator for Google Calendar**, which has its own policy: [NanoEvent privacy policy](https://github.com/wihoho/privacy/blob/main/nano-event-privacy-policy.md). This page describes the earlier ChatGPT for Google Calendar code (version 2.0, debug log without page addresses since 27 November 2026).

## What the extension does

ChatGPT for Google Calendar turns text you select on a web page into a calendar event. You select text, right-click and choose "Add to calendar". The extension sends the selected text to an AI service, which reads out the title, start and end time and location. You check and edit the event in a small window on the page, then choose Google Calendar, Outlook or an .ics file.

## What leaves your computer

### 1. The text you select, to our AI service

When you click "Add to calendar", the extension sends one request to our AI service at **aistudio.share.zrok.io**. The service runs on the developer's own computer and passes the request to **Google Gemini**. The request contains:

- the text you selected (if you right-click without a selection, the text is empty), and
- today's date, so that words like "tomorrow" can be worked out.

Nothing else from the page is sent: not the page's other text, its web address, your browsing history, your emails or your existing calendar events. The answer that comes back is the event's title, start, end and location.

If our AI service cannot answer, the extension sends the same request to **OpenRouter** (openrouter.ai) instead, which passes it to Google Gemini. That request is not kept in our 14-day log; OpenRouter's and Google's own privacy policies apply to it.

The extension uses its own built-in service key for these requests. It does not ask for, use or store an API key of yours, and it has no OpenAI or "own key" setting.

### 2. Subscription check, to ExtensionPay

The extension is a paid subscription with a free trial, handled by **ExtensionPay** (extensionpay.com), with payments processed by Stripe. ExtensionPay receives:

- a random ID that the extension creates on first use (it identifies this installation, not you), and whether the extension is a development copy;
- a request with that ID each time you click "Add to calendar", to check whether your trial or subscription is active;
- the email address you type on ExtensionPay's trial, payment or "Already paid? Log in" page, and your trial and payment status.

Card and payment details are entered on Stripe's checkout page; the extension and the developer never see them. The developer can see your email address and subscription status in ExtensionPay. ExtensionPay never receives the text you select or your events. ExtensionPay's and Stripe's privacy policies apply to what they receive.

### 3. The finished event, to the calendar you choose

- **Google Calendar**: the extension opens Google Calendar's own "new event" page in a new window, with the title, time, location and your selected text (as the description) filled in through the page's web address. Nothing is saved until you click Save in Google Calendar, in your own Google account.
- **Outlook**: the same, using Outlook on the web's "new event" page.
- **.ics file**: the event is saved as a file on your computer through Chrome's download dialog. Nothing is sent.

The extension does not sign in to your Google account and has no access to Google Calendar's data: it cannot read, change or delete your calendars or events. It requests no Google OAuth scopes.

## 14-day server log

Our AI service (aistudio.share.zrok.io) runs on the developer's own computer and passes requests to Google Gemini. For every request the extension sends to it, the service keeps a log entry with the full request and the full answer for 14 days: the text you selected, today's date, and the event details that came back. Each entry also records the time, the app and its version or the AI model used, and the country and network part of your address (never the full IP address). It never keeps API keys or passwords.

The log is kept only to find and fix problems and to improve the quality of results. After 14 days each entry is deleted automatically, and the log is not included in backups. Only the developer can see it, in a private dashboard behind the developer's Google sign-in. It is never sold, shared, used for advertising or used to train AI models. To have your requests deleted sooner, email tmosby137@gmail.com.

## What is stored in your browser

The extension keeps these in Chrome's extension storage (chrome.storage) on your computer. None of it is sent to the developer:

- **Debug log** (the latest 1,000 entries): what the extension did and any errors. It never records the web addresses of the pages you visit. It includes the first 100 characters of the text you selected (the whole text in some error entries, for example when no event was found), the event details, and your ExtensionPay email when you start a trial or pay. You can download or clear the log on the extension's options page (Debug panel), and it is removed when you uninstall the extension.
- **Settings and counters**: the theme, whether you have finished the welcome steps, how many events you have added (used to ask for a review now and then) and whether you dismissed that request.
- **ExtensionPay data**: the random installation ID and the last subscription status returned by ExtensionPay (including your email, if you gave one). The ExtensionPay library keeps these in chrome.storage.sync, so if Chrome sync is on, Chrome copies them to your other signed-in computers.

## Permissions

| Permission | Why it is needed |
|------------|------------------|
| contextMenus | Adds "Add to calendar" to the right-click menu |
| activeTab, scripting | Shows the review window on the page you are on |
| tabs | Checks that the current page can show the review window (Chrome's own pages cannot) |
| storage | Keeps the settings, debug log and subscription status listed above |
| windows | Opens Google Calendar or Outlook in a new window |
| notifications | Shows short success and error messages |
| downloads | Saves the .ics file when you choose that option |

Host permissions: **aistudio.share.zrok.io** (our AI service), **openrouter.ai** (fallback AI service) and **extensionpay.com** (trial and subscription). The extension's page script is loaded on all sites so that the review window can appear on whichever page you select text on. It does not read the page's content; the only page text the extension uses is the text you select and send.

## What we don't do

- We don't sell, rent or share your data, and we don't use it for advertising.
- We don't use analytics or tracking.
- Nothing is sent to the AI service until you click "Add to calendar".

## Your choices

- Choose exactly which text to send, and edit or cancel the event before anything is saved.
- Clear the debug log on the options page at any time. Uninstalling the extension removes what it stored in that browser.
- Ask for your 14-day log entries to be deleted sooner, or make any other privacy request, by email.

## Children

This extension is not directed at children under 13, and we do not knowingly collect information from children.

## Changes

If this policy changes, the updated version will be posted here with a new effective date.

## Contact

Questions or requests: email [tmosby137@gmail.com](mailto:tmosby137@gmail.com).
