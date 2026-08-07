# VI Intel — Intel Feed

Live news feed for the VI Intel iOS app. Edit `news.json` and commit — the app picks it up on next refresh, no app update needed.

Schema per item: `id` (unique slug), `date` (YYYY-MM-DD), `tag` (NEWS | RUMOR | GUIDE | CHEATS), `title`, `body`, `image` (asset name or https URL, optional), `link` (https URL, optional).

Newest date sorts first in the app.
