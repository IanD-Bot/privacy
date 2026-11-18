# Classic Control support

_Last updated: November 18, 2026_

Classic Control is published by Deck-Of-Jacks.

## About this app

Classic Control brings back the classic Control Panel (category, large icons, and small icons, with search and favorites) and classic taskbar sound and network controls.

## Requirements

Windows 10 version 2004 (build 19041) or later, or Windows 11.

## Install and launch

Install the app from the Microsoft Store, then open it from the Start menu. The Control Panel window opens, and sound and network icons appear in the notification area. If they land in the overflow (^), drag them onto the taskbar. On Windows 11 you can also use Settings > Personalization > Taskbar > Other system tray icons.

Closing the Control Panel window keeps the app in the tray. Starting the app again while it is running brings the Control Panel window back. With Start with Windows, it starts in the tray only.

## Settings

Right-click a tray icon and choose **Settings...** (also linked from the Control Panel window).

- **General:** Start with Windows, and the default Control Panel view.
- **Tray icons:** one icon (default) or separate icons. You can hide the Sound or Network icon when using separate icons.
- **Sound:** the optional mic-mute hotkey (off by default), and the volume chime.
- **Network:** the network connect notice and its sound.
- **Troubleshooting:** **Launch check...** lists which page each Control Panel item opens on this PC.

Your preferences, favorites, and launch locations are saved in a settings file in your Windows user profile. Light and dark mode follow Windows and apply immediately.

## Common questions

- **An item opens the wrong page, or nothing, after a Windows update.** Open Settings > Troubleshooting > Launch check... to see which page each item opens on this PC.
- **Sound says "Windows Audio isn't available."** Start the Windows Audio service. The app reconnects by itself.
- **The mouse wheel over the sound icon does nothing.** Some security tools block low-level mouse hooks. Everything else still works.
- **The mic-mute hotkey doesn't register.** Another app already uses that combination. Choose another in Settings.
- **Renew IP or Reset network asked for administrator permission.** Those Network Quick Fixes ask for permission every time you run them. Reset network also needs a restart afterwards.
- **What is my public IP?** That built-in shortcut on the Shortcuts tab is the one exception that goes online, and only when you click it.

## Reset and uninstall

Turn off Start with Windows in Settings if it is on, then uninstall the app from Settings > Apps. Uninstalling the packaged app removes its data.

## Report a problem

Open a public issue at https://github.com/IanD-Bot/support/issues/new?template=classic-control.yml. Please don't include personal information in the issue.

## Privacy

See the [Classic Control privacy policy](../classic-control).
