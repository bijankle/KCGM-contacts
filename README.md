# KCGM Contacts

Lightweight contact search app, published with GitHub Pages.

* `contacts.json` holds all contacts (one per line, so the change history is easy to read).
* `index.html` is the whole app. Search splits what you type on spaces and looks for every word in every column, ignores case and accents, matches phone numbers with or without spaces, and tolerates small typos.
* Tap a number to call, the person icon to save to phone contacts, the pencil to edit.

## Editing

Open the gear, paste a GitHub fine grained token (Repository access: only `bijankle/KCGM-contacts`, Permissions: Contents read and write). Each save is committed straight to `contacts.json`; the site updates for everyone within about a minute.
