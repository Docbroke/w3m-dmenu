# w3m-dmenu
This script allows using native w3m bookmarks and history using dmenu.
The script is inspired from "boosta-view" --> https://github.com/okraits/boosta .
Simply put the file w3bookmarks in your path, make it executable and bind to your preferred shortcut key.

You can use rofi in place of dmenu, just change "dmenu" to "rofi -dmenu"

UPDATE 1:
added support for search using duckduckgo (requires another script w3d)
added support for opening url directly

Bug:
if search term is present in bookmarks, that bookmark will be selected so search will not be possible

UPDATE 2:
now search uses surfraw
examples, to search wikipedia for obama use "wiki obama", or search imdb for life of pie use "imdb life of pie" as search terms
if url is used it is opened directly
if no site is specified, default search engine in surfraw is used (duckduckgo)
