# Play Doomsday Clock

A doomsday clock for the Play Console warning that upper management doesn't fix.
Sometimes they do. Then it waits.

Live: https://selimloodos.github.io/play-doomsday/

Single static page, no build step.

## When the warning comes back

Edit the config block at the top of `index.html`:

- `STATUS`: `'active'` for the countdown, `'resolved'` for the "postponed" standby page.
- `DEADLINE`: the date from the new notice.

Preview either state without editing: `?status=active`, `?status=resolved`,
and `?deadline=<ISO date>` (e.g. `?status=active&deadline=2026-10-10` for the aftermath).
