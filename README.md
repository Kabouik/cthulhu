# Cthulhu

Cthulhu is a simple python CLI application that facilitates the streaming of torrents directly from 1337x. It uses [webtorrent](https://webtorrent.io/) to stream video from magnet links directly.

<p align="center">
<img src="./preview.gif" alt="Video Preview" width="700px">
</p>

Cthulhu is heavily inspired by [Bugswriter's notflix](https://github.com/Bugswriter/notflix), which was written using shell scripting. The differences between our programs aren't very stark. All in all, I wrote this program mainly for fun and practice. 

Feel free to submit issues and feature requests.

### Notable Features (so far)

- Runs in the terminal
- Flags for filtering results by specific categories (Movies, TV Shows, Anime)
- Filtering out unwanted results by default, such as application files and pornogrophy

## Requirements

- [lxml](https://lxml.de/) - A python library for parsing XML/HTML. `pip install lxml`
- [webtorrent](https://webtorrent.io/) - A tool to stream torrent. `npm install webtorrent-cli -g`

## Installation for Linux/macOS

### cURL
cURL **cthulhu** to your **$PATH** and give execute permissions.

```sh
sudo curl -sL "https://raw.githubusercontent.com/trianglecirclexyz/cthulhu/main/cthulhu" -o /usr/local/bin/cthulhu
sudo chmod +x /usr/local/bin/cthulhu
```
- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, remove `cthulhu` from your **$PATH**, for example `sudo rm -f /usr/local/bin/cthulhu.`


