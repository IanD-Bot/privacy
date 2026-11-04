# Classic Network Monitor privacy policy

_Last updated: November 4, 2026_

Classic Network Monitor is published by Deck-Of-Jacks.

## Summary

Classic Network Monitor collects no personal data, and it does not send any data off your PC.

## Details

- **No data collection.** The app has no telemetry, analytics, crash reporting service, accounts, or advertising.
- **No network connections of its own.** The app reads the connection table from Windows on your PC. Countries come from a database bundled inside the app; it never downloads it or contacts its provider. It does not check for updates.
- **Reverse DNS (off by default).** If you turn on the Reverse DNS toggle, remote IP addresses in the list are looked up through your Windows DNS resolver, which sends them to your configured DNS server. Nothing is looked up while the toggle is off.
- **Traffic counts.** When you run the app as administrator, it counts packets and bytes per connection with a Windows kernel event session on your PC. The counts stay in memory and are not saved or sent.
- **Local files.** A crash log and diagnostic logs are written to the app's local data folder on your PC. Nothing is uploaded. Uninstalling the app removes them.
- **New since… history.** To mark apps that connect for the first time, the app keeps a small list of the programs that connected and the countries and purposes each one reached, in its local cache folder on your PC. The list is never uploaded or shared. You can delete it at any time with **New since… > Clear history**, and uninstalling the app removes it. Notifications about new apps are shown by Windows on your PC and can be turned off in the same menu.
- **Firewall rules.** "Make firewall rule" only saves a file you choose or copies a command to your clipboard. The app never changes your firewall.

## Changes to this policy

If this policy changes, the updated version is posted at this same address with a new "Last updated" date.

## Contact

Questions or concerns about this policy? Open an issue at https://github.com/IanD-Bot/privacy/issues. Please don't include personal information in the issue.
