# Liquid.qihl README

Welcome to Liquid.qihl! This document contains everything you need to know to interact with this server. Please read all of it before posting to `#help-desk`, it will save you and the staff time and questions. Thank you.

## Contents

1. [Rules](#rules)  
2. [Ranks](#ranks)  
	2.1 [Checking Ranks](#checking-ranks)  
	2.2 [Finding Steam64IDs](#finding-steam64ids)  
4. [Reporting Players](#reporting-players)  
5. [Finding, Joining, and Hosting Games](#finding-joining-and-hosting-games)  
6. [Get Started](#get-started)  

## Rules
1. Do not threaten, dox, or ddos.
2. Do not break Discord ToS.
3. Do not play in lobbies when under the minimum rank. You must forfeit (`-refresh` in game  **NOT** in Discord). Only applies to Chessbot games (not in `#intermediate-lobbies-no-bot`, etc). 
4. Do not post lobby passwords in Chessbot lobbies. 
5. Do not share Chessbot passwords. 
6. If someone disconnects the host should pause (press `F9` in game) for 1 or 2 minutes as a courtesy to allow them to reconnect.
     
## Ranks
Lobbies are organized using the following ranks:

- Beginner: `Unknown`+
- Intermediate: `Bishop-1`+
- Advanced: `Bishop-6`+
- Expert: `Rook-1`+
- Master: `Rook-4`+
         
### Checking Ranks
Use these in `#chessbot-commands`, **NOT** in `#help-desk`.

- Check and update your rank: `!rank` 
- Check someone else's rank (without `[]`): `!rank [steam64ID]` or `!rank [@DiscordName#0000]`. 
                           
### Finding Steam64IDs
1. Copy and paste a Steam Profile URL (e.g. https://steamcommunity.com/id/SomeonesSteam) into  https://steamidfinder.com/.

2. Click "Query" in https://steamidfinder.com/.

3. Copy the `Steam64ID` from https://steamidfinder.com/ and use it for `!rank [Steam64ID]`, etc.
             
## Reporting Players
If you are in danger of demotion from a tier (e.g. You are `Bishop-1`, and playing in `#intermediate-lobbies-eue`) you should wait for your game to complete and your rank to update before you join another game in your current league. If your rank updates before you join your next game, but after you join the Chessbot lobby, and you are below the minimum rank for the league while in game (e.g. you lost your previous game and are now `Knight-9`) you must forfeit the game (by typing `-refresh` in game,  **NOT** in Discord) or be banned from this server. 

Players that experience this in your games, please consider not caring about a one-rank difference in your game. It doesn't have a serious impact, and is often an honest mistake. Making a big deal of these instances is seldom beneficial for anyone. This is not an invitation to do this, however, and we do not condone this behavior. We will be handing out bans for this, so please be careful.

If a player refuses to forfeit (`-refresh` in game,  **NOT** in Discord): Post a screenshot, their Steam Profile URL, and the final Chessbot Lobby message (after the host uses `!start`) to `#player-reports`. This does **NOT** apply to lobbies without Chessbot (e.g. `#intermediate-lobbies-no-bot`); we don't enforce ranks in lobbies without Chessbot.
    
## Finding, Joining, and Hosting Games

Games are arranged through Chessbot. You must enable direct messages from this server to interact with Chessbot. Use the following commands in `#[rank]-lobbies channels`  ONLY (e.g. `#master-lobbies`): (without `[]`)

- `!list`
- `!join`
- `!join [region]` (without `[]`)
	- Regions are: `NA`, `SA`, `EUE`, `EUW`, `RU`, `SEA`, and `OCE`
- `!join [DiscordName@0000]` (without `[]`)
- `!host`
- `!host [region]` (without `[]`)
- `!host [region] [rank-x]` (without `[]`. `rank-x` must be `your-rank` - 2 or lower. )
- `!leave`
- `!kick [@DiscordName#0000]` (without `[]`)
- `!start`
- `!cancel`
         
To join a game use `!list` (in a `#[rank]-lobbies` channel) to show available games and `!join` to join a lobby. You can also use `!join [region]` to join a specific region if there are options, or `!join [DiscordName@0000]` to join a specific user's lobby. Chessbot will whisper you the password for the lobby on Discord. Copy the password > Open Auto Chess > Lobby List > Find Private Lobbies > Paste Password > Search > Join Lobby.

If there are no games in your channel you can host one using `!host`, `!host [region]`, or `!host [region] [rank-x]` (to restrict the rank of your lobby). When the lobbies fills (8/8 players) use `!start`, then create the lobby in game with the password Chessbot direct messages you. Please wait until everybody has loaded in before starting in game. If you need to cancel the lobby you've hosted, use `!cancel`.

People can host games in any region. Look at the region when you search for the lobby in game. Don't join the lobby in game if it's not a region you prefer.
    
## Get Started
Please **read everything** above this so you understand how to interact with this server. It will save you and the staff time and questions. Thank you.
 
1. **Clear your browser cache. Open Discord in your web browser.** Make sure you are logged into the correct Discord account (name and number: `Name#0000`). Go to User Settings in Discord.  
![enter image description here](https://lh3.googleusercontent.com/BKWZi8LTdT8v6fdAQiwyLtOuR_jFj5CBjvxObViUGdM7F4jxnlGH3CxAfKgkP075SDZFcx0FvYY)
2. Go to Connections. Click the Steam icon.  
![enter image description here](https://lh3.googleusercontent.com/0BHECBR5G8obQXgH_J1IjqotC0jAQW2sXPBsFlngSYPPS4Pu_3LlAikr0Ls0WK8ymdb7ZbLhTkE)
3. Click sign in. If you haven't signed into Steam in your browser, do so.  
![enter image description here](https://lh3.googleusercontent.com/Kc5SWqhe_lUFGBwGMVxmi7g3YWbHH1rouljLqFYFy0GyRZq-ECmLzWCPYVErm5gCFsQjHw6K54M)
4. Make sure Steam appears in your list of Discord Connections.  
![enter image description here](https://lh3.googleusercontent.com/XnuTe3xZWuJ0P9em1hM6a1ne9QsAFjFR_QEfi5ZVSOupezvNTh0ef5r58LsxJPCxskRoDyLJods)

5. **Make sure you're using Discord in your web browser.** Make sure you are logged into the correct Discord account (name and number: `Name#0000`). Click this link: [autochessbot.vinthian.com](http://autochessbot.vinthian.com). Make sure this shows your Discord is connected to Steam, and the Discord and Steam usernames are correct. Click Authorize.  
       ![enter image description here](https://lh3.googleusercontent.com/08ZHOcSVKHEjHixMc53zFEc-zsw9fckQgiyG_T6dnNpot8F3vjmseO5Hoeiye8HwmudNYGawLCY) 
6. Make sure it shows the correct `Steam64ID`. Click `Link [Steam64ID]`.  
![enter image description here](https://lh3.googleusercontent.com/W2TnP6mdOc0P_jULKu-wQZvYr8-bNwszT-lY19XgFT5p5C19jBZOjB3yVd0G6Tj-cchs4ufHogE)
7. You're verified! If something went wrong clear your browser cache and try again. If that doesn't work, visit help-desk.  
![enter image description here](https://lh3.googleusercontent.com/1uOA1tSQgY02_in_NJZ0ymz64tDwu-mlhHWaqUkHVlt37S-lEx80g7y_hu_9LHoRt0I9_g1Yoa8)
8. In `#chessbot-commands` use: `!updateroles`
    
Your Discord/Steam should now be linked to Chessbot and you should be able to see some new channels (on the left of Discord). If you don't see the new channels your status may be invisible on Discord or you may have used the wrong `Steam64ID`. If you have problems, ask for help in help-desk. 

9. Go to`#league-region` and react to the post get tagged with a region. You can remove your reaction if you don't like the notifications.   
10. Go to a `#[rank]-lobbies` channel (e.g. `#beginner-lobbies`, `#intermediate-lobbies-eue` , etc) and have fun!
