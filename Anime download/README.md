# Anime download (torrent) scripts (they uses only horriblesubs releases).

those scripts uses aria2 plus rsstail for anime_watcher and nyaa/nyaa2

1) anime_watcher uses horriblesubs release via [nyaa.se](https://nyaa.se) RSS feeds, watching new episodes and downloading if anime is in the filter (fullname or partiel name, but it needs to match, take precaution) and you need a file with exit code listed, like mine .aria2_exit on the same folder

2) haruhidl uses horriblesubs releases via [haruhichan.com](https://haruhichan.com). It's used like that "haruhidl quality(720p/1080p) url(ex: http://haruhichan.com/page/anime/1483/download-flying-witch.html)" folder(ex: "Flying Witch")

3) nyaa/nyaa2 use horriblesubs release via [nyaa.se](https://nyaa.se) RSS feeds. It's used like that "nyaa/nyaa2 quality(720p/1080p) anime name(ex: "Flying Witch").

nyaa let you choose what to downloads (ex: ep 1 to 5, only ep 5, or all for all episodes) and nyaa2 downloads all episodes directly. There is also an -s argument for anime search (ex: nyaa/nyaa2 -s 720p "Flying Witch")

# Don't forget to modify the directory variable dir=/folder= and adapte whatever you want to your needs.
