# Agentic Leadership — Repo Structure (v1)

Top Level structure:

```
/
├── README.md
├── sessions/
├── participants/
└── shared/
```

## sessions/

Where lived time gets captured. Each session gets a folder. Nothing inside is required — only expected.

```
sessions/
  session-01/
  session-02/
  session-03/
  session-04/
```

Inside a session folder, files may include (not guaranteed):
- `transcript.md` (raw full-group transcript)
- `phone-calls/` (raw paired call transcripts)
- `slides.md` (markdown slide deck)
- `notes.md` (live / facilitator notes)
- `artifacts/` (demos, visuals, outputs)

**Rules:**
- Transcripts are raw.
- Nothing is cleaned.
- Nothing is summarized by default.
- Artifacts can be messy.
- Order doesn’t matter.

Sessions are records, not lessons.

## participants/

Where individual thinking lives. Each participant has a folder.

```
participants/
  alice/
  bob/
  charlie/
```

Inside, anything goes (notes, pillar-game, screenshots, drafts, prompts).

**Rules:**
- No formatting expectations.
- No evaluation.
- No “right” way.
- Public by default, unless someone chooses otherwise.

These folders are personal working memory.

## shared/

Things that cut across sessions. This is for material that keeps resurfacing.

```
shared/
  references.md      ← links, articles, videos
  concepts.md        ← words, phrases, language that emerges
  datasets/           ← any data we reuse
  demos/              ← shared experiments or tools
```

**Rules:**
- Nothing here is authoritative.
- This is a commons, not a canon.
- Duplication is fine.

If something shows up more than once, it probably belongs here.
