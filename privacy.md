# Sutr privacy policy

*Last updated 28 October 2026.*

Sutr is a notes app for Android made by Rohith G. This page says what the app
does with your information. In short: what you write stays on your phone, and
nothing about you is ever sent to the developer.

## What stays on your phone

Everything you write in Sutr (journal entries, tasks, projects, notes, quotes,
people's names) and its settings are stored in the app's private storage on
your phone. Other apps cannot read it. Sutr has no account, no server, no
analytics, no advertising and no crash reporting. The developer never receives
your entries, your settings or anything about how you use the app.

Uninstalling Sutr deletes everything it stored on the phone.

## Google Drive backups (only if you connect them)

If you choose to connect Google Drive in Settings → Backup, Sutr uses Google's
sign-in on your phone to get permission for two limited kinds of access:

- **`drive.file`**: only the files Sutr itself creates. Sutr makes a folder
  called *Sutr Backups* in your Drive and saves backup copies there. It cannot
  see any other file in your Drive.
- **`drive.appdata`**: a hidden folder in your Drive that only Sutr can use.
  Sutr keeps the password for your backups there, so a new phone can restore
  them after you connect the same Google account.

Each backup is a ZIP of your entries as Markdown text, encrypted with AES-256
under a password generated on your phone. Any standard tool, such as 7-Zip,
opens it with that password, which you can see in Settings. Anyone with full
access to your Google account could find the password too.

Sutr keeps your Google account's email address on the phone, to know which
account to back up to. The backups go directly from your phone to your Google
Drive; they never pass through any server of the developer's. Sutr does not
use Google data for anything except making, checking and restoring your own
backups, and never shares it with anyone.

You can stop at any time in Settings, delete the *Sutr Backups* folder in Drive,
and remove Sutr's access at
[myaccount.google.com/permissions](https://myaccount.google.com/permissions).

Sutr's use and transfer of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## The update check

Once a day, when you open the app, Sutr downloads one small file
(`latest.json`) from this GitHub repository to see whether a newer version
exists. The request carries no information about you or your entries. Like any
web request, it is seen by GitHub, which receives your IP address; see
[GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
You can turn the check off in Settings → Updates; everything else works the same
without it. Sutr never downloads or installs an update by itself: an update
opens in your browser, and you install it.

## Files you choose

Sutr reads a file only when you pick it (an import from another app, or a
backup to restore), and writes one only where you choose to save it (an export,
or the folder for automatic backups).

## Diagnostic reports

Settings → Diagnostics can build a text report about your phone model, Android
version, the app's settings, counts of entries and the errors the app recorded.
It never includes anything you wrote. It is built only when you ask, you see it
first, and it goes nowhere unless you share it yourself.

## Permissions

- **Notifications, alarms and starting after a restart**: for reminders and
  digests, which are made on the phone.
- **Biometrics**: for the optional app lock, handled by Android; Sutr never
  sees your fingerprint or face.
- **Internet**: for Google Drive backups and the update check, as above.

## Children

Sutr is not directed at children under 13 and collects no information from
anyone.

## Changes

If this policy changes, the new version is published on this page with a new
date above.

## Contact

Questions about this policy:
[open an issue](https://github.com/Rohith-G1024/Sutr-Releases/issues).
