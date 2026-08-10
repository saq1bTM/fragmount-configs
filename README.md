# fragmount-configs
configs for both admins and broadcasters

# INSTALLATION:

`broadcast.cfg`
put in Counter-Strike Global Offensive/csgo/cfg

`fs26_gotv.cfg`
put in debian/csgo/cfg of the server directory

# LOADING

`broadcast.cfg`
type `exec broadcast`, then pause the game and un-pause

`fs26_gotv.cfg`
type `exec fs26_gotv` IN THE SERVER CONSOLE THIS CFG IS FOR THE SERVER CONSOLE

# USAGE

`broadcast.cfg`
press x to toggle x-ray (spectator wallhacks)

`fs26_gotv.cfg`

useful terms for explaining:

`<n>` - a number
`<team prefix>` - a shortened version of a team name to save on time and typing (use the command `prefixes` to see all of them)

team 1 - the team that starts as a ct, but switches to t in the other half
team 2 - the team that starts as a t, but switches to ct in the other half

commands:

setteam`<n>`_`<team prefix>` - sets team depending on `<n>` and `<team prefix>` if n = 1 it will set team 1 if n = 2 it will set team 2, the prefix decides what logo flag and name that team will be e.g `setteam1_hz` would set team 1 to be named hazard.net, set their flag to Uzbekistan, and their logo to the hazard.net logo.

setscore`<n>`-`<n>`- sets score and the text that says "Match `<n>` of 3", e.g setscore1-1 would set the text near the top to say "Match 3 of 3" and then 1's on the side of that bar.

setprediction_`<n>` - sets the prediction in the bar that shows for 5 seconds at the start of each round saying "HLTV Odds", so if `<n>` is set to 23, it would show a 23 percent prediction for team 1 and a 77 percent prediction for team 2.

resetsettings - sets the settings like flags logos names predictions Match of 3 and others back to normal values in a PUG server.
