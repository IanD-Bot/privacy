# Classic Chippy support

_Last updated: November 18, 2026_

Classic Chippy is published by Deck-Of-Jacks.

## About this app

Classic Chippy is a tray helper who finds Windows settings, explains errors, reads text from screenshots, and offers quick fixes, all on your PC. He gives you commands to copy and never runs anything for you.

## Requirements

Windows 10 version 2004 (build 19041) or later, 64-bit.

## Install and launch

Install the app from the Microsoft Store, then open it from the Start menu. The notification-area icon can show or hide Chippy; a single click on the tray icon opens search, and a double-click shows or hides him.

The default keyboard shortcut is Ctrl+Shift+Space (rebindable in Settings). Start with Windows is on by default and can be turned off in Settings.

## Settings

Open Settings from the tray menu or from Chippy's right-click menu.

- **General:** Start with Windows and quiet mode (quiet mode hides Chippy during fullscreen apps and games).
- **Shortcut:** rebind the keyboard shortcut.
- **Sounds:** mute (the same setting as **Mute sounds** in the tray menu).
- **Privacy:** optional watchers, which are off until you turn them on: Explain copied errors, and Event Log tips.
- **About:** the app version and a link to the privacy policy.

Settings are saved in a settings folder in your Windows user profile.

## Common questions

- **Chippy isn't visible.** He may be hidden, or quiet mode may be hiding him during a fullscreen app. Click or double-click the tray icon, press the keyboard shortcut, or choose Classic Chippy from the tray menu. If the icon is in the overflow (^), drag it onto the taskbar.
- **The keyboard shortcut does nothing.** Choose another shortcut in Settings > Shortcut. Another app may already be using the same combination.
- **Does Chippy run PowerShell commands?** No. Script answers and templates have a Copy button. The Open PowerShell and Open elevated PowerShell buttons only open an empty window (the elevated one through the normal Windows prompt). You paste the script yourself. Chippy never runs elevated.
- **How do I read text from a screenshot?** Take a window screenshot with Alt+Print Screen and choose **Read text**, or paste or drop an image. Recognition uses the text recognition built into Windows, on your PC. Turn this off in Settings > Privacy > Read text from window screenshots.
- **How do I review recent Windows errors?** Right-click Chippy or use the tray menu and choose **Review recent Windows errors**. That lists recent Error and Critical events from the System and Application logs in the last 7 days.

## Reset and uninstall

Turn off Start with Windows in Settings if you want it off, then uninstall the app from Settings > Apps. Uninstalling the packaged app removes its data.

## Report a problem

Open a public issue at https://github.com/IanD-Bot/support/issues/new?template=classic-chippy.yml. Please don't include personal information in the issue.

## Privacy

See the [Classic Chippy privacy policy](../classic-chippy).
