# wpe-flatpak

This repository contains flatpak-builder files to create the necessary Flatpak deployments of different WPE components.

Deploymets are readily hosted on https://software.igalia.com/. To install from there:
```
$ flatpak --user remote-add wpe-releases --from https://software.igalia.com/flatpak-refs/wpe-releases.flatpakrepo
$ flatpak --user install org.wpe.Cog
$ flatpak run org.wpe.Cog -P fdo <url>
```
