# AP World History: Modern — Study Vault

A structured Obsidian knowledge base, slide deck collection, and Cornell Notes library for the **AMSCO *AP World History: Modern*** textbook. Each chapter gets its own folder with seven interlinked Markdown notes, a chapter slide deck, and a Cornell Notes PDF for active recall practice.

---

## Using This Vault

**Obsidian** is the recommended way to read these notes. Open the root of this folder as your vault — the `[[wikilinks]]` between files will become a navigable graph, and the `#tags`, callout blocks, and YAML frontmatter will all render correctly.

If you don't have Obsidian: the `.md` files are plain Markdown and readable in any editor, GitHub, or VS Code.

**Slides** (`.pptx`) open in PowerPoint, Keynote (via import), or Google Slides. They're designed for review sessions, not just passive reading — use them to quiz yourself on the visuals.

**Cornell Notes PDFs** follow the classic Cornell method: cue questions on the left, detailed notes on the right, and a blank summary strip at the bottom you fill in yourself after reviewing each page.

---

## Vault Structure

```
AP World History Study/
├── Unit-1-Overview.md        ← Unit 1 synthesis hub (start here for exam review)
├── Unit1-Review.pptx         ← 20-slide consolidated Unit 1 review deck
│
├── Unit-1-Ch-1/              ← Developments in East Asia
├── Unit-1-Ch-2/              ← Developments in Dar al-Islam
├── Unit-1-Ch-3/              ← Developments in South & Southeast Asia
├── Unit-1-Ch-4/              ← State Building in Africa
├── Unit-1-Ch-5/              ← State Building in the Americas
├── Unit-1-Ch-6/              ← Developments in Europe
└── ...                       ← Future units added here
```

Each chapter folder contains:

| File | Contents |
|------|----------|
| `00-Overview.md` | Chapter summary, AMSCO learning objectives, AP key concepts, and thematic preview |
| `01-Key-Terms.md` | 15–25 vocabulary terms with definitions, historical significance, and `[[wikilinks]]` |
| `02-Key-People-and-Groups.md` | Key individuals, civilizations, and movements — focused on causation and AP impact, not biography |
| `03-Themes-and-Causation.md` | Content analyzed through AP's six thematic lenses with explicit cause-and-effect chains |
| `04-Timeline.md` | Chronological table of 10–20 events with continuity vs. change annotations |
| `05-Practice-Questions.md` | 10 AP-style MCQs (with answers + explanations), 2 SAQ prompts, and 1 DBQ outline |
| `06-Connections.md` | Cross-chapter `[[wikilinks]]` — what this chapter builds on, what it sets up, and comparative civilizations |
| `ChN-Title.pptx` | 15-slide visual presentation covering all major topics in the chapter |
| `ChN-Cornell-Notes.pdf` | 7-page Cornell Notes PDF for active recall practice |

---

## AP Exam Callouts

Every note uses Obsidian callout blocks to flag exam-relevant content:

```
> [!exam-tip]
> Content that appears frequently on the AP exam.

> [!tip]
> Study strategies and connections to watch for.

> [!warning]
> Common misconceptions or oversimplifications to avoid.
```

---

## How to Study With This

**Suggested study flow for each chapter:**

1. **Cornell Notes PDF first** — read through the pre-filled cues and notes, then cover the right column and self-quiz using the cue questions. Write your own summary in the blank strip at the bottom of each page.
2. **Chapter slides** — use the `.pptx` to do a fast visual pass; each slide is a testable concept cluster.
3. **Obsidian notes** — dive into `03-Themes-and-Causation.md` for causation depth, and attempt the essay prompts in `05-Practice-Questions.md` before reading the guidance.
4. **`06-Connections.md`** — after finishing a chapter, review how it links forward and backward. This is the key to long-essay complexity points.

**For unit-level exam review:**

- Open `Unit-1-Overview.md` as a synthesis hub — it has comparison tables, causation chains, and AP essay traps all in one place.
- Run through `Unit1-Review.pptx` slide by slide; cover the content on each card and try to reconstruct it from memory before reading.

**Graph view in Obsidian** — once you have multiple chapters loaded, the `[[wikilinks]]` in `06-Connections.md` will create a visual map of how concepts connect across the course. This is especially useful for spotting the cross-regional comparison patterns the AP exam loves.

---

## Coverage

| Unit | Period | Chapters | Status |
|------|--------|----------|--------|
| Unit 1: The Global Tapestry | c. 1200–1450 | Ch 1–6 | ✅ Complete — notes, slides, Cornell PDFs, overview, unit review deck |
| Unit 2: Networks of Exchange | c. 1200–1450 | — | Coming soon |
| Unit 3: Land-Based Empires | c. 1450–1750 | — | Coming soon |
| Unit 4: Transoceanic Interconnections | c. 1450–1750 | — | Coming soon |
| Unit 5: Revolutions | c. 1750–1900 | — | Coming soon |
| Unit 6: Consequences of Industrialization | c. 1750–1900 | — | Coming soon |
| Unit 7: Global Conflict | c. 1900–present | — | Coming soon |
| Unit 8: Cold War and Decolonization | c. 1900–present | — | Coming soon |
| Unit 9: Globalization | c. 1900–present | — | Coming soon |

---

## `.gitignore` Suggestion

If you want to keep the repo clean, add a `.gitignore` with:

```
.DS_Store
.obsidian/workspace.json
.obsidian/workspace-mobile.json
```

The rest of `.obsidian/` (themes, graph settings, plugins) is worth committing so your setup is reproducible.
