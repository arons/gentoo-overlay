arons7's gentoo overlay
=========================

a simepl Gentoo Overlay.

----------

To add this to your list of overlays, as root, run the following

```
# Download and save this repo xml to /etc/layman/overlays/
curl -o /etc/layman/overlays/arons7.xml https://raw.githubusercontent.com/arons7/gentoo-overlay/master/arons7.xml

# Add my overlay to layman
layman -a arons7

# Sync arons7 layman overlays
layman -s arons7

# or sync all layman overlays
layman -S
```

If you don't have layman setup on your machine please read this: https://www.gentoo.org/proj/en/overlays/userguide.xml

----------

This overlay provides ebuilds for the following packages:

* [Plex Media Server](https://plex.tv/downloads): media-tv/plex-media-server - Public released are "stable" (arch) and PlexPass releases are "unstable" (~arch)

