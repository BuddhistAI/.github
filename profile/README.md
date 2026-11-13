# BuddhistAI

Open AI skills and benchmarks for Buddhist texts, built together by Buddhist organizations. Everything is MIT licensed. Founded by [WeBuddhist](https://webuddhist.com).

**[Leaderboard](https://buddhistai.github.io/buddhist-benchmarks/)** · **[Hugging Face](https://huggingface.co/BuddhistAI)** · **[Forum](https://forum.webuddhist.com/c/wg/ai-wg/36)** · **[Discord](https://discord.com/invite/7GFpPFSTeA)** · **[WeBuddhist](https://webuddhist.com)**

## Start here

**I translate or run a text project.**
Check the [leaderboard](https://buddhistai.github.io/buddhist-benchmarks/) for the best skill and model for your task and language ("Best overall" and "Best value"), then install the skills for your language from [buddhist-skills](https://github.com/BuddhistAI/buddhist-skills#install):

```bash
claude plugin marketplace add BuddhistAI/buddhist-skills
claude plugin install buddhist-skills-tibetan@buddhistai   # or -pali, -sanskrit, -classical-chinese, ...
```

**I want to build a better skill or add test data.**
See how a skill is developed in a workshop repo like [toc-extraction-tibetan](https://github.com/BuddhistAI/toc-extraction-tibetan), then score it on [buddhist-benchmarks](https://github.com/BuddhistAI/buddhist-benchmarks#scoring-a-skill). To add a test set for your language, follow [its contributing guide](https://github.com/BuddhistAI/buddhist-benchmarks/blob/main/CONTRIBUTING.md). The leaderboard winner ships in buddhist-skills.

**I represent a tradition, monastery, shedra or university.**
Help [BuddhistBench](https://github.com/BuddhistAI/buddhist-bench) test how well AI knows your tradition: share [exam papers](https://github.com/BuddhistAI/buddhist-bench/blob/main/docs/exams.md) (with permission) or write and review expert questions ([how](https://github.com/BuddhistAI/buddhist-bench/blob/main/CONTRIBUTING.md)).

**I do research.**
Plans, logs and reports for every experiment are in [research](https://github.com/BuddhistAI/research).

## Repositories

| Repo | What it holds |
| --- | --- |
| [buddhist-skills](https://github.com/BuddhistAI/buddhist-skills) | The best skill for each task and language, ready to install, one plugin per language |
| [buddhist-benchmarks](https://github.com/BuddhistAI/buddhist-benchmarks) | Test sets (standard JSONL), scorers and the [live leaderboard](https://buddhistai.github.io/buddhist-benchmarks/) for skills |
| [buddhist-bench](https://github.com/BuddhistAI/buddhist-bench) | BuddhistBench: questions that rank AI models on Buddhist knowledge, across traditions and languages |
| [toc-extraction-tibetan](https://github.com/BuddhistAI/toc-extraction-tibetan) | Workshop for one skill: variants, runs and the ranking report |
| [research](https://github.com/BuddhistAI/research) | Experiment plans and reports |

## Links

- **Leaderboard:** [buddhistai.github.io/buddhist-benchmarks](https://buddhistai.github.io/buddhist-benchmarks/), the best skill and model for each task and language
- **Datasets:** [huggingface.co/BuddhistAI](https://huggingface.co/BuddhistAI)
- **Buddhist AI Studio:** [buddhistai.tools](https://buddhistai.tools/), WeBuddhist's AI tools for translating and annotating texts
- **Talk to us:** the [AI Tools working group](https://forum.webuddhist.com/c/wg/ai-wg/36) on the WeBuddhist forum, where experiment reports are posted, or [Discord](https://discord.com/invite/7GFpPFSTeA). For a bug or idea about one repo, open an issue there.
- **WeBuddhist:** [webuddhist.com](https://webuddhist.com)
