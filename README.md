# Infinite Soul School · media

Public file host for **finished, approved** Infinite Soul School videos and carousel slide videos, so Buffer (and later the Meta API) can fetch them by URL.

- Files are added only by `pipeline/host.py` in the main repo (`Alfatrees/Alfatrees-Mindset---Scool-of-Life`):
  `python3 pipeline/host.py add out/<id>.mp4` → prints `https://raw.githubusercontent.com/Alfatrees/infinite-soul-school-media/main/<file>`
- Nothing else lives here: no scripts, no secrets, no drafts. Rules are in the main repo's `MASTER.md` (12.2b).
- Files may be removed once every post using them has gone out (`python3 pipeline/host.py remove <file>`).
