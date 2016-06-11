This repo contains two scripts one is specific for w3m, which is a wonderful text-mode web browser --> w3m-dmenu
Another script will work with any-other browser, after some easy configuration (defaults to chromium) --> dmenu-browse

Basically this scripts provides web-search/open-url/bookmarks&histor-search functions.
The scripts depends on surfraw for searching through specific sites;

EXAMPLES:

imdb pulp fiction --> to search for pulp fiction on imdb

other supported terms are

wiki for wikipedia
awiki for archwiki
aur for arch user repository
pkg for official arch packages
google for google
dict for webster dictionary
dictu for urban dictionary
torrent for piratebay
pubmed for pubmed

Practically script can be edited to add support for any search engine supported by surfraw.

By default searchs are directed to duckduckgo (as per surfraw defaults)

If inplace of search term URL is provided, it will be opened directly
