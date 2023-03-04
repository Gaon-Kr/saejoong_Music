# Basic discord music bot using discord js and discord-player

After you have cloned the repo make sure to create a `.env` file with the `TOKEN` and `CLIENT_ID` specified for example

```
TOKEN=MTA4MTUyNzQ0MzkwMDM1MDU1NA.GX6Vjf.7Wyj-EHLl8ll3Vh4zOb-JSuaCJG2ZuOCAjgkZM
CLIENT_ID=1081527443900350554
```

# Running with docker

`docker run -e TOKEN=MTA4MTUyNzQ0MzkwMDM1MDU1NA.GX6Vjf.7Wyj-EHLl8ll3Vh4zOb-JSuaCJG2ZuOCAjgkZM -e CLIENT_ID=1081527443900350554 -d pabolo02345/discord-js-music-bot`

# Commands

- play
  - song {url}       - plays the song from the youtube url
  - search {keyword} - searches for the keyword on youtube and plays the first result
  - playlist {url}   - plays the playlist from url

- skip   - Skips the current song
- queue  - Displays the first 10 songs in the queue
- pause  - pauses the current song
- resume - resumes playing the current song
- exit   - kicks the bot from the voice channel
