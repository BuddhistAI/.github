# BuddhistAI

Open agent skills and benchmarks for working with Buddhist texts, shared by Buddhist organizations.

BuddhistAI is a neutral home. Any group working on Buddhist texts in any language is welcome to use, test, and improve what is here. WeBuddhist started it; it belongs to everyone who takes part.

## What's here

**[buddhist-skills](https://github.com/BuddhistAI/buddhist-skills)** holds agent skills, one language per skill, written by people who know that language. Skills are named `<task>-<language>`, for example `toc-extraction-tibetan` or `translation-tibetan-to-english`. Each one is the current winner on its benchmark.

**[buddhist-benchmarks](https://github.com/BuddhistAI/buddhist-benchmarks)** defines each task once (`tasks/<task>/`), with test data per language, one shared scorer, and a leaderboard. Better challengers replace the current skill.

Tasks include:

- text-translation alignment
- text-commentary alignment
- text cleanup
- table-of-contents extraction
- entity extraction
- citation mapping
- translation, in stages

## Install

Claude Code, one plugin per language:

```bash
claude plugin marketplace add BuddhistAI/buddhist-skills
claude plugin install buddhist-skills-tibetan@buddhistai   # or -pali, -sanskrit, -classical-chinese, ...
```

Any other agent: `npx skills add BuddhistAI/buddhist-skills`

See the [buddhist-skills README](https://github.com/BuddhistAI/buddhist-skills#readme) for details.

## Contribute

Add test data in your language, propose a new task, or submit a challenger skill and let the benchmark decide. Start with [CONTRIBUTING.md](https://github.com/BuddhistAI/buddhist-skills/blob/main/CONTRIBUTING.md).

Everything here is MIT licensed.
