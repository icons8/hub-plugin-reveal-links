# Links to Finder — an Agents Hub plugin

> Original author: [@Eugenius-S](https://github.com/Eugenius-S) · upstream: [Eugenius-S/hub-plugin-reveal-links](https://github.com/Eugenius-S/hub-plugin-reveal-links). This is the copy the Hub catalog installs; the author's updates are taken into it from upstream.
>
> License: MIT (Eugenius-S)

File links in session chats: a plain click opens the file in the hub's "Files", Cmd-click (Ctrl-click on Windows)
opens the folder with the file selected: Finder on Mac, Explorer on Windows. Works on the computer where the hub runs;
from a phone the links open in "Files".

Needs a hub with `/api/reveal` on the page (POST `{path, cwd}`); without it Cmd/Ctrl-click opens "Files".

Install: Settings -> Plugins -> Available -> reveal-links.

UI language: English, or Russian when the hub language is Russian.

Code — MIT.

Icon — [3D Fluency](https://icons8.com/icons/3d-fluency) by Icons8.
