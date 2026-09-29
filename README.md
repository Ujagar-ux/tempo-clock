# Tempo

A customizable clock, countdown timer and stopwatch in one page, with live time trivia, F1 record timers and a JoJo-inspired Chaos mode.

It's a single `index.html` with no build step and no dependencies. Just open it in a browser.

## Features

**Clock**
- Analog, digital or both, with three dial styles
- 12- or 24-hour time, optional seconds, smooth or ticking second hand, date, and 13 time zones
- A new "right now" fact every 5 seconds (share of the day gone, Unix time, when the sunlight you see left the Sun, other cities' times, and more)
- A history note that reads the time as a year, so 19:24 shows what happened in 1924

**Timer**
- One-tap common timers: 30 s, 1, 2, 3, 5, 10, 15, 20, 25 (Pomodoro), 30, 45 and 60 minutes
- Custom timers with labels, saved as your own presets
- Add or take away 10 s, 1 min or 5 min while it runs
- A new fact every second, matched to the time left (milestones like 3:59 for Bannister's mile, years like 19:24 = 1924, light, heartbeats, orbits, F1 laps)
- A fact log that saves every fact shown, with sources

**Stopwatch**
- Laps with split and total times, with the fastest and slowest laps highlighted

**F1**
- Lights-out reaction test with jump-start detection and a saved best time
- Record times you can load as timers: 1.80 s pit stop, 1:18.792 fastest lap, 3:27 shortest race, 1:13:24 fastest race, 4:04:39 longest race

**Chaos mode**
- Time runs fast, slow or backwards; colors, language (8 languages), digit scripts, fonts and sounds change at random
- JoJo abilities: The World and Star Platinum time stop, Bites the Dust rewind, King Crimson skip, Made in Heaven acceleration
- Intensity slider, sound and motion toggles, and a Reset reality button

**Customization**
- Accent colors, light/dark/auto theme, 5 alarm sounds, volume, ring count, last-10-seconds ticking, flash on finish and loop mode
- Settings and presets are saved in your browser (`localStorage`)

## Keyboard shortcuts

| Key | Timer | Stopwatch | F1 | Chaos |
|-----|-------|-----------|----|-------|
| `Space` | Start / pause | Start / stop | React | Start / stop chaos |
| `R` | Reset | Reset | | |
| `L` | | Lap | | |
| `Esc` | Stop alarm | | | |

## Run it

```sh
open index.html
```

To host it for free, turn on GitHub Pages for this repository (Settings → Pages → deploy from the `main` branch).

## Sources

Facts cite their sources on the page (NASA, IAU, BIPM, American Heart Association, World Athletics, Formula1.com, and others). F1 records are correct as of the end of the 2025 season.
