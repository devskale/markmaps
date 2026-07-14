# markmaps

Markmap mind maps and a WordPress plugin for embedding them.

## Structure

```
markmaps/
├── docs/          # Markmap markdown files (render as interactive mind maps)
│   ├── AI_ResearchFields.md
│   └── default.md
└── wp-plugin/     # WordPress plugin: shortcode for embedding markmaps
    └── skalemap.php
```

## Markmaps

The `.md` files in `docs/` use `markmap:` frontmatter and render as interactive
mind maps at https://markmap.js.org/repl

## WordPress Plugin

`wp-plugin/skalemap.php` adds shortcodes:
- `[skale_date]` — displays current date
- `[skale_map]` — displays a simple mindmap
