# BlueMap for Pelican (releases)

Built releases and the update feed for the `pelican-bluemap` Pelican Panel plugin. It installs and configures [BlueMap](https://bluemap.bluecolored.de) on Minecraft Java servers (MariaDB storage, HTTPS through Nginx Proxy Manager, configuration wizards).

- `releases/` holds the plugin zips.
- `update.json` is the feed the panel reads (`update_url` in the plugin's `plugin.json`).

First install: in the panel, Admin -> Plugins -> Import from URL, paste the zip URL from `update.json`, then Install. After that the panel offers updates itself.

This repo is written by a release pipeline; don't edit it by hand.
