---
title: Personal rclone Drive access
---

# Personal rclone Drive access

This personal configuration uses [rclone](https://rclone.org/) to transfer owner-selected files between Google Drive and four computers.
The computers are a Workstation, Server, Mac mini and Windows Laptop.
It serves one personal Google account. It is not a public sign-up service.

## Google Drive access

The owner approved permission to see, edit, create and delete Google Drive files.
This permission supports transfers that the owner selects. It does not instruct rclone to transfer every file.
The current setup test used one owner-selected 43-byte file.

Google Drive and the selected source and destination devices are the intended storage and transfer endpoints.
This configuration does not provide email, calendar, recording or messaging features.

## Owner control

The owner chooses transfer commands, source paths and destinations.
The owner can stop transfers, remove a configured connection or revoke access through [Google Account connections](https://myaccount.google.com/connections).
Revocation does not remove files already transferred. The owner manages those copies at their storage locations.

## Personal use and terms

This configuration is for its owner's use. This page does not offer a hosted transfer service to other people.
The rclone software has its own [license](https://rclone.org/licence/).
Google Drive use remains subject to Google's applicable terms and [OAuth policies](https://developers.google.com/identity/protocols/oauth2/policies).

Read the [privacy policy](privacy.html) for data use and owner controls.

Last updated: 17 November 2026.
