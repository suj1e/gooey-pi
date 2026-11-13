# Sidebar — Shelf

Open `index.html` directly in a browser (no server needed).

The sidebar has two independent regions: **Spaces** (navigation + counts) and
**Agents** (Working / Idle, with a `space · title` prefix and relative time).
Neither region owns the other.

## Interactions

- Spaces: click a row to select it. The `+` in the Spaces header opens a popover
  anchored beside the sidebar.
- Popover, **Folder** tab: `Choose folder…` stands in for the OS folder picker;
  the recent rows add a space immediately and select it.
- Popover, **Agent** tab: pick a space and a harness (`OMP` or `Pi`), then
  `Start agent` inserts a new agent row under Working and closes the popover.
- Agents: click a row to select it; the history icon next to the Agents count is
  the only other action there (no add button).
- The search field takes focus normally; Escape or a click outside closes the
  popover.

This directory is a prototype surface, not product code. It is ignored by git.
