# Circuit Central Theme

The shared shadcn theme for Circuit Central apps: navy with a sunflower highlight, Plus Jakarta Sans, and 10px corners.

## Install

From an app's `frontend` folder, with the release tag:

```
bunx shadcn add https://raw.githubusercontent.com/19th-Judicial-Circuit-Court/circuit-central-theme/v0.2.1/courthouse.json
```

Rerun it with a newer tag to update.
Change the theme here, never in an app's `index.css`.

## Highlight color

`bg-highlight`, `text-highlight-foreground`, and `bg-highlight-muted` are the playful accent.
Use them sparingly, for things that need a second look.
Text on `bg-highlight-muted` uses `text-highlight-muted-foreground`, and a sunflower outline uses `border-highlight-border`, which stays visible on white.

## Status colors

`bg-destructive-muted` with `text-destructive-muted-foreground` is the soft red for a status that has failed, such as Expired.
Pair it with `highlight-muted` for one that needs a second look, such as Expiring Soon, and `secondary` for one that is fine, such as Active.
