# Adam Wei

**Data Technician apprentice (Level 3) · Liverpool, UK · working towards Data Analyst**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Adam%20Wei-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adamwei)
[![Build log](https://img.shields.io/badge/Build%20log-read%20the%20write--ups-24292f?logo=github)](https://github.com/adamwei2009-design/build-log)
[![tests](https://github.com/adamwei2009-design/build-log/actions/workflows/tests.yml/badge.svg)](https://github.com/adamwei2009-design/build-log/actions)

I work on AI and automation for a small UK home-services company, alongside a Level 3 Data Technician apprenticeship with NowSkills. I look for places where work gets lost or slowed down, map how the process really flows, set the rules for a fix and test it before anything goes live.

## What's here, and what isn't

- ✅ **Real projects, written up honestly.** Each one says whether it's live or still in testing.
- ✅ **Fake data only.** No customer details, company names, internal links or keys are ever published. Every file passes my [upload safety check](https://github.com/adamwei2009-design/build-log/tree/main/tools) before it's pushed.
- ✅ **Honest about AI.** I design the process, set the rules, test it and decide what goes live. AI tools help me write code and challenge my work. I say which is which.
- ❌ I'm not selling anything, and I'll never ask you to download or pay for something.

## How I work

```mermaid
flowchart LR
  A[Spot where time leaks] --> B[Map the real process]
  B --> C[Set the rules]
  C --> D[Build with AI help]
  D --> E[Second AI challenges it]
  E --> F[Test with fake data]
  F --> G{My go?}
  G -- yes --> H[Live, with an undo]
  G -- no --> C
  H --> I[Daily check: did anything slip?]
```

## Data analysis

**[How homes are heated: Census 2021](https://github.com/adamwei2009-design/build-log/tree/main/analysis/home-heating-census)**: real published data for 24.8 million households in England and Wales, from the Office for National Statistics.

- **Checked first:** every area adds up, and my figures match what ONS published.
- **SQL:** 6 questions, each answered a second way in Python so the two must match.
- **Honest about limits:** two totals differ by 30 households, and I say so instead of hiding it.

[![Mains gas by region](https://raw.githubusercontent.com/adamwei2009-design/build-log/main/analysis/home-heating-census/chart2_gas_by_region.png)](https://github.com/adamwei2009-design/build-log/tree/main/analysis/home-heating-census)

Source: ONS, Census 2021, table TS046. Open Government Licence v3.0.

**[Service jobs analysis](https://github.com/adamwei2009-design/build-log/tree/main/analysis/service-jobs)**: one year of made-up service jobs, taken from a messy export to findings in 4 stages.

- **Clean:** duplicates, test rows and mixed date formats fixed in Python, with row counts before and after every step.
- **SQL:** 5 business questions, each answered a second way in Python so the two must match.
- **Charts:** titles that state the answer, and tests that fail if a title stops being true.
- **Findings:** a statistical test flagged the wrong engineer, so I show why you check before you blame.
- **Power BI:** the same data as a [one-page dashboard](https://github.com/adamwei2009-design/build-log/tree/main/analysis/service-jobs/powerbi), with DAX measures and every card checked against the SQL.

[![Repair waits are longer in winter](https://raw.githubusercontent.com/adamwei2009-design/build-log/main/analysis/service-jobs/stage3-charts/chart2_repair_wait.png)](https://github.com/adamwei2009-design/build-log/tree/main/analysis/service-jobs)

The data in this second project is made up. The method is real.

## Selected builds

| Build | Status | What it shows |
|---|---|---|
| [Enquiry auto-reply](https://github.com/adamwei2009-design/build-log/blob/main/builds/01-enquiry-auto-reply.md) | Live | Process design, routing rules, a daily "nothing slipped" check |
| [WhatsApp quote journey](https://github.com/adamwei2009-design/build-log/blob/main/builds/02-whatsapp-quote-journey.md) | Live | API integration; first reply cut from about 2m40s to 27s in testing |
| [The monthly review that adds up](https://github.com/adamwei2009-design/build-log/blob/main/builds/monthly-review.md) | Live | Reporting: every total is checked against the raw rows before it is shown |
| [Upload safety check](https://github.com/adamwei2009-design/build-log/tree/main/tools) | In use | Python: blocks secrets and personal data before anything goes public |
| [Working examples with tests](https://github.com/adamwei2009-design/build-log/tree/main/examples) | 10 tests passing | Python: merging repeat alerts, routing by context, a safe delete gate, cleaning image metadata |

More are added as I write them up. Full list: [build-log](https://github.com/adamwei2009-design/build-log).

## Skills

**Using now:** Excel · Power Query · Google Sheets · Zapier · Cloudflare Workers · Python (with pytest) · Process mapping (Lucidchart) · Claude and ChatGPT
**Learning:** SQL · Power BI

## Learning

- Level 3 Data Technician apprenticeship (NowSkills), in progress
- LinkedIn Learning: Learning Data Analytics 1: Foundations (completed May 2026)
- Current focus: checking data before trusting it (row counts, raw-data checks, spotting the mistake), Power Query, SQL

📫 The best way to reach me is a message on [LinkedIn](https://www.linkedin.com/in/adamwei).
