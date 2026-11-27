# Privacy Policy for Daily Reflect

**Last Updated**: November 27, 2026

## Overview

Daily Reflect ("we", "our", or "the app") is a journaling app. You capture thoughts during the day by typing or speaking, and the app uses AI to turn them into a diary entry and a short reflection. This Privacy Policy explains what information the app handles, where it goes, and how you control it.

## Information We Collect & Process

### Data Stored Locally on Your Device
- **Thoughts and Diary Entries**: Text you type, the voice notes you record (audio files), the photos you add (a resized copy; your originals are untouched), and the diary entries, reflections, transcripts and photo captions generated from them are stored on your device (a local Isar database and the app's private folder).
- **Application Preferences**: Settings such as theme and markdown export folder are saved locally on your device (`shared_preferences`).

### Data Sent Off Your Device
- **AI Diary Generation**: Only when a diary entry is written (you tap Create entry or Update entry, or the app writes a past day's entry when you open it), that day's thoughts are sent over HTTPS to an AI service operated by us: the text of typed thoughts, the audio of voice notes that have not been transcribed yet, and resized copies of photos that have not been captioned yet. That service runs behind a zrok tunnel (zrok.io, operated by NetFoundry) and passes the request to Google's Gemini models, which write the entry, the reflection, a transcript of each voice note and a caption for each photo. The text, audio and photos are used to produce your entry, and are kept for 14 days in our server log (see 14-day server log below) to find and fix problems and improve results. We do not sell them or use them for advertising. Google processes these requests under the [Gemini API Additional Terms of Service](https://ai.google.dev/gemini-api/terms).
- **Install ID**: Each AI request carries a random ID that the app creates on first use. It is not linked to your name, account or device identifiers, and is used only to apply a fair daily limit of AI requests per installation. If the AI service can't be reached, or the daily limit is used up, the entry is saved on your device in your own words and nothing is sent; voice notes then wait on your device until the next time the entry is written.
- **Voice Notes**: With your permission, the app uses the microphone only while you record a voice note. The recording stays on your device for playback until you delete the thought; its audio leaves the device only as described under AI Diary Generation.
- **Google Doc copy (optional)**: If you turn on "Keep a copy in Google Docs" and sign in with Google, the app keeps one Google Doc in your own Google Drive up to date with your finished entries, reflections and photos. The app asks only for Google's "drive.file" permission, which lets it see and change only the files it creates; it cannot read anything else in your Drive. This data goes directly from your device to your Google account under Google's terms; it does not pass through our servers and we never see it. To put a photo into the doc, the app uploads it to your Drive, makes its link viewable by anyone who has the link for the few seconds the doc needs to copy it, then deletes that uploaded file. You can turn the copy off at any time in Settings; the doc stays in your Drive until you delete it, and you can remove the app's access at myaccount.google.com/permissions.
- **Reports of AI-Generated Content**: If you report an AI-generated entry, we receive your selected reason, any details you add, and up to 500 characters of the entry and reflection, sent through Formspree (formspree.io), so we can review the report and improve content quality. If a report can't be sent (for example, while offline), it is kept on your device and sent later.

### Data You Choose to Export or Share
- **Markdown Export**: If you enable export, entries are written to a folder you choose on your device. What happens to them afterwards (for example, if that folder syncs to a cloud service) is under your control.
- **Sharing**: If you tap Share on an entry, its text goes to the app you pick through Android's share sheet.

## 14-day server log

Our AI service runs on the developer's own computer. For every request the app sends to it, the service keeps a log entry with the full request and the full answer for 14 days. For Daily Reflect this includes the text of your thoughts, the audio of your voice notes, the photo copies, and the diary entry, reflection, transcripts and captions that come back. Each entry also records the time, the app and its version or the AI model used, and the country and network part of your address (never the full IP address). It never keeps API keys or passwords.

The log is kept only to find and fix problems and to improve the quality of results. After 14 days each entry is deleted automatically, and the log is not included in backups. Only the developer can see it, in a private dashboard behind the developer's Google sign-in. It is never sold, shared, used for advertising or used to train AI models. To have your log entries deleted sooner, email us at **wihoho@gmail.com**.

## What We Don't Do
- No user accounts or sign-in.
- No advertising, and no analytics or tracking SDKs.
- No sale of personal data.

## Data Security
All network communication from the app uses HTTPS.

## Data Retention & Deletion
- You can edit or delete individual thoughts in the app.
- Uninstalling the app deletes all data stored on your device.
- What is sent for AI generation (text, voice note audio and photo copies) and the answer are kept in our server log for 14 days, then deleted automatically.
- To ask us to delete a content report you submitted, contact us at the address below.

## Children's Privacy
Daily Reflect is not directed at children under 13, and we do not knowingly collect personal information from children.

## Changes to This Policy
We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated "Last Updated" date.

## Contact Us
If you have questions about this Privacy Policy, contact us at: **wihoho@gmail.com**
