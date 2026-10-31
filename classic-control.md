# Classic Control privacy policy

_Last updated: October 30, 2026_

Classic Control is published by Deck-Of-Jacks.

## Summary

Classic Control collects no personal data, and it does not send any data off your PC.

## Details

- **No data collection.** The app has no telemetry, analytics, crash reporting, accounts, or advertising.
- **No network connections.** The app does not connect to the internet or to any server, and it does not check for updates. The one exception is a shortcut you click yourself: the built-in "What is my public IP?" shortcut on the Shortcuts tab asks icanhazip.com for your public IP address, and only when you click it. That site sees your IP address, as any website does. To show the network flyout it reads your network adapters' status from Windows on your PC.
- **Settings stay on your PC.** Your preferences, favorites and launch locations are saved in a settings file in your Windows user profile. If you chose "Start with Windows", Windows saves that setting too. Nothing is uploaded. Uninstalling the app removes the packaged app's data.
- **Network Quick Fixes.** These run only when you choose them. They start built-in Windows tools (`ipconfig /release` and `/renew`, `ipconfig /flushdns`, `netsh winsock reset`, `netsh int ip reset`), which renew or reset your network settings. Windows may then reconnect to your network as usual. Classic Control sends nothing itself.
- **Shortcuts.** The Shortcuts tab runs the PowerShell commands listed there (the built-ins or your own) only when you click one. Your shortcuts are saved in the same settings file.
- **Other apps.** Some buttons open Windows tools such as Control Panel, Settings, Task Manager or Process Explorer. Each of those tools has its own behavior.

## Contact

Open an issue at https://github.com/IanD-Bot/privacy/issues.
