# Privacy Policy for Daily Reflect

**Last Updated**: November 19, 2026

## Overview

Daily Reflect ("we", "our", or "the app") is a journaling app. You capture thoughts during the day by typing or speaking, and the app uses AI to turn them into a diary entry and a short reflection. This Privacy Policy explains what information the app handles, where it goes, and how you control it.

## Information We Collect & Process

### Data Stored Locally on Your Device
- **Thoughts and Diary Entries**: Text you type, the voice notes you record (audio files), and the diary entries, reflections and voice-note transcripts generated from them are stored on your device (a local Isar database and the app's private folder).
- **Application Preferences**: Settings such as theme and markdown export folder are saved locally on your device (`shared_preferences`).

### Data Sent Off Your Device
- **AI Diary Generation**: Only when a diary entry is written (you tap Create entry or Update entry, or the app writes a past day's entry when you open it), that day's thoughts are sent over HTTPS to an AI service operated by us: the text of typed thoughts, and the audio of voice notes that have not been transcribed yet. That service runs behind a zrok tunnel (zrok.io, operated by NetFoundry) and passes the request to Google's Gemini models, which write the entry, the reflection and a transcript of each voice note. The text and audio are used only to produce your entry. We do not sell them, use them for advertising, or keep them after the request completes. Google processes these requests under the [Gemini API Additional Terms of Service](https://ai.google.dev/gemini-api/terms).
- **Install ID**: Each AI request carries a random ID that the app creates on first use. It is not linked to your name, account or device identifiers, and is used only to apply a fair daily limit of AI requests per installation. If the AI service can't be reached, or the daily limit is used up, the entry is saved on your device in your own words and nothing is sent; voice notes then wait on your device until the next time the entry is written.
- **Voice Notes**: With your permission, the app uses the microphone only while you record a voice note. The recording stays on your device for playback until you delete the thought; its audio leaves the device only as described under AI Diary Generation.
- **Reports of AI-Generated Content**: If you report an AI-generated entry, we receive your selected reason, any details you add, and up to 500 characters of the entry and reflection, sent through Formspree (formspree.io), so we can review the report and improve content quality. If a report can't be sent (for example, while offline), it is kept on your device and sent later.

### Data You Choose to Export or Share
- **Markdown Export**: If you enable export, entries are written to a folder you choose on your device. What happens to them afterwards (for example, if that folder syncs to a cloud service) is under your control.
- **Sharing**: If you tap Share on an entry, its text goes to the app you pick through Android's share sheet.

## What We Don't Do
- No user accounts or sign-in.
- No advertising, and no analytics or tracking SDKs.
- No sale of personal data.

## Data Security
All network communication from the app uses HTTPS.

## Data Retention & Deletion
- You can edit or delete individual thoughts in the app.
- Uninstalling the app deletes all data stored on your device.
- Text sent for AI generation is not retained after the request completes.
- To ask us to delete a content report you submitted, contact us at the address below.

## Children's Privacy
Daily Reflect is not directed at children under 13, and we do not knowingly collect personal information from children.

## Changes to This Policy
We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated "Last Updated" date.

## Contact Us
If you have questions about this Privacy Policy, contact us at: **wihoho@gmail.com**
