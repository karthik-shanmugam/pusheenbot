# pusheenbot

Pusheenbot is a [Slack /slash command](https://api.slack.com/slash-commands) that allows you to post animated Pusheen stickers to Slack.

This repo contains two components of Pusheenbot:
* **pusheen-slash-command** - simple [Google app engine](https://cloud.google.com/appengine/) webserver for the slash command
* **pusheen-stickers** - script to generate Pusheen .gifs from .pngs


## TODOs
* Allow users to choose size of pusheen (small/large options) and reduce default size
* Simple sentiment analysis for unrecognised words
* Include food Pusheen stickers & "hard" gifs (>4 frames)
* Include other Pusheens (from webcomic, etc)
