# RXP Visual Guide Builder (website)

Build RestedXP (RXP) leveling guides for WoW Forever on the world map, then export them as an addon.

This repository is the password-protected website copy. The app itself is in `app.enc`, encrypted with the site password; `index.html` asks for the password and unlocks it in the browser. The map tiles and guide data are plain files.

To change the password or update the app, run **Set website password.html** from the builder folder and upload the new `app.enc` here.

## Credits and license

- Guide library and quest data come from the [RestedXP guides](https://github.com/RestedXP/RXPGuides) by RestedXP, licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). The copies in `data/` are shared under the same license.
- Map tiles are World of Warcraft minimap art, © Blizzard Entertainment, used for a free fan tool.
- Map drawn with [Leaflet](https://leafletjs.com) (BSD 2-Clause).

Free fan project, not affiliated with RestedXP or Blizzard.
