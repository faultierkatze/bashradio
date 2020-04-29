# bashradio
simple command line web radio player

depends on *mpv* for playback, but other players such as mplayer can be selected with `--player <...>`

stations are saved as plain-text files in ./stations, containing one URL per file (the file name doubles as the station name displayed)

the stations provided in this repo are -unsurprisingly- ones that I like to listen to myself, serving as examples - there's no deeper meaning to the selection

```Usage:
  --help                 Display this help message.
  --player <...>         Specify the player to be used (optional, default is mpv).
  --player-option <...>  Passes an option directly to the player. Use once per option.
  --quiet                Suppresses player output except errors (stderr).
  --quieter              Suppresses all player output (stdout and stderr). Also clears up the screen when returning to the menu.
  --loop                 Automatically restart a stream unless the player is quit with Ctrl-C. EXPERIMENTAL, might break the script if with anything else than mpv!
```
