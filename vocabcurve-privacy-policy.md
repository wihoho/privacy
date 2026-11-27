# Privacy Policy for VocabCurve

**Last Updated**: November 27, 2026

This is a copy of the policy at https://wihoho.github.io/privacy/vocabcurve/.

This policy covers the **VocabCurve** Android app (package com.wihoho.vocabcurve), a vocabulary builder for English, Spanish, French, German, Italian, Portuguese, Japanese, Korean and Chinese: you save words from what you read, with the sentence you found them in, look them up in an offline dictionary and review them with spaced repetition. In short: your words are stored on your phone. They leave the phone only when you **sign in with Google** or turn on **sync with a code** (to keep your phones in step), or when you press **Explain** (to get an AI explanation of one word in its sentence). VocabCurve has no ads, no analytics, no tracking, no in-app purchases, and we never sell or share data.

## Information the app handles

- The words you save, the sentence you saved each one with, your notes, tags and review history (spaced-repetition state: when each word is due, how well you knew it).
- Explanations you asked for, kept so you don't need to ask again.
- Your settings, such as "My language" and the reminder time.
- Photos you choose to read words from are processed on the phone (text recognition runs on the device) and are not kept or sent anywhere.

All of this is stored on the phone, in the app's private storage. Dictionaries work offline; looking up a word never sends it anywhere.

## Dictionary downloads

The English dictionary is built in. When you add another language, the app downloads that language's dictionary file once from GitHub (github.com, the public wihoho/vocabcurve-data repository). The request contains only which file is wanted; GitHub sees your IP address, as with any download, under [GitHub's privacy statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## Sync between phones (optional, off until you turn it on)

When you sign in with Google or turn on sync in Settings, VocabCurve sends your saved words, their sentences, notes, review history and cached explanations over HTTPS to our sync server, PlainAPI, which runs on the developer's own computer. The server stores them under a private sync space so that your other phones can show the same words, together with the time each record changed. Words you delete are removed from the server too (a short deletion marker is kept so other phones delete them as well).

If you use sync with a code instead of Google, anyone who has the code can read and change your words, so keep it to your own phones. Sync never blocks the app: when the server can't be reached, everything keeps working on the phone and catches up later. Signing out keeps your words on the phone.

## Google sign-in (optional)

VocabCurve asks Google only for the basic sign-in permissions (your name, email address and account id). The sign-in token is sent to our sync server, which checks it with Google and stores your Google account id and email address next to your sync space, so the same account finds the same words on another phone. It is never used for anything else and never shared.

## AI explanations (only when you press Explain)

When you press **Explain** on a word, the app sends that word, the sentence you saved it with and the language you want the answer in to our AI gateway, which runs on the developer's computer and passes the request to Google's Gemini model to write the explanation. A random install id (not linked to you) is sent to apply a daily limit of 20 explanations per phone. Nothing else is sent, and nothing is sent unless you press the button.

## 14-day server log

Our AI gateway and our sync server (PlainAPI) run on the developer's own computer. For every request the app sends to either of them, the server keeps a log entry with the full request and the full answer for 14 days. For VocabCurve this includes the word, sentence and language sent when you press Explain and the explanation that comes back, and, with sync on, your synced records (words, sentences, notes, review history and cached explanations). Each entry also records the time, the app and its version or the AI model used, and the country and network part of your address (never the full IP address). It never keeps Google sign-in tokens, sync codes, API keys or passwords.

With sync on, your words stay on our server for sync as described above; the 14-day log is an extra copy that is deleted on its own after 14 days.

The log is kept only to find and fix problems and to improve the quality of results. After 14 days each entry is deleted automatically, and the log is not included in backups. Only the developer can see it, in a private dashboard behind the developer's Google sign-in. It is never sold, shared, used for advertising or used to train AI models. To have your log entries deleted sooner, ask us through the contact link below.

## Translations

Dictionary meanings (and, if you ask, your saved sentences) are translated into your language on the phone with Google ML Kit. The first time you pick such a language, the app downloads that language's translation model (about 30 MB) from Google; after that, translation works offline and your text stays on the phone.

## Permissions

Internet (for the optional sync, Google sign-in, AI explanations, dictionary downloads and the one-time translation model download) and notifications (for the optional daily review reminder). Photos are taken or picked through the phone's own camera and photo picker, so the app needs no camera or storage permission. No location, contacts or microphone permissions.

## Storage and deletion

Uninstalling the app removes its data from the phone. You can export all your words to CSV or JSON at any time. To delete your synced words from the server, delete them in the app while signed in, or contact us (below) and we will delete your space. Copies in the 14-day server log are deleted automatically after 14 days.

## What we don't do

- We don't sell or transfer data to third parties.
- We don't show ads or use advertising IDs.
- We don't use analytics or crash-reporting services.
- We don't use your words for anything other than showing them to you on your own phones, writing the explanations you ask for, and finding and fixing problems through the 14-day server log.

## Changes

If this policy changes, the updated version will be posted on this page with a new date.

## Contact

Questions or deletion requests:
- **Email**: wihoho@gmail.com
- **Issues**: https://github.com/wihoho/privacy/issues
