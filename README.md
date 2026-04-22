# stackwright registry

Community catalog of technologies for [stackwright](https://github.com/joppe2001/stackwright).

The live registry lives at `registry.json` on this repo's `main` branch and
is fetched at tool launch by stackwright, with a 24h local cache and a
bundled fallback compiled into the binary.

## Schema

See `registry.json` — each entry describes one technology's:
- **Design phase** fields: description, diagram color, compatible peers, logo URL
- **Setup phase** fields: CLI install commands (per platform), account requirements, auth flow
- **Scaffold phase** fields: boilerplate snippet, setup steps, docs URL

## Contributing

To add or update a technology, open a PR editing `registry.json`.
The `stackwright registry share <slug>` command produces a pre-filled issue
for you when you've added a technology locally.

## Logos

Logos live under `logos/<slug>.png`. They should be square, 128×128 or
larger, with a transparent background.
