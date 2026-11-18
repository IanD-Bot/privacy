# Classic Firewall Advanced Rulesets support

_Last updated: November 18, 2026_

Classic Firewall Advanced Rulesets is published by Deck-Of-Jacks.

## About this app

Classic Firewall Advanced Rulesets puts named rule groups on top of Windows Firewall, with a preview of every change, backups, and protection against locking yourself out over Remote Desktop.

## Requirements

Windows 10 version 2004 (build 19041) or later, 64-bit.

## Install and launch

Install the app from the Microsoft Store, then open it from the Start menu. You can also launch it from Classic Control if that app is installed.

When you run it as a standard user, the app is read-only. Applying a change, or turning triggers on, needs administrator approval through the usual Windows prompt.

## Settings and data

Your rule groups, firewall backups, a rollback log, and a crash log are saved on your PC, in the app's data folder and in Documents\Firewall Rulesets backups. Nothing is uploaded.

## Common questions

- **I only want to look at rules.** Run the app as a standard user. It stays read-only until you apply a change and approve the administrator prompt.
- **What happens before a change is applied?** You get a preview of the exact difference. Apply changes only the rules this app created. Over Remote Desktop, the app adds a safety allow rule for your session first, warns about any rule that would block the Remote Desktop port, and rolls the change back after 60 seconds unless you confirm the connection still works.
- **Restore over Remote Desktop.** Restore needs a two-checkbox confirmation and has no timed rollback, so a restored policy can lock you out of the session.
- **What do triggers do?** With triggers on, groups can switch by network profile, network name or Wi-Fi name, time of day, a running app, or until a date and time. Temporary groups turn off at the time you set, including while the app is closed.
- **Cleanup of stale or duplicate rules.** That tool can remove other rules, but only the ones you tick. It saves a backup first and uses the same 60-second rollback unless you confirm. Built-in Windows rules and this app's own group rules are left out.
- **Can I import connections from Classic Network Monitor?** Yes. Import reads only the file you choose, or the newest export in Documents\Classic Network Monitor when running as administrator.

## Reset and uninstall

You can back up and restore the whole firewall policy from the app. Uninstall the app from Settings > Apps to remove the app's data folder. Backups in Documents\Firewall Rulesets backups stay until you delete them.

## Report a problem

Open a public issue at https://github.com/IanD-Bot/support/issues/new?template=classic-firewall-advanced-rulesets.yml. Please don't include personal information in the issue.

## Privacy

See the [Classic Firewall Advanced Rulesets privacy policy](../classic-firewall-advanced-rulesets).
