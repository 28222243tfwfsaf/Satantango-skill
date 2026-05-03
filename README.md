# Satantango Skill

> A Claude Code skill that enables any LLM to write in the style of László Krasznahorkai's *Satantango* — with dramatically higher information density and reading efficiency.
>
> *Satantango* is the masterwork of **László Krasznahorkai, winner of the 2025 Nobel Prize in Literature**.
>
> [中文说明](README.zh-CN.md)

## Install

```bash
mkdir -p ~/.claude/skills/satantango
curl -o ~/.claude/skills/satantango/SKILL.md \
    https://raw.githubusercontent.com/28222243tfwfsaf/satantango-skill/main/satantango.md
```

That's it. Type `/satantango` in Claude Code to activate. The skill is **off by default** — it only affects conversations where you explicitly invoke it.

## Why This Skill

Most writing advice tells you to use short sentences. This is wrong — for information delivery. Short sentences waste words rebuilding context at every period. Each new sentence forces the reader to re-establish who is speaking, where they are, and what frame they're in.

Krasznahorkai's long-sentence technique solves this:

- **One frame, many data points.** Build the scaffolding once. Accumulate. No redundant subject-verb reconstructions.
- **Parataxis compresses.** Juxtaposed clauses carry more information per word than separated sentences.
- **No micro-reorientations.** The reader stays inside the consciousness. Every period is a wall — the reader must climb over it and re-locate.
- **Simultaneity preserved.** Physical detail, psychological state, and philosophical claim coexist in syntax, just as they do in reality.
- **Breath is the natural unit of thought.** We don't think in periods. We think in clauses, turns, self-revisions. The prose reproduces a mind working.

The result: **higher information density per sentence, faster reading comprehension, less cognitive overhead.**

## What This Is

A pure text-based writing instruction set — not an app, not an API, not a library. Based on deep bilingual analysis of the English translation (George Szirtes) and the Chinese translation (余泽民, Yilin Press, 2017). Contains no copyrighted text — this is original writing craft analysis.

## License

MIT — see [LICENSE](LICENSE).

## Credits

Analysis based on:
- *Sátántangó* by Krasznahorkai László (1985)
- English translation *Satantango* by George Szirtes (New Directions, 2012)
- Chinese translation《撒旦探戈》by 余泽民 (译林出版社, 2017)
