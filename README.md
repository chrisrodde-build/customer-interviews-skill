# Customer Interviews — a Claude skill

A B2B customer interview skill for marketers. It plans, runs, scores and synthesizes best-customer (switch), win-loss and churn interviews, built on the published methods of four practitioners who each cover the others' blind spots. It turns a decision into the right participants, the participants into real stories, and the stories into findings that change something.

**Most interview programs fail in one of three places:** they talk to the wrong people, they ask questions people can't answer truthfully, or the findings never become a decision. The sequence exists to prevent all three.

| Step | Question | Output |
|---|---|---|
| 1. Decide | What decision will this research inform? | Research brief |
| 2. Select | Who has the evidence, and how do we reach them? | Participant criteria, screener, invite |
| 3. Design | What story do we collect to answer our research questions? | Interview guide |
| 4. Run | Are we getting real stories, or polite opinions? | Recordings, transcripts |
| 5. Score | Was each interview reliable, and what did it say? | Quality score, coded transcript, snapshot |
| 6. Synthesize | What patterns hold across interviews, and what do they rule out? | Findings report or demand brief |

It includes four rubrics with anchored 1–4 scales: participant fit, guide quality, interview quality and evidence coding.

## What's in here

```
SKILL.md       the sequence, the guardrails, the output templates
references/    study design, interview guides and question banks, rubrics,
               synthesis, and the practitioners' methods in depth
```

## Works with Positioning & Messaging

This skill is the evidence engine for the [Positioning & Messaging skill](https://github.com/chrisrodde-build/positioning-and-messaging-skill). It applies Bob Moesta's Four Forces as its analysis lens (documented there in `references/moesta-demand.md`) and hands off a demand brief in the format that skill expects. Each works on its own; together they run from interviews to a messaging framework.

## How to get it

- **Download:** click the green **Code** button → **Download ZIP**.
- **Clone:** `git clone https://github.com/chrisrodde-build/customer-interviews-skill.git`

## How to use it

**Claude Code / Claude (Cowork):** put these files in a folder named `customer-interviews` inside your skills directory, so you end up with `~/.claude/skills/customer-interviews/SKILL.md`. If you downloaded the ZIP, rename the unzipped folder to `customer-interviews` and drop it in `~/.claude/skills/`. Restart your session and it triggers automatically when you describe interview work.

**Cursor or any other capable agent:** point the agent at `SKILL.md` and let it pull in the reference files as each step becomes active.

You don't invoke it by keyword. Just describe the work: *"Help me plan churn interviews,"* *"Draft a discussion guide for our best customers,"* *"Score this transcript,"* or *"Why are we losing deals to our main competitor?"*

## Attribution

This skill synthesizes publicly published methods. It is **not affiliated with, endorsed by, or reviewed by** any of the practitioners or companies named; any errors in the summaries are the skill's, not theirs. Go to the sources:

- **Georgiana Laudi & Claire Suellentrop** — *Forget the Funnel* and the Forget the Funnel podcast — [forgetthefunnel.com](https://www.forgetthefunnel.com/), [customerled.com](https://www.customerled.com/)
- **Teresa Torres** — *Continuous Discovery Habits* and the Story-Based Customer Interviews course — [producttalk.org](https://www.producttalk.org/)
- **Rob Fitzpatrick** — *The Mom Test* — [momtestbook.com](https://www.momtestbook.com/)
- **Clozd** — the Win-Loss 101 course and question framework — [clozd.com](https://www.clozd.com/)
- **Bob Moesta & Chris Spiek** — the Four Forces — [jobstobedone.org](https://jobstobedone.org/)

The sequencing, the rubrics and the output templates are how the method has been assembled here.

## License

MIT — see [LICENSE](LICENSE). Free to use, adapt, and share.

Built by Chris Rodde, [Two Spruce Partners](https://twospruce.co). If you build something with it or improve it, I'd love to hear about it.
