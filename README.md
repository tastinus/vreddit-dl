## vreddit-dl

Downloads v.redd.it videos as mp4s.

`vdl-py3` file is an executable Python3 script that can be copied right into your path.

**Note**: `vdl-py3` downloads to the current directory by default.

**Note 2**: Actual v.redd.it URLs don't work too well because it should be easier to just link the post itself.

### Dependencies

```
beautifulsoup4==4.6.3
youtube-dl==2018.11.23
```

(actual version is not a big deal, it only uses basic functionality)

Requirements can also be found in `requirements.txt`.

### Usage

`vdl-py3 <url>`

`<url>` can be either a link to a Reddit post or a .mpd link.

For example,

`vdl https://old.reddit.com/r/Animemes/comments/8v27fc/`
