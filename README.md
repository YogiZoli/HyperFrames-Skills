# HyperFrames Skills

Zoltan Gero HyperFrames videógyártási skilljei, verziózva.

Húsz skill, a teljes pipeline-tudás: a belépési ponttól (`hyperframes`) a
kompozíció szerződésén (`hyperframes-core`), a mozgásrendszeren
(`hyperframes-animation`, `hyperframes-keyframes`) és a médiabeszerzésen
(`media-use`) át a kész műfajokig (`product-launch-video`,
`faceless-explainer`, `motion-graphics`, `music-to-video` és a többi).

2026-09-23-án derült ki, hogy ezekről **sehol nem volt másolat**. 18 MB, 897
fájl, csak a gép merevlemezén. Ez a repo ezt orvosolja.

## Telepítés egy gépre

A skillek helye:

```text
macOS:   ~/.claude/skills/
Windows: C:/Users/<neved>/.claude/skills/
```

Klónozd ide a repo tartalmát, és a Claude a következő indításkor látja őket.

```bash
git clone https://github.com/YogiZoli/HyperFrames-Skills.git ~/.claude/skills
```

Ha már van ott valami, előbb tedd félre.

## A húsz skill

| Skill | Mire való |
|---|---|
| `hyperframes` | **a belépési pont**, minden videós kérés innen indul |
| `hyperframes-core` | a kompozíció szerződése, `data-*` időzítés, sávok |
| `hyperframes-animation` | mozgásszabályok, jelenet-tervrajzok, hét futtatókörnyezet |
| `hyperframes-keyframes` | seek-biztos 2D/3D kulcskockák, GSAP, SVG morph |
| `hyperframes-creative` | design spec, paletta, tipográfia, narráció, beat-terv |
| `hyperframes-cli` | a fejlesztői ciklus, render, publikálás, diagnosztika |
| `hyperframes-audio` | keverés, voiceover-kivágás, effektek, automatizálás |
| `hyperframes-registry` | blokkok és komponensek telepítése, bekötése |
| `media-use` | zene, hang, kép, ikon, logó, hang, LUT beszerzése |
| `product-launch-video` | termékbemutató, promó, funkció-leleplezés |
| `faceless-explainer` | arc nélküli magyarázó videó szövegből |
| `motion-graphics` | rövid, design-vezérelt mozgókép, kinetikus tipográfia |
| `music-to-video` | zenére vágott videó, lyric video, beat-szinkron |
| `general-video` | egyedi kompozíció, ha semmi más nem illik |
| `embedded-captions` | feliratok meglévő beszélőfejes videóra |
| `talking-head-recut` | grafikus overlay kártyák interjúra, podcastra |
| `pr-to-video` | GitHub pull requestből kódváltozás-magyarázó |
| `slideshow` | prezentáció, pitch deck, interaktív dia |
| `figma` | Figma tartalom behozatala kompozícióba |
| `remotion-to-hyperframes` | meglévő Remotion forrás átültetése |

## Kapcsolódó repók

```text
brand-frames      a HyperFrames kánon: PIPELINE.md, MOTION.md, FRAME.md
claude-setup      a Claude gép-szintű beállításai (CLAUDE.md, memória, eszközök)
```

A `brand-frames` a `~/HyperFrames/_frames` alatt él, és **a kánon ott van, nem
itt**. Ezek a skillek a hogyan, az a mit és a miért.
