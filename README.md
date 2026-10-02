# BRR Lab Management Hub Free Edition

**v1.5 public preview · free independent copies for laboratories**

Manage improvement ideas, implementation, results, tasks, and projects in one
shared program. Each lab runs its own host with its own accounts, permissions,
records, templates, and backups. Staff connect to that lab's trusted HTTPS
address on phones, tablets, or computers. The editable application source stays
private; this public repository contains download guides and notices.

## Install your lab's host

[![Install on Windows](install-windows.svg)](https://github.com/beyondthereferencerange9999/BRR-Lab-Hub-Downloads/releases/download/v1.5.0-preview.1/BRR_Lab_Hub_Setup_1.5.0_Windows_x64.exe)

Windows x64 · installation wizard · Python included

[![Install on Ubuntu](install-ubuntu.svg)](https://github.com/beyondthereferencerange9999/BRR-Lab-Hub-Downloads/releases/download/v1.5.0-preview.1/BRR_Lab_Hub_1.5.0_Ubuntu_24.04_x64.deb)

Ubuntu 24.04 x64 · native package · Python included

[![Download Mac Apple silicon](install-mac-arm.svg)](https://github.com/beyondthereferencerange9999/BRR-Lab-Hub-Downloads/releases/download/v1.5.0-preview.1/BRR_Lab_Hub_1.5.0_Mac_arm64.dmg)

[![Download Mac Intel](install-mac-intel.svg)](https://github.com/beyondthereferencerange9999/BRR-Lab-Hub-Downloads/releases/download/v1.5.0-preview.1/BRR_Lab_Hub_1.5.0_Mac_x86_64.dmg)

Mac builds tested on macOS 15. **Unsigned, unnotarized IT previews:** use a
lab-approved distribution method. Normal Gatekeeper acceptance is not verified.
The downloaded disk image contains the app and an Applications shortcut.

All four installers are unsigned. Have lab IT review the appropriate installer
and its [SHA-256 checksum](https://github.com/beyondthereferencerange9999/BRR-Lab-Hub-Downloads/releases/download/v1.5.0-preview.1/INSTALLER_SHA256.sha256).
Windows testing used Windows Server 2025; acceptance on the intended workstation
is a local deployment check. Ubuntu versions other than 24.04 and other Linux
distributions have not been validated.

[Setup and upgrade guide](https://github.com/beyondthereferencerange9999/BRR-Lab-Hub-Downloads/releases/download/v1.5.0-preview.1/START_HERE.html) · [Release and validation downloads](https://github.com/beyondthereferencerange9999/BRR-Lab-Hub-Downloads/releases/tag/v1.5.0-preview.1) · [Free-use terms](PUBLIC_USE_TERMS.txt) · [Third-party notices](THIRD_PARTY_NOTICES.txt)

Open **BRR Lab Hub** from the Start menu or Applications. Choose **Set up or open
this lab's host**, then **Start my lab's host**. The guided first-time setup
creates this lab's name and first Lab Manager account; no preset passwords or
remote BRR administrator account are included. Configure trusted HTTPS and
complete the five deployment checks before routine use. Keep the host running.

## Install the staff app on a phone or computer

Staff use the lab's own HTTPS address, then **Install Lab Hub**, **Install app**,
or **Add to Home Screen** where their browser supports it. On iPhone/iPad, open
the address in Safari and use **Share → Add to Home Screen**. On a supported Mac,
Safari offers **File → Add to Dock**. Use the browser directly when installation
is unavailable or blocked by lab policy. Each member has an individual account.

Phone users connect to the shared host; the phone does not run the lab's host.
The offline screen asks the member to reconnect and retains no private records.
Physical phone installation remains a target-device deployment check.

## What's new in v1.5

- **Manager Desk:** a decision queue with reasons, owners, blockers, department
  filters, and personal review scheduling. Existing deadlines and reminders continue.
- **Weekly workload planning:** estimated project hours, available hours, active
  work limits, and overload warnings. Unknown capacity stays distinct from zero.
- **Small pilot tests:** record the question, prediction, limited scope,
  observations, learning, and management's adapt/adopt/stop decision.
- **Outcome evidence:** outcome, process, and balancing measures; dated baseline
  and later readings; percentage denominators; observed trends; attributed corrections.
- **Honest completion:** structured measures require a current management outcome
  review before closure. Insufficient evidence keeps that requirement pending;
  partial and unmet benefit can be recorded with the learning.
- **Improvement Templates:** save lessons and implementation steps from completed
  improvements inside the lab. Each copy is a fresh draft with unchecked steps,
  fresh approval, and new local baselines and results.
- **Safer upgrades:** a pre-upgrade database snapshot for existing v1.4 records,
  retained history, and backup/recovery support for the new workflow records.
- **Mac and Ubuntu host packages**, alongside the Windows installer and staff web app.

Implementation checkboxes still record the completing member and time, retain
revision history, and prevent rollout until planned steps are complete. Tasks,
projects, recurring work, approvals, acknowledgments, 30/60/90-day reviews,
protected attachments, account permissions, conflict detection, and host health
and recovery tools remain available. Pilot decisions do not bypass approval or rollout.

## Validation and local deployment

The release includes original platform reports and synthetic browser screenshots.
Native builds run **98 Python tests and 10 JavaScript checks**. Installed-host
checks cover the native window, frozen runtime, reinstall/uninstall with retained
records, browser workflows, mobile-width layouts, offline privacy, explicit
updates, host restart, and isolated backup/recovery. Windows browser workflows
use Edge; standalone browser app installation and launch use Chrome. Mac and
Ubuntu browser workflows use Playwright Chromium. The reports identify the
checks completed on each platform.

This is a **public preview**. Each lab completes and records:

1. IT acceptance and installation of the unsigned host package.
2. Trusted HTTPS sign-in and correct permissions from a second staff device.
3. Installation or approved browser use and reviewed updates on intended devices.
4. Actual OS restart, host availability, staff reconnection, and scheduled work.
5. Full-backup retrieval from the intended separate restricted destination and
   isolated restoration on a spare host or test records folder.

Windows has an optional **Start this lab host when I sign in to Windows** setting.
Mac/Linux automatic startup needs local IT configuration. Keep the host window
open; availability before sign-in needs a lab-administered host arrangement.

Before upgrading, stop the host and obtain a verified full external backup.
Reinstalling retains the separate records folder. v1.5 upgrades the database to
schema 3; returning to v1.4 requires restoration of a verified v1.4 backup on an
isolated compatible host. Do not open a schema-3 database with the older app.

## Shared OneDrive or Google Drive

A shared cloud folder can hold installers, guides, and the exported team launcher.
Uploading files does not run the app. One designated Windows, Mac, or supported
Ubuntu computer runs the host. Keep live records and the TLS private key on its
local disk outside cloud synchronization. Store completed full backups in a
separate restricted folder for authorized managers and host administrators.

## Free copies and feedback

There is no program fee, required software subscription, per-member charge,
paid database, or BRR account. Each lab supplies and maintains its host, network,
certificate trust, staff devices, and backup storage; separate hardware, hosting,
or commercial support may cost money.

[PUBLIC_USE_TERMS.txt](PUBLIC_USE_TERMS.txt) permits free installation, use, and
sharing of the unmodified installer with terms and third-party notices retained.
It does not grant an open-source license. Runtime components retain their
original license rights; notices are included inside each installer.

Report ordinary bugs or suggestions through this repository's **Issues** tab.
Include app/OS/browser versions and reproducible steps using synthetic work.
Do not post lab records, backups, credentials, private keys, or sensitive screenshots.
For a security concern, request a private reporting route without posting details.

The program supports management and process improvement. It does not replace
the lab's official procedures, document control, or training system. Enter no
patient or other sensitive personal information. It is provided as-is under
the included terms.
