# Carbon Pulse

Neon-framed WingFlight instruments on a flat dark face: a segmented motor rpm
arc, bright green readouts, angled blue panels and condensed italic lettering
drawn from glyph masks. Studio theme, ported for airplanes from Studio's
Rotorflight Carbon Pulse.

- **Preflight** (also drawn while armed on the ground): live telemetry checks with
  lamps for pack, fuel, BEC, ESC and link, and the arm state.
- **Inflight:** motor rpm arc with needle (and the second motor on a twin), flight
  timer, profiles, power, altitude and link.
- **Postflight** (also drawn offline): recorded peaks and minimums with flight time
  and model totals.

Supports 800 × 480 and the compact 784 × 294 layout. Settings: BEC, fuel, ESC,
link thresholds and the motor rpm arc maximum (a display scale, not a limit).

Copy the whole folder, including `gfx/`. WingFlight also needs the theme listed in
its theme tables. The glyph masks in `gfx/` and `glyphs.lua` are derived from
Barlow Condensed and are under the SIL Open Font License 1.1
(`gfx/FONT-LICENSE.txt`). Everything else is GPLv3; see the per-file notices.
