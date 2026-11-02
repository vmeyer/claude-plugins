# vmeyer-plugins

Claude Code plugin marketplace by Volker Meyer.

## Installation

```
/plugin marketplace add vmeyer/claude-plugins
```

## Available Plugins

### research-toolkit

Multi-agent, evidence-grade research pipeline with parallel web research, triangulation, and a machine-readable evidence contract (claims + sources). Two dials — `depth` and `assurance` — add an optional blocking evidence gate, rework loop, and final critic; runs are persisted and resumable.

**Install:**
```
/plugin install research-toolkit@vmeyer-plugins
```

**Skills:**
- `/research-toolkit:research-and-summarize` — Full research pipeline
- `/research-toolkit:research-dashboard` — Aggregate HTML reports into dashboard

[View on GitHub](https://github.com/vmeyer/research-toolkit)

### diagram-skills

Create beautiful dark-mode diagrams as Excalidraw JSON or HTML/CSS. Visual argument diagrams with hand-drawn aesthetics, automatic PNG rendering, and shared brand palette.

**Install:**
```
/plugin install diagram-skills@vmeyer-plugins
```

**Skills:**
- `/diagram-skills:excalidraw-diagram` — Generate `.excalidraw` JSON files with hand-drawn aesthetics
- `/diagram-skills:html-diagram` — Generate standalone `.html` diagram files with clean CSS layouts

[View on GitHub](https://github.com/vmeyer/diagram-skills)

### powerpoint-skills

Design PowerPoint slides or whole decks as native, editable shapes, with or without your master: built in a working copy, checked and rendered to PNG before you see it, and refined from your feedback. Renders with PowerPoint on macOS when installed, LibreOffice otherwise.

**Install:**
```
/plugin install powerpoint-skills@vmeyer-plugins
```

**Skills:**
- `/powerpoint-skills:slide-design` — Build or revise a single slide or a whole deck, with or without a master
- `/powerpoint-skills:deck-storyline` — Plan a deck's outline as a storyline of action titles

[View on GitHub](https://github.com/vmeyer/powerpoint-skills)
