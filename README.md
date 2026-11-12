# Google Reviews Analysis

A structured starting point for analysing a Google review dataset. The repo holds the structure only: no data and no analysis code yet.

## Start here

1. Fill in `docs/question.md`: what you are asking, for whom, and what "done" means.
2. Put the dataset in `data/raw/` and record its source in `data/README.md`.
3. Fill in `docs/data_dictionary.md` from the actual file, not from memory.
4. Write the steps in `docs/analysis_plan.md`.
5. Work through the plan. Log each analytic choice in `DECISIONS.md` before coding it.
6. Record results in `docs/findings.md` as you go.

## Layout

```
.
├── CLAUDE.md              Rules Claude follows in this repo
├── DECISIONS.md           Log of analytic choices
├── docs/
│   ├── question.md        The question and definition of done
│   ├── data_dictionary.md Columns, types, known problems
│   ├── analysis_plan.md   Ordered steps and status
│   └── findings.md        Results, traced to code and decisions
├── data/
│   ├── raw/               Original files, never edited
│   ├── interim/           Partly cleaned
│   └── processed/         Analysis-ready
├── notebooks/             Numbered notebooks
├── src/                   Reusable code
├── outputs/
│   ├── figures/
│   └── tables/
└── reports/               Final write-up or slides
```

## Setup

```
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
