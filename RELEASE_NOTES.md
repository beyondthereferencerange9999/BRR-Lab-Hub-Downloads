# Release notes

## v1.5.0-preview.1

New Manager Desk, decision scheduling, weekly workload/capacity planning,
structured small pilot tests, outcome/process/balancing measurements, observed
trend charts, attributed corrections, current outcome reviews, and lab-local
Improvement Templates. Copies of templates start as fresh proposal drafts with
unchecked implementation steps and fresh approvals, baselines, and results.

Existing implementation checkboxes, rollout gates, approvals, permissions,
tasks/projects, recurrence, process acknowledgments, and 30/60/90-day reviews
are retained. Structured measures add a current outcome-review closure gate.
Partial or unmet benefit can be recorded with reasoning; insufficient evidence
keeps the gate pending. New evidence invalidates the prior evidence review;
completed items keep their original closure and flag later evidence for review.

Existing v1.4 records get a pre-upgrade database snapshot before migration to
schema 3. New workflow records participate in full backup/restore checks.
Reinstall and removal retain the separate local records folder. Obtain a
verified full external backup before upgrading. Downgrade requires restoration
of a verified compatible v1.4 backup on an isolated host.

Native installers: Windows x64, Ubuntu 24.04 x64, and macOS 15 Apple silicon and
Intel previews. All are unsigned. Mac previews are unnotarized and require a
lab-approved distribution method; normal Gatekeeper acceptance is not verified.
Mac/Linux automatic startup requires local IT configuration. Staff continue to
use the installable web app from the lab's trusted HTTPS address on supported
phones, tablets, and computers.

Validation: 98 Python tests and 10 JavaScript checks per native build; installed
native UI/runtime/install/reinstall/uninstall with retained records; 21 Windows
and 17 browser checks per Mac/Ubuntu target. Windows checked trusted test HTTPS,
Edge workflows, and Chrome standalone installation/launch/removal. Mac/Ubuntu
used Playwright Chromium and loopback connections. Original reports, screenshots,
runtime notices, and checksums are in the full package. Actual lab networks,
physical phones, OS reboot, and external backup routes remain local gates.

Source stays private. Free independent use and unmodified installer sharing
remain permitted with use terms and third-party notices retained. The previous
v1.4 release remains available for its verified compatible installations.
