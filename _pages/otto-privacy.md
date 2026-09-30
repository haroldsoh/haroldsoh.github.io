---
layout: otto
title: Privacy policy
description: How Otto accesses, uses, stores and shares email data, including optional AI features and local storage controls.
permalink: /otto/privacy/
---

Otto is a personal macOS email client developed and operated by Harold Soh for his own use. It is not a public email hosting service. This policy describes the current personal build of Otto and these information pages.

## Information Otto accesses

When you connect an account, Otto accesses its email address, message headers, recipients, subjects, labels, message bodies and attachments to provide email features. It requests Gmail’s `gmail.modify` permission to read, search, send and organize mail. If you separately enable Gmail vacation replies, it requests `gmail.settings.basic` to read and update those settings. Microsoft 365 connections use delegated account and mail permissions for the same email functions.

Otto signs in through Google or Microsoft. Their access and refresh tokens authorize the connection; Otto does not collect your Google or Microsoft password.

With your separate macOS permission, Otto can read Mac Contacts to suggest recipients and calendar events to help you check availability. Its calendar view does not create or change events. An optional Apple Mail sending connection passes the outgoing message and attachments to Apple Mail on your Mac, which handles delivery using its configured account.

## How data is used

Email data is used to display and search mail, compose and send messages, manage read status and folders, handle attachments, and provide drafts, snooze and follow-up reminders. Optional AI assistance is described below. Otto does not sell email data, use it for advertising, or build advertising profiles. Otto has no implemented analytics or telemetry service.

Otto’s use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements. Google user data is not used by Otto to train general-purpose AI models.

## Storage and retention

Account tokens and the configured AI API key are stored in macOS Keychain. Recent mail, downloaded bodies, local drafts, templates, signatures, reminder state and downloaded images are stored on your Mac. Mail caches are bounded; Otto does not automatically download an entire mailbox. Data is retained while needed for these features or until you clear it. Your mail provider independently retains your server mailbox.

The app’s mail and draft files are not encrypted by Otto itself. macOS account permissions restrict access, and FileVault can protect the Mac’s disk. Backups and files you save or export may retain separate copies. Apple Mail attachment handoff copies can also remain locally so Mail can finish delivery.

## When data leaves your Mac

- **Mail services:** Otto communicates directly with the account’s Google or Microsoft service to synchronize mail and carry out requested actions. Sending a message shares it and its attachments with the selected recipients through the sending provider. The Apple Mail option delegates this to that local application.
- **Optional AI:** Nothing is sent to an AI endpoint until you invoke an AI feature. The request can include your question, relevant email or draft context, recent chat history, and files you select. Selected documents may be sent as extracted text or as their original supported format. Requests go to the endpoint configured in Otto, which can be an external provider or a local model. External providers have their own processing and retention terms; choose a configuration compatible with Google’s Limited Use requirements and your obligations to correspondents. Do not enable provider training on Google email data.
- **Optional Codex handoff:** Choosing Open in Codex transfers a prepared question and selected context/files to your local Codex app for review. Submitting it there uses Codex’s configured service and data controls.
- **Remote content and links:** Remote email images are blocked by default. If you allow them for a sender or globally, image servers receive network requests that may reveal your IP address and that the image was loaded. Opening an email link contacts the linked website in your browser.

There is no Otto-operated server that receives or stores your mailbox. Google, Microsoft, an AI service you choose, and other destinations you deliberately contact have their own privacy policies.

## Your controls and deletion

You can stop using optional AI, Mac Contacts or Calendar features and change remote-image preferences. macOS permissions can be revoked in System Settings.

Use Otto’s account removal control to remove that account’s saved mail connection, cached messages and local drafts from Otto. This does not delete your mailbox at Google or Microsoft. You can also revoke Otto’s authorization in the provider’s account security settings. Clearing Otto’s downloaded-mail cache removes cached messages, while preserving accounts and local drafts.

For full local removal, quit Otto and remove its app data and related credentials from your Mac. Current production app data uses the legacy folder `~/Library/Application Support/Aster/`; Apple Mail handoff files, downloaded/exported attachments, backups and any copies in other apps should be considered separately. Contact Harold if you need help locating these copies. Revoking access alone does not erase previously saved files or data already sent to another service.

## This website and contact

These Otto pages have no forms, added tracking scripts or advertising cookies. The website hosting provider may process ordinary web request logs, such as IP addresses, under its own policies. These pages do not receive your mailbox data.

For questions about Otto or this policy, [contact Harold Soh](https://haroldsoh.com/contact/). The date above records the latest revision; this policy will be updated when Otto’s data practices change.
