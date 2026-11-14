# Desktop — prototype

Open `index.html` directly in a browser (no server needed). This is the
desktop-level surface: sidebar, pane tabs, composer, settings, plugins, and
remote-machine pairing.

## Sidebar

- **Spaces** — flat list; each space expands to its sessions (chevron). Sessions
  can be renamed inline with the pencil (Enter commits, Escape cancels).
- **Agents** — independent region above Remote machines, grouped Working / Idle /
  Done with a status light per row. State is labelled `OSC 5701`. No add button.
- **Remote machines** — a machine row expands into its own spaces, agents, and
  screens. Screen thumbnails open the Screen pane.
- **Footer** — Plugins, Settings, Pair device.

The Spaces `+` opens a two-tab popover: **Folder** (recent folders add instantly;
`Choose folder…` stands in for the OS picker) and **Agent** (Space + Harness
dropdowns, `OMP` default, `Pi` available).

## Panes

Chat, Browser, Files, Terminal, plus two skill-opened panes: Screen (remote
framebuffer) and Media (session capture). Tabs marked `✦` are opened by a skill;
each pane header repeats the provenance badge.

## Composer

Model menu, thinking level (click to cycle Low / Medium / Max), context meter,
slash-command menu (type `/` or use the Commands chip), attachments, dictation
state, and send.

## Settings / Plugins

Settings has General, Appearance, Machines, Alerts, and Updates; the nav swaps
the panel. Plugins shows capability cards with toggles.

## Remote machines

`Add machine` / `Pair device` share one modal. Pairing shows a six-digit code and
an expiry hint.

This directory is a prototype surface, not product code.
