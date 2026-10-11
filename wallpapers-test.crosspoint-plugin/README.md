# TEMP · Wallpaper Capability Test

Temporary CrossPoint plugin used to validate Plugin Hub firmware compatibility filtering and the wallpaper catalog UI before those firmware features are upstreamed.

This plugin intentionally requires both firmware capabilities:

- `catalog.images`
- `catalog.cache`

Firmware in the `crosspoint` family that advertises both capabilities may display this plugin. Compatibility-aware firmware missing either capability should omit it from the offered catalog.

The runtime configuration is the current wallpaper test payload and consumes the live `jadehawk/wallpapers.crosspoint-plugin` catalog and cache seed.

Author: **Jadehawk**
