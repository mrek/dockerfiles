# mrek83nl/youtube-dl

A small command-line utility to download videos from [YouTube.com](http://youtube.com) as well as some other supported video sites.
See the official [youtube-dl](http://ytdl-org.github.io/youtube-dl/) site for more information.

## Example
````
docker run --rm -v <Local Path>:/data mrek83nl/youtube-dl -o '%(title)s.%(ext)s' zF34dRivLOw
````