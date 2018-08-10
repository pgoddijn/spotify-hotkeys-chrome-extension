Forked Spotify Web Player Hotkeys Chrome Extension
==================================================

This is a fork of the Spotify Web Player Hotkeys, which is a Chrome Extension that adds keyboard shortcuts to Chrome to pause, play next and previous tracks in [Spotify Web Player](https://open.spotify.com).

The original extension was written by François Beauort and the source can be found here: https://github.com/beaufortfrancois/spotify-hotkeys-chrome-extension

You can find the official Chrome Extension (Françoi' version) in the Chrome Web Store at https://chrome.google.com/webstore/detail/kimlaecdbfehihbiieeaeelbdkahophn


I forked this extension because my daily driver is a ChromeBook and the original extension was configured to use the key combination "Alt+Shift+P" as pause, but Google recently mapped "Stylus tools" on that key combination and the extension doesn't allow me to remap. So, I simply took the original code and remapped the keys.

The current mappings:

Pause: "Ctrl+Shift+M"

Previous track: "Ctrl+Shift+<"

Next track: "Ctrl+Shift+>"


I wish it were possible to map the /-key but that key isn't supported. And somehow the spacebare is supported but it doesn't work on my ChromeBook. Still, this works just fine for me, hope it also does that for you :-).

UPDATE: Things seem to be broken: "Ctrl+Shift+M" and "Ctrl+Shift+<" don't work anymore. I'm trying to find a solution to this problem but I can't find anything about another key being in use.
If you want do do your own investigation, you might like "chrome://keyboardoverlay/" to see what key combinations do. You used to be able to call this overlay with "Ctrl+Alt+/" but this has been replaced with a window that gives you more of an overview of general functions (not useful in this case).

