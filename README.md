# BRR Lab Management Hub Free Edition

**v1.4 public preview — free, independent copies for laboratories.**

BRR Lab Hub supports shared management work and process improvement. Each lab
runs its own Windows host with its own accounts, permissions, records, and
backups. Staff connect to that lab's trusted HTTPS address in a browser or an
installable browser app. The editable application source remains private.

## Install on Windows

[![Install on Windows](install-windows.svg)](https://github.com/beyondthereferencerange9999/BRR-Lab-Hub-Downloads/releases/download/v1.4.0-preview.1/BRR_Lab_Hub_Setup_1.4.0_Windows_x64.exe)

**Free public preview · Windows x64 · Python included**  
[Free-use terms](PUBLIC_USE_TERMS.txt) · [Third-party notices](THIRD_PARTY_NOTICES.txt)

1. Click **Install on Windows** to download the installer directly.
2. Have lab IT review the unsigned installer and its [SHA-256 checksum](https://github.com/beyondthereferencerange9999/BRR-Lab-Hub-Downloads/releases/download/v1.4.0-preview.1/INSTALLER_SHA256.sha256), then open it and follow the installation wizard.
3. Open **BRR Lab Hub** from the Windows Start menu.
4. Choose **Set up or open this lab's host**, then **Start my lab's host**.
   The guided first-time setup creates this lab's name and Lab Manager account.

**First lab setup:** configure trusted HTTPS for team access and complete the
five deployment checks before routine use. The host window stays open while
staff use the app. The optional **Start this lab host when I sign in to Windows**
setting opens it after the designated Windows user signs in.

Staff use this lab's address on their phones, tablets, or computers and install
the browser app where supported. They connect to the lab's central host.

[Setup guide](https://github.com/beyondthereferencerange9999/BRR-Lab-Hub-Downloads/releases/download/v1.4.0-preview.1/START_HERE.html) · [Complete package with guides and validation reports](https://github.com/beyondthereferencerange9999/BRR-Lab-Hub-Downloads/releases/download/v1.4.0-preview.1/BRR_Lab_Hub_Windows_Installer_v1.4_Public_Preview.zip)

Keep a copy of [PUBLIC_USE_TERMS.txt](PUBLIC_USE_TERMS.txt) with any installer
you redistribute; the installer includes the third-party notices and runtime licenses.

There is no program fee, required software subscription, per-member service,
paid database, or BRR account. Each lab supplies and maintains its own host,
network, certificate trust, staff devices, and backup storage. Separate hardware,
hosting, or commercial support may cost money.

## What the program provides

- Shared proposals with implementation checkboxes attributed to the member and time.
- A rollout gate until the planned implementation steps are complete; revisions retain history.
- Tasks, projects, recurring work, approvals, process acknowledgments, and effectiveness reviews.
- Role-based access, attributed history, conflict detection, and a program inbox.
- Manager-only host health, full backup and isolated recovery checks, and interrupted-restore recovery.
- Browser app installation, explicit updates that preserve unsaved forms, and offline privacy protections.
- Optional host startup after the designated Windows user signs in; the host window stays open.

## Validation and deployment

The unchanged installer passed **85 Python tests, 10 local JavaScript event checks,
and 17 actual browser checks**, plus packaged and installed runtime, native host,
installation, reinstallation, uninstallation, and isolated backup/restore checks.
Testing used synthetic records on an isolated Windows Server 2025 build machine.
Edge browser workflow was checked; standalone browser app installation, launch,
and removal were checked in Chrome. Edge app installation requires a target-device check.

This is a **public preview**. Actual lab networks and an operating-system reboot
on the intended host have not been validated by BRR. Each lab must record:

1. IT acceptance and installation of the unsigned installer on its Windows host.
2. Trusted HTTPS sign-in and correct permissions from a second staff device.
3. Installation or approved browser use and reviewed updates on intended devices.
4. Actual Windows restart, sign-in, staff reconnection, and scheduled work.
5. Retrieval of a full backup from the intended separate restricted destination
   and restoration on an isolated spare host or test records folder.

The ZIP includes the full setup guide, checkable deployment record, consolidated
validation results, original reports and images, checksums, and runtime notices.

## Shared OneDrive or Google Drive

A shared cloud folder can hold installers, guides, and the exported team launcher.
Uploading the package does not run the app. One designated Windows computer runs
the lab's host. Keep the live records and TLS private key on its local disk outside
cloud synchronization. Store completed full backups in a separate restricted
folder for authorized managers and host administrators; test retrieval and restore.
Members use individual Lab Hub accounts for attributed work.

## Free-use terms and feedback

[PUBLIC_USE_TERMS.txt](PUBLIC_USE_TERMS.txt) permits free installation, use, and
sharing of the unmodified installer with terms and third-party notices retained.
It does not grant an open-source license. Runtime components retain their
original licenses; see [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

For ordinary bugs or suggestions, use this repository's **Issues** tab. Include
the app version, Windows/browser versions, reproducible steps using synthetic
work, and the expected and observed result. Do not attach lab records, full
backups, credentials, private keys, or screenshots containing sensitive details.
For a security concern, request a private reporting route without posting the
vulnerability details or sensitive data publicly.

The app supports management and process improvement. It does not replace the
lab's official procedures, document control, or training system. Enter no patient
or other sensitive personal information. It is provided as-is under the included terms.
