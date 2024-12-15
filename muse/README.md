# Muse

I use Muse to run a music Discord bot in a small Discord server for me and my friends to enjoy. This is currently the only service hosted outside of my homelab on my RackNerd VPS.

Due to YouTube trying to block bots from using their services, this container depends on the Cloudflare WARP container to handle its traffic to use a cleaner IP address.

> [!WARNING]
> Depends on the WARP container due to YouTube-related issues. WARP may not be required if you have clean IPs or a better implementation of authentication for YouTube.

## Changes Made

- Enabled Spotify API features for looking up songs with Spotify
- Enable a cache size of 10GB for songs
- Enabled SponsorBlock support and a timeout for if the SponsorBlock server is unavailable
- Added bot status information