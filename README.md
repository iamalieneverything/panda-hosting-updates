# PandA Hosting — update feed

PandA Hosting OS (by Alien & Patrko) checks `stable/latest.json` for updates.
Every update is signed: PandA verifies `latest.json.sig` with its built-in public key
and the package's SHA-256 before installing, and rolls back by itself if a new
version doesn't start. Files here are published automatically — don't edit them.
