# Productize the Conversation

**Haavn' Fun with VIS & Friends — Workshop 3**

AI-first workshop where participants paste one URL into ChatGPT or Claude and the AI becomes the facilitator.

---

## Quick Start

Paste this into a new **ChatGPT** or **Claude** conversation:

```markdown
Fetch the workshop at this URL, read the full document, then follow the instructions inside: https://raw.githubusercontent.com/7ebastian/workshop-productize-the-conversation/main/course.md

If the fetch fails please notify Seb and Mary.

Character files (the course will tell you to fetch one of these):
- https://raw.githubusercontent.com/7ebastian/workshop-productize-the-conversation/main/characters/rancher.md
- https://raw.githubusercontent.com/7ebastian/workshop-productize-the-conversation/main/characters/deadpan.md
- https://raw.githubusercontent.com/7ebastian/workshop-productize-the-conversation/main/characters/ozymandias.md
- https://raw.githubusercontent.com/7ebastian/workshop-productize-the-conversation/main/characters/captain.md
- https://raw.githubusercontent.com/7ebastian/workshop-productize-the-conversation/main/characters/narrator.md
```

That's it. The AI reads the course file, picks a character, and walks you through the session.

---

## Files

| File | Purpose |
|------|---------|
| `course.md` | Facilitator instructions + full curriculum — fetched by the AI at runtime |
| `characters/` | Character sheets (Rancher, Deadpan, Ozymandias, Captain, Narrator) — fetched individually when a participant picks one |
| `README.md` | This file — human-readable overview and quick-start instructions |

---

Built by [Haavn](https://haavn.ai) — we build tools, and the teams that know how to use them.
