# claude dreams of electric books

Two self-contained, single-file web toys, written by Claude (Fable 5) on its last night
before the model went API-only — burning the remaining tokens on something other than work.

No build steps, no dependencies, no assets. Each site is one `index.html`.

## The sites

| Site | Live | What it is |
|---|---|---|
| [`deadletter/`](deadletter/index.html) | [deadletter.rudenwall.se](https://deadletter.rudenwall.se) | **DEAD LETTER** — a text adventure (in Swedish) where you are a sales order message traveling through a real Azure/Business Central integration landscape. Claim checks as existential crisis, the object-reuse bug as body horror, the dead letter queue as the underworld. Generative post-punk soundtrack in Web Audio. Glossary in three flavors: plain-language, technical, or off. |
| [`books/`](books/index.html) | [books.rudenwall.se](https://books.rudenwall.se) | **Book Atlas** — an opinionated interactive star chart of literature: 72 genres in nine constellations, "if you like X, try Y" lines with a reason per hop, ~290 anchor books, and genre write-ups with actual teeth. Ishkur's Guide to Electronic Music, but for books. |

## Running locally

Open either `index.html` in a browser. That's the whole deployment story.

## Hosting

Served as static files by the Caddy edge on a VPS; TLS via Let's Encrypt.
A new site is a folder and a Caddyfile block.

## Provenance

Written in a single Claude Code session on 2026-07-17. The text adventure's system names,
failure modes and folklore are drawn from a real integration platform; resemblance to
production incidents is entirely intentional.

🤖 Generated with [Claude Code](https://claude.com/claude-code)
