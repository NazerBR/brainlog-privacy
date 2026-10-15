---
title: BrainLog privacy policy
---

# BrainLog privacy policy

Last updated: 15 October 2026

BrainLog is a personal application used only by its owner. It has no other users.

**Data accessed.** With the owner's consent, BrainLog reads the owner's Gmail
(`gmail.readonly`) and Google Calendar events (`calendar.events.readonly`):

- it regularly copies recent email and calendar events to the owner's server;
- when the owner asks a question or asks for an email, or a new email matches a search the
  owner saved, it searches the owner's Gmail and reads the matching emails, including their PDF
  and image attachments.

If the owner also grants the optional `gmail.compose` and `calendar.events` permissions,
BrainLog can write to the owner's Google account:

- when it prepares an email, it first saves it as a draft in the owner's Gmail, then shows it
  to the owner. It sends the draft only when the owner taps Send. Cancel deletes the draft,
  unless the owner has changed it in Gmail;
- it adds an event to the owner's calendar only when the owner taps Confirm.

It does not change or delete any other email or calendar event.

**Use.** This data is used only to help the owner with their own tasks, questions, reminders
and email. It is not sold, not used for advertising, and BrainLog does not use it to train AI
models.

**Sharing.** BrainLog shares Google user data only with these services, to do this work:

- **AI model providers.** The text a piece of work needs, such as the owner's notes and tasks
  and the relevant email, calendar and attachment content, is sent through their APIs to the
  provider the owner chose for that work: Anthropic (Claude) or OpenAI. Photos and scanned
  documents are sent only to Anthropic.
- **Telegram.** BrainLog talks to the owner in the owner's private Telegram chat with it. Its
  messages can include email and calendar details, such as a draft email for the owner to
  check or the day's events, and Telegram keeps the chat.
- **Hosting.** The owner's server is rented from DigitalOcean, which stores BrainLog's data and
  backups.

No other third party receives Google user data.

**Storage and retention.** Data is stored on the owner's private server.

- BrainLog's saved copies of synced emails and calendar events are deleted when they are no
  longer current and were saved more than 30 days earlier, and its copies of emails and
  attachments read to answer a question 30 days after they were last read. A copy is kept
  while a task, question or review cites it.
- Files the owner sends in Telegram are deleted after 30 days.
- These have no time limit: notes, tasks, questions and reviews; the emails and events
  BrainLog offered; its messages with the owner; and the assistant's working history, which
  includes text from the emails, events and attachments it read.
- An audit history records each change. After 30 days, any part of a record over 2 KB is
  replaced by its size and a fingerprint; shorter text, such as a short email, can remain.
- Daily backups on the server are kept for 7 days. DigitalOcean's server backups are kept
  on its own schedule.

**Google API Services.** BrainLog's use and transfer of information received from Google APIs
adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

**Removal.** Access can be revoked at any time at
[myaccount.google.com/permissions](https://myaccount.google.com/permissions).
The owner can delete stored data from the server.

**Contact.** Open an issue at
[github.com/NazerBR/brainlog-privacy/issues](https://github.com/NazerBR/brainlog-privacy/issues).

[Home](./)
