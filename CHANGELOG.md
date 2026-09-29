# Changelog

The current version is shown in the menu under Settings, and in the notification when the script loads.

**Numbering:** each new feature or fix gets the next `1.0.x` number. If it takes more than one try to get right, the follow-ups get a letter: `1.0.1`, `1.0.1b`, `1.0.1c` and so on. The next feature moves on to `1.0.2`.

## 1.0.0 - 2026-09-29

- First release. Detects needle objects as they appear (anything named needle, anything in the needle objective folders, needle tools in characters and backpacks) and draws a marker, tracer and distance label on each, including who's holding it.
- Menu with ESP and tracer toggles, a status line for the nearest needle and the latest event, plus notifications.
- The workspace scan is spread across frames so it doesn't stutter, and the menu only redraws what actually changed.
