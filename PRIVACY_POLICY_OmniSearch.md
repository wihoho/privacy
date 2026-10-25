# OmniSearch Privacy Policy

**Last Updated: October 25, 2026**

## Overview

OmniSearch is a Chrome extension that lets you search websites straight from Chrome's address bar with short keywords (type `os`, a keyword and your search), and manage those shortcuts in a sidebar. This policy explains what OmniSearch does and does not do with your data.

## Data Collection

**We do not collect any personal data.** OmniSearch has no servers of its own and sends nothing to the developer.

### What We Don't Collect

- Personal information (name, email, address, etc.)
- Browsing history or the pages you visit
- The content of web pages
- Search queries or search terms
- Usage analytics, device identifiers or location
- Any form of tracking data

## Data Storage

OmniSearch stores the following in Chrome's built-in extension storage (`chrome.storage.sync`):

- **Your shortcuts**: the built-in and custom shortcuts, their keywords and search URLs, and whether each one is on or off
- **Advanced shortcut settings**: the page address, input box selector and button selector you enter for an advanced shortcut
- **Preferences**: for example whether you have seen the welcome page

If Chrome sync is turned on, Chrome syncs these settings across your own Chrome browsers. That is handled by Google Chrome and covered by Google's privacy policy. The developer has no access to it.

## How OmniSearch Works With Websites

### Searches

When you search with a shortcut, OmniSearch builds the search address (for example `https://www.youtube.com/results?search_query=cats`) and opens it in a new tab. What happens on that site is covered by that site's privacy policy. OmniSearch does not record or monitor your searches.

### Advanced shortcuts

For an advanced shortcut that you set up yourself, OmniSearch opens the page you chose, types your search into the input box you specified and clicks the button you specified. It does this only on that page and only when you run the shortcut. It does not read or send anything back from the page.

### The sidebar

The sidebar for managing your shortcuts can open on whatever page you are viewing (toolbar icon or `Ctrl+Shift+S` / `Cmd+Shift+S`). For that, OmniSearch's script is present on web pages, but it only shows the sidebar when you open it and does not read, collect or transmit page content.

### Website icons

The sidebar shows small website icons (favicons) loaded directly by your browser from the websites themselves or from Google's favicon service. These requests are not tracked by OmniSearch.

## Permissions Explanation

- **`storage`**: saves your shortcuts and preferences as described above.
- **`scripting`**: adds OmniSearch's own sidebar script to the current tab when you open the sidebar on a tab that was already open before OmniSearch was installed or updated.
- **Access to websites (`<all_urls>`)**: lets the sidebar open on any page you are viewing, and lets an advanced shortcut type your search into the site you set it up for. OmniSearch does not read, collect or transmit page content.
- **`omnibox` keyword `os`**: lets you search from the address bar.

## Data Security

- Your data stays in Chrome's own storage
- No data is sent to the developer or any third party
- No accounts, cookies, ads or tracking

## Children's Privacy

OmniSearch does not collect data from anyone, including children.

## Data Deletion

To delete all OmniSearch data, remove the extension at `chrome://extensions/`. Chrome deletes OmniSearch's stored shortcuts and settings when the extension is removed.

## Changes to This Policy

We may update this policy. Changes will be shown by the "Last Updated" date above.

## Contact

Questions about this policy or OmniSearch's data practices: open an issue at [https://github.com/wihoho/search-extension/issues](https://github.com/wihoho/search-extension/issues).

## Summary

**In simple terms**: OmniSearch keeps your shortcuts in your own Chrome, opens the searches you ask for, and does not collect, read or send your data.
