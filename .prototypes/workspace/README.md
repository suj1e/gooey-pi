# Workspace shell — prototype variants

Open `index.html` directly in a browser (no server needed). One variant renders
full size at a time; the picker at the top flips between them.

| Key | Action |
| --- | --- |
| `1` / `2` / `3` | Restored / Focus / Ledger |
| `←` / `→` | Previous / next variant |
| `R` | Replay the entrance animation |

Variants:

1. **Restored** — faithful to the current app: 248px sidebar with the harness
   switcher and project tree, 52px workspace bar, ~880px reading column sharing
   the transcript measure, 420px inspector (Summary / Changes / Browser / Files),
   and the 104px composer with model, reasoning, and checkout chips.
2. **Focus** — 56px icon rail instead of the sidebar, no inspector; a single
   centered column with the composer elevated and a `Summary · Ready` pill for
   on-demand inspection. More air, larger body type.
3. **Ledger** — an engineering console: session tree with timestamps on the left,
   a dense transcript with a mono metadata line per turn, and a 300px stats rail
   (context, output, changes) instead of tabs. Composer is shorter and wider.

This directory is a prototype surface, not product code. Do not import it into
the app; it is ignored by git.
