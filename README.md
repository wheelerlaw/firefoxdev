# firefoxdev

[![Build Status](https://travis-ci.org/wheelerlaw/firefoxdev.svg?branch=master)](https://travis-ci.org/wheelerlaw/firefoxdev)

A simple .deb wrapper around the binary distribution for Firefox Developer Edition

### Installation

To use this, download the `.deb` from the Releases section of this repo, or run the following commands:

```
curl -fsSL "https://api.github.com/repos/wheelerlaw/firefoxdev/releases/latest" | jq '.assets[0].browser_download_url' | xargs curl -OL
sudo dpkg -i firefoxdev_*_.deb
```
