# CASA VIDAA deep-link adjustment

This hosted copy is based on the community Stremio build for Hisense VIDAA:
https://github.com/NoobyGains/stremio-vidaa-tv

The startup router was adjusted to preserve a valid initial hash route (for example `#/detail/series/tt26545992`) instead of replacing it with the default route. This allows CASA recommendation cards to open directly on the selected detail page. The rest of the TV interface and its assets are from the upstream published build. `README-UPSTREAM.md` preserves the upstream project documentation.

This copy is served below the CASA GitHub Pages origin, so it shares browser storage with CASA. Stremio account state from the original `noobygains.github.io` origin is separate; the account may need to be linked once on this copy.

The upstream Stremio Web project identifies its license as GPL-2.0. See `LICENSE-STREMIO.md` and the upstream project at https://github.com/Stremio/stremio-web. The VIDAA build is maintained at https://github.com/NoobyGains/stremio-vidaa-tv.
