# Privacy Policy for VocabCurve

**Last Updated**: July 26, 2026

## Overview

VocabCurve ("we", "our", or "the app") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and protect information when you use our mobile application. VocabCurve is a privacy-first English vocabulary learning tool designed around spaced repetition memory curves (SRS), flashcard reviews, and on-device word search.

## Information We Collect & Process

### Data Stored Locally on Your Device
- **Vocabulary Lists & Flashcards**: Words, definitions, custom notes, and review history are stored locally on your device in a local SQLite database (`sqflite`).
- **On-Device Text Recognition (OCR)**: If you use the camera or image scan feature to extract vocabulary, optical character recognition is performed on-device using Google ML Kit. Images are processed locally and are never transmitted to external servers.
- **Application Preferences**: Your study settings, daily goals, and notification preferences are saved locally on your device (`shared_preferences`).

### Information We Do NOT Collect
- We do not require account registration or user sign-in.
- We do not collect or store personal identification information (such as your name, email, address, or phone number).
- We do not track your location or device identifiers.
- We do not sell, rent, or trade any user data to third parties.
- We do not host your study history on external servers.

## Permissions Usage

- **Camera / Storage / Photos**: Used solely when you choose to scan printed text or images to import vocabulary words locally via OCR.
- **Notifications**: Used to schedule local reminders on your device for scheduled vocabulary reviews (`flutter_local_notifications`).

## Advertising & Third-Party Services

- **No Ads**: VocabCurve does not contain any third-party advertisements or ad tracking frameworks.
- **No Analytics / Tracking**: We do not use third-party tracking or behavioral analytics tools.

## Data Security

- All application data stays on your local device.
- We implement industry-standard practices to ensure local database safety.

## Children's Privacy

VocabCurve does not knowingly collect any personal information from children. Because the application processes data entirely locally on the user's device and collects no personal data, it is safe for users of all ages.

## Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Any changes will be posted on this page with an updated "Last Updated" date.

## Contact Us

If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us:
- **Email**: wihoho@gmail.com
- **Repository**: https://github.com/wihoho/privacy
