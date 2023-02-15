This is a fork of https://github.com/jgoerzen/docker-bbs/tree/master/dosbox

I made it because tightvncserver by default, doesn't support XKEYBOARD.
The only thing I had to change was the startvnc script, adding as a workaround export XKB_DEFAULT_RULES=base 