# Mealie
I use Mealie to store the recipes me and my family use frequently across a wide range of sources from paper cookbooks to online cooking websites.

## Changes Made

- Tweaked the maximum memory the container uses ([this line](https://github.com/RooRay/DockerCompose/blob/db36fdb260401a4eaa066a141fa8e5334fa9eed4/mealie/docker-compose.yml#L1))) to keep my Raspberry Pi from running out of memory and crashing - I have not tested long-term whether or not this has a detrimental impact on Mealie but it seems fine so far