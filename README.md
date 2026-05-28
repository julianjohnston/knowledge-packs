# AIMS-OS Prototype Hub

Self-contained static-HTML design prototypes for AIMS-OS. Each prototype is a single HTML file with inline CSS + JS — no build step, no dependencies. Open them in a browser and they work.

## Prototypes

| Prototype | File | What it covers |
| --- | --- | --- |
| Prototype Hub | [`index.html`](index.html) | Landing page linking to the rest |
| Agentic Studio | [`agentic-studio.html`](agentic-studio.html) | Agent-network builder, knowledge configurator, sub-nodes |
| Communication Hub | [`communication-hub.html`](communication-hub.html) | Channels (Voice, WhatsApp, Email, SMS), routing, agent assignment |
| Governance Studio | [`governance-studio.html`](governance-studio.html) | Knowledge Packs, Truth Planes, approval workflows |
| Voice Channel UX | [`voice-channel-ux.html`](voice-channel-ux.html) | Voice flows, call routing, human handoff |

There's also `agentic-studio-demo.html` (a parallel demo variant) and supporting assets under `governance-studio/` and `voice-channel/`.

## Running locally

Open `index.html` in a browser directly, or serve the directory:

```bash
python3 -m http.server 8765
# then open http://localhost:8765/
```

A static server is preferable — some browser features (relative paths, history navigation) behave better when content is served over HTTP.

## Documentation

Internal context for the prototypes lives alongside the HTML:

- `KNOWLEDGE_SYSTEM_V1.md` — the knowledge system design
- `AUDIT.md`, `FEATURE_REVIEW.md` — review notes
- `TICKET_*.md` — implementation ticket drafts

## Status

Internal prototype. Not for public distribution.
