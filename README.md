# find-a-needle-script

Needle tracker for Find a Needle. The menu is [JDUI](https://github.com/jdev-studio/jdui).

## Running it

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/jdev-studio/find-a-needle-script/refs/heads/main/Needle"))()
```

You need an executor that supports the Drawing API (written against Matcha).

## What's in it

- **Needle ESP** – as soon as someone digs the needle up it gets a marker, a tracer and its distance, and stays marked while it's carried to the farmer. The label says who's holding it.
- **Alerts** – a notification when a needle appears or disappears, and the latest event in the menu.

The needle has no object in the game until it's found (the server only sends which hay piece it's under), so this can't show where it's hidden. It shows it from the moment it's dug up.

## Controls

| Key | Action |
| --- | --- |
| N | Toggle needle ESP |
| T | Toggle tracers |
| Right Ctrl | Show / hide menu |

The menu starts hidden; press Right Ctrl to open it. The menu key can be changed in Settings. Settings also has a toggle for the menu's glow and trail effects.
