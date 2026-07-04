# roblox overlay chat

chat that sits on top of roblox. works even when in-game chat is blocked or disabled. you talk to anyone in your server who also has the app.

## download

get the exe from [releases](https://github.com/GabiCreative/roblox-overlay-chat-releases/releases/latest). windows will warn you because it's not signed, click more info > run anyway. after installing once it updates itself.

## using it

- open the app, join a game, it connects by itself
- ctrl+shift+c to type, esc to go back to playing
- the x hides it, ctrl+shift+c brings it back, quit from the tray icon
- server tab = your server, game tab = everyone playing that game
- you only see people who have the app. join your friend through the friends list so you end up in the same server

commands: `/w name message` (whisper), `/me`, `/mute name`, `/unmute name`, `/clear`, `/help`

## how it works

roblox saves a log file on your pc that says which server you joined. the app just reads that file, nothing gets injected into roblox. your name comes from the account you're logged into so you can't fake being someone else.

there's a chat filter, and you can report messages by hovering over them and clicking the flag. bans are permanent. messages aren't saved anywhere.

if it says "not in a game", put roblox in windowed or borderless fullscreen.
