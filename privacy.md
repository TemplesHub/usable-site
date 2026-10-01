---
title: Privacy policy
permalink: /privacy/
---
# Haven privacy policy

*Alpha, last updated 2026-10-01. This page says what the app does today. It changes when the app does.*

## The short version

Your notes, plans and calendar live on your phone. Our server holds only what it needs to evaluate or relay a message between you and the people you connect with, and nothing else. We do not sell data, run ads, or use analytics.

## What stays on your phone

Everything you write: notes, to-dos, commitments, day plans, and their history. Your Google Calendar sign-in tokens and the events from a linked Google calendar, when you link one. Your local settings, chimes and reminders. Deleting the app deletes all of it.

## What our server holds

- **Your account:** the display name and phone number you register with, and a hashed device credential so your phone can prove it is yours. We never see or store a password.
- **Contact matching:** hashed forms of the contact details you choose to share for finding people you know. We do not store your address book and we do not build a graph of who knows whom.
- **Messages in transit:** a shared note or an invitation waits on the server until the other person's phone collects it, then it is gone.
- **A wake signal:** a push token so we can tell your phone to check for new messages. The push itself carries no content.
- **Feedback you send:** the text and any screenshot you attach through Send Feedback, kept by the team to fix what you reported.

## Google Calendar

If you link a Google calendar, Haven asks Google for two permissions:

- **See the list of your calendars**, so you can pick the one to link.
- **See and edit events on your calendars**, so that one linked calendar and your commitments
  in Haven stay the same. Haven reads and writes events only on the calendar you picked.

What Haven does with it:

- **It stays on your phone.** Events from the linked calendar, and the Google sign-in tokens,
  are kept on your phone and nowhere else. The sync runs on your phone.
- **Your phone does the syncing.** When you open Haven, and while it is in front, your phone
  asks Google for what changed since last time (using Google's sync token). Edits you make in
  Haven are written back to the same calendar.
- **Our server never sees calendar data.** No event, title, time or guest ever reaches it, unless you include it in feedback you choose to send.
- **Sharing is your act.** An event reaches another Haven user only when you send it or
  change your own meeting that they are on, the same way a note you write reaches them. Haven
  never sends your guest lists anywhere.
- **No ads, no selling, no model training.** Haven does not sell Google data, use it for
  advertising, or use it to develop, improve or train AI or machine-learning models.
- **No people read it.** The team never sees your calendar data, unless you include it in feedback you choose to send.

Stopping and deleting:

- **Unlink** on the Calendar sync screen stops all access at once: the pulls and writes stop and
  the stored Google sign-in token is removed from your phone. You choose whether the
  synced commitments stay in Haven or are removed from your phone. Nothing in your Google
  calendar is changed by unlinking.
- You can also remove Haven's access from your Google Account at
  https://myaccount.google.com/permissions.
- Deleting the app deletes everything it kept from Google.

Haven's use and transfer of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements. The use of information received from Google Workspace
scopes will adhere to the Google User Data Policy, including the Limited Use requirements.

Questions: [hello@havencoordination.com](mailto:hello@havencoordination.com)

## How we protect your data

This covers everything Haven holds, including the data it receives from Google when you link a calendar.

- **Encrypted in transit.** Every connection Haven makes, to Google and to our own server, uses TLS (HTTPS). Calendar data travels only between your phone and Google.
- **Sign-in tokens in the iOS Keychain.** Your Google sign-in tokens and the record of your linked calendar are stored in the iOS Keychain, which is encrypted by the device and readable only by Haven.
- **Encrypted at rest on your phone.** Events from a linked calendar are stored in Haven's private app storage. iOS keeps that storage separate from every other app and encrypts it when your phone has a passcode.
- **Not on our servers.** Google user data is never copied to our server, so there is no server-side copy to protect, breach or hand over.
- **The least access that works.** Haven asks Google only for the calendar list (read-only) and for events, and reads and writes events only on the one calendar you linked.
- **Limited team access.** The server records listed above are reachable only by the small team that runs the service, over encrypted connections. Device credentials are stored hashed.
- **Deleted when you say.** Unlinking removes the Google sign-in token from your phone; deleting the app removes everything it stored; on request we delete your account and its server records.
- **If something goes wrong.** If we learn of a security incident affecting your data, we will tell affected users promptly at the contact details they registered.

## Who can see what

The people you connect with see what you choose to share with them at the closeness you set. We, the team, can see the server records described above and the feedback you send. Nobody else.

## Keeping it and deleting it

Server records stay while your account exists. Ask us and we delete your account and everything the server holds about you. Messages in transit are deleted on delivery.

## Children

Haven is not directed at children under 13.

## Contact

[hello@havencoordination.com](mailto:hello@havencoordination.com)
