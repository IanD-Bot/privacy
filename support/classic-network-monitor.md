# Classic Network Monitor support

_Last updated: November 18, 2026_

Classic Network Monitor is published by Deck-Of-Jacks.

## About this app

Classic Network Monitor shows every app and service on your PC with its open ports and network connections, in one live list. It is read-only: it never changes your firewall or your network settings.

## Requirements

Windows 10 version 2004 (build 19041) or later, 64-bit.

## Install and launch

Install the app from the Microsoft Store, then open it from the Start menu. You can also launch it from Classic Control if that app is installed.

## Settings and history

- **Reverse DNS** is optional and off by default. While it is on, remote addresses are looked up through your Windows DNS resolver.
- **New since…** marks programs that connect for the first time, or that reach a new country or purpose. The first run is a silent baseline. Notifications can be turned off in the same menu. **New since… > Clear history** deletes the local history, including data usage history.
- **Data usage** shows bytes sent and received per program. Recording new counts needs administrator permission. Without it, the dialog asks you to restart as administrator and still shows history already recorded.

History and diagnostic logs stay in the app's local data on your PC. Nothing is uploaded.

## Common questions

- **Traffic or data usage counts are missing.** Packet and byte counts use a Windows kernel event session and need the app to run as administrator. The connection list itself works without administrator permission.
- **Does this app change my firewall?** No. **Make firewall rule** only saves a file you choose (for Classic Firewall Advanced Rulesets) or copies a command to the clipboard. A red warning appears when a rule would block Remote Desktop.
- **Where do countries come from?** Countries come from a database bundled inside the app. It is used offline and is never downloaded at run time.
- **How do I filter the list?** Use the filter box. You can filter by text, a process name, a port such as :443, or a process id such as pid:1234.

## Reset and uninstall

To clear New since… and data usage history only, use **New since… > Clear history**. To remove the app, uninstall it from Settings > Apps. Uninstalling removes its local data.

## Report a problem

Open a public issue at https://github.com/IanD-Bot/support/issues/new?template=classic-network-monitor.yml. Please don't include personal information in the issue.

## Privacy

See the [Classic Network Monitor privacy policy](../classic-network-monitor).
