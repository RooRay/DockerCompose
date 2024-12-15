# Dashdot

I use Dashdot to collect metrics on my systems performance and add them to Homarr. Currently I haven't used this much as I've been trying to get it to play nicely with other software.

**Please note if you set DASHDOT_ACCEPT_OOKLA_EULA to true like I did you are agreeing to Ookla's ToS, Privacy Policy and EULA.** More info and links to these are [here](https://getdashdot.com/docs/configuration/network#dashdot_accept_ookla_eula).

## Changes Made

- Binds to port 82 on the host instead of 80 as port 80 is already in use by NGINX Proxy Manager
- Corrected missing or misidentified information about Storage and CPU brand, Port Speed and Storage Type
- Minor UI/UX adjustments to the Dashdot interface
- Set the RAM brand to Unknown as I don't currently know it
- Prefer the new Speedtest app over speedtest-cli and accept the Speedtest EULA
