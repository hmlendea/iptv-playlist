[![Donate](https://img.shields.io/badge/-%E2%99%A5%20Donate-%23ff69b4)](https://hmlendea.go.ro/funding)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://gnu.org/licenses/gpl-3.0)

# IPTV Playlist

A collection of free, publicly available IPTV stream playlists for television channels. Each channel includes multiple fallback stream URLs to maximise availability.

## ✨ Features

- Romanian TV channels (`ro.m3u`)
- Moldovan TV channels (`md.m3u`)
- Multiple fallback stream URLs per channel for improved reliability
- Compatible with any M3U-capable media player or IPTV application

## 🚀 Usage

Open a playlist directly from its raw GitHub URL in any M3U-compatible player.

**VLC:**
```
Media > Open Network Stream > https://raw.githubusercontent.com/hmlendea/iptv-playlist/master/ro.m3u
```

**Kodi / IPTV Simple Client:**

Set the M3U playlist URL to:
```
https://raw.githubusercontent.com/hmlendea/iptv-playlist/master/ro.m3u
```
or
```
https://raw.githubusercontent.com/hmlendea/iptv-playlist/master/md.m3u
```

Alternatively, clone the repository and open the `.m3u` files locally.

## ⚠️ Known Limitations

- Stream URLs are maintained on a best-effort basis and may become unavailable without notice if the broadcaster changes or removes the stream.
- Some channels provide multiple URLs; if one fails, attempt the next entry for the same channel.

## 🤝 Contributing

Contributions are welcome. Please:
- Keep the changes cross-platform
- Keep the pull requests focused and consistent with the existing code style
- Update the documentation when behaviour changes

## 💝 Support

Found a bug or have a suggestion? [Open an issue](https://github.com/hmlendea/iptv-playlist/issues)!

If you find this project useful, consider [funding it](https://hmlendea.go.ro/funding) or giving a ⭐️ on GitHub!

## 📄 License

Licensed under the `GNU General Public License v3.0` or later.
See [LICENSE](./LICENSE) for details.
