# RS Mailbox CLI — Privacy Policy

Effective 23 November 2026

RS Mailbox CLI is a personal, single-user command-line application used only by
its owner. It is not distributed.

## Data accessed

With the owner's OAuth consent, it accesses the owner's own Google Account:
basic profile information (email address, display name) and Gmail data
(messages, threads, and labels), using the `gmail.modify` scope. That scope
allows reading, composing, sending, and modifying email, but not permanent
deletion that bypasses the trash.

## Use

Data is used only to display, search, read, organize, and — when the owner asks
— compose or send email from the command line on the owner's computer. There is
no advertising, analytics, profiling, or other use.

## Storage and sharing

OAuth credentials are stored locally on the owner's computer, encrypted with
AES-256-GCM and a key held in the macOS Keychain. Email content is not stored on
any server and is not sold, shared, or transferred to any third party. The
application communicates only with Google APIs.

Use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Revocation

Revoke access at https://myaccount.google.com/permissions. Remove local
credentials with `gws auth logout`.

## Contact

Personal application; contact the owner at https://github.com/rsacramento.
