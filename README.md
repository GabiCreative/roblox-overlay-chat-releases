# Roblox Overlay Chat

A chat window that sits on top of Roblox and lets you talk to your friends in the same server, even when the in-game chat doesn't work (region blocked, disabled by the game, whatever).

**[Download the latest version here](https://github.com/GabiCreative/roblox-overlay-chat-releases/releases/latest)** — grab the `.exe` file.

## Installing

1. Download and run the installer
2. Windows will show a "Windows protected your PC" warning because the app isn't signed. Click **More info**, then **Run anyway**. It's fine.
3. That's it. The app updates itself from now on, you never need to come back here.

## How to use it

- Start the app, then join any Roblox game. The panel in the top right corner connects automatically and shows the game's name.
- Press **Ctrl+Shift+C** to start typing. Press **Esc** or Ctrl+Shift+C again to go back to playing (the panel becomes click-through so it never blocks your game).
- The **X** hides the panel. Ctrl+Shift+C brings it back. Quit from the tray icon near your clock.
- **Server tab** = people in your exact server. **Game tab** = everyone playing that game, any server.
- You only see people who also have the app. If your friend isn't showing up, they either don't have it or they're in a different server (use Join Friend so you land in the same one).

## Commands

Type these in the chat box:

| command | what it does |
|---|---|
| `/w name message` | whisper, only that person sees it |
| `/me does something` | action message in italics |
| `/mute name` | hide someone's messages (just for you) |
| `/unmute name` | undo that |
| `/clear` | clear the chat window |
| `/help` | shows this list in chat |

## How it works (short version)

Roblox writes a log file on your PC that says which server you joined. The app reads that file (nothing is injected into Roblox, no rules broken) and connects you to a chat room for that exact server. Your username and avatar come from the Roblox account you're logged into, so nobody can pretend to be someone else.

## Rules and moderation

- Messages go through a chat filter (swearing, bullying etc. comes out as ####). Trying to dodge it with stuff like k1ll doesn't work either.
- If someone's being toxic, hover over their message and click the flag to report it. A moderator sees every report.
- Breaking the rules can get you muted or banned. Bans stick.
- Messages aren't saved anywhere. Once they scroll by, they're gone.

## Problems?

- **Panel says "Not in a game"** — make sure Roblox is in windowed or borderless fullscreen (the default). Exclusive fullscreen hides overlays.
- **Can't see my friend** — same game isn't enough, you need the same server. Join through the friends list.
- **First message of the day takes a bit** — the chat server wakes up if nobody used it for a while. Give it a few seconds.
