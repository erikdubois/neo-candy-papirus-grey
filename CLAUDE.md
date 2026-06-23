# CLAUDE.md — neo-candy-papirus-grey

## Project overview

Standalone repo for the **neo-candy-papirus-grey** folder-icon theme — the same folder set as
`erikdubois/surfn-papirus-grey` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-papirus-grey/` — folders only. Packaged as `neo-candy-papirus-grey-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-papirus-grey/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
