# 2D Documentary Skill

A Claude skill that produces a finished 16:9 stick-figure documentary video in code: researched title ideas, length, script, voice-over sync, character sheets, visual beats and a rendered MP4. 2D characters live in Three.js 3D sets filmed by a floating camera.

The skill itself is in [`skills/2d-documentory-skill/SKILL.md`](skills/2d-documentory-skill/SKILL.md).

## Install

**As a Claude Code plugin**

```
/plugin marketplace add swarnavo09/2d-documentary-skill
/plugin install 2d-documentary-skill@2d-documentary-skill
```

**As a personal skill**

```
git clone https://github.com/swarnavo09/2d-documentary-skill
cp -r 2d-documentary-skill/skills/2d-documentory-skill ~/.claude/skills/
```

**On claude.ai**: zip the `skills/2d-documentory-skill` folder and upload it under Settings → Capabilities → Skills.

## Use

Ask for a documentary or business/news explainer video, title ideas or a script, e.g. "Make me a 3-minute documentary about the biggest IPO flop of the year."
