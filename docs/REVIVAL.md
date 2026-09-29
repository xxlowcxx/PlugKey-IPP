# Emergency and system revival

Plug Key is a presence factor. IPP is how presence is spoken when the system is sick or offline.

## Why this works when passwords fail

- Stolen disk image does not include the hands.
- Offline box still sees USB attach/detach.
- Compromised userspace can lie about files. It has a harder time forging a live cadence if the interpreter sits below it.

## Modes (same stick)

- A — first identity / mint
- B — second identity after DOUBLE flip
- R — revival: known-good local profile, trusted store, rescue shell
- X — emergency: keep network dark, local recovery only

Bind modes to machines we own. This is not a remote exploit toy.

## First software to write

1. Timestamp logger for insert/remove only.
2. Cadence matcher with operator-local timing file (not in git).
3. One revival action on an owned box (rescue boot stanza or sidecar unlock).

Exact R/X sentences stay out of git.
