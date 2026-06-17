# sky widget bundle for Tesserae

Aurora alert score (NOAA SWPC) and current moon phase. Two-widget celestial bundle, no API keys.

Drop into [Tesserae](https://github.com/dmellok/tesserae) via Settings → Widgets → Browse community widgets.

## Folders shipped

- `sky_aurora`
- `sky_moon`

## What happened to air traffic + BoM warnings?

They moved into their own single-widget repos so you can install just the one you want:

- [`tesserae-air-traffic`](https://github.com/dmellok/tesserae-air-traffic), overhead-flights widget (OpenSky)
- [`tesserae-bom-warnings`](https://github.com/dmellok/tesserae-bom-warnings), Australian BoM warnings

If you had the v0.1.x sky bundle installed, the v0.2.0 update drops the `sky_air_traffic/` and `sky_bom_warnings/` folders. Re-install them from their new catalog entries (Air Traffic, BoM Warnings) on Settings → Widgets → Browse if you still want them.

## License

AGPL-3.0-or-later. See [LICENSE](./LICENSE).
