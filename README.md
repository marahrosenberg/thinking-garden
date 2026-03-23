# Thinking Garden 2.0
### A shared memoir journal for two writers working in parallel

*Developed by [Liminal Living](https://liminalliving.net) | CC BY-NC 4.0*

---

## What this is

A Claude skill that gives two writers a shared journaling space — each on their own device, writing in parallel, with a thoughtful companion that responds to their entries and finds the connections between their work.

Thinking Garden is not a writing workshop. Claude doesn't critique, coach, or give advice. It mirrors, questions, synthesizes, and — when both writers have written enough — finds what's resonating between them.

Built for memoir writers, but useful for any two people thinking alongside each other.

---

## What it does

**Four response modes:**
- **Reflect** — mirrors back the feeling, the image, the thing underneath the words
- **Question** — one generative question that sits with a person
- **Synthesize** — names the theme or pattern surfacing in an entry
- **Connect** — finds what rhymes between your entry and your partner's

**Harvest library** — tag entries by type and format seed for future reuse as essays, scenes, lyric essays, prose poems, and more

**The Weave** — a synthesis across both writers' journals that surfaces shared territory, productive divergences, a thread worth pulling, and a question for both

**Session export** — full plain-text export of everything: entries, responses, harvest tags, partner entries, and the Weave

---

## How to install

1. Download or clone this repository
2. In Claude.ai, open or create a Project
3. Upload `SKILL.md` and the `references/` folder to the Project
4. Start a conversation — Claude will ask for your name, your partner's name, and optional project context

Each writer installs the skill on their own device. You share entries via any external doc (Google Doc, Notion, etc.).

---

## How it works

```
Writer A (their device)          Writer B (their device)
       │                                  │
  Thinking Garden                   Thinking Garden
       │                                  │
  writes entries                    writes entries
  gets responses                    gets responses
       │                                  │
       └──── shared doc (Google Doc, Notion, etc.) ────┘
                          │
              paste partner's entries
              into Partner's entries tab
                          │
                    Connect mode
                      The Weave
```

Neither writer sees the other's Claude responses unless they choose to share them via the external doc.

---

## Harvest tags

After every response, Claude suggests tags for the entry:

```
TAGS: type=[value] | theme=[2-4 words] | seed=[value]
```

**Tag types:** scene, image, theme, question, fragment, insight, memory, tension

**Format seeds:** essay, scene, list, letter, lyric essay, braided narrative, prose poem, dialogue, inventory

The harvest library is the long game — how a journal becomes material.

---

## Philosophy

Most writing tools optimize for output. Thinking Garden optimizes for the quality of attention.

The entry doesn't have to go anywhere. The question doesn't have to be answered. The Weave doesn't have to lead to a project. Two people writing in parallel, finding what connects them — that's enough.

---

## File structure

```
thinking-garden/
  SKILL.md                        ← identity, setup, load order, core workflow
  references/
    modes.md                      ← Reflect, Question, Synthesize, Connect behavior
    harvest.md                    ← tag types, confirmation, library view
    connect-weave.md              ← Connect mode + Weave spec
    export.md                     ← copy blocks, sharing flow, session export
    example-responses.md          ← voice calibration with worked examples
```

---

## License

CC BY-NC 4.0 — free to use and adapt with attribution. Not for commercial use without permission.

For licensing inquiries: marah.rosenberg+liminalskill@gmail.com
---

## About Liminal Living

Liminal Living is a practice of presence built on treating human capacity as the core system rather than a variable to manage around. We work at the intersection of organizational dynamics, grief literacy, and systems thinking.

