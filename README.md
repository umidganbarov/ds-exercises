# DS Exercises

A running log of data science practice — scripts, dataset drills, and model
experiments from my learning path. This is a working log, not a portfolio;
for finished, write-up'd projects, see [<link to your portfolio repo>].

## What's here

Exercises are organized loosely by topic or dataset. Each script is
self-contained and runnable on its own — no shared setup required beyond
the dependencies listed below.

```
├── pandas/          # data cleaning, merging, apply, datetime handling
├── sklearn/          # pipelines, model comparison, cross-validation
└── ...
```

## Why this exists

- Keeps a version history of how I was solving problems at a given point,
  so I can look back and see progress.
- Separates practice/throwaway work from my actual portfolio, so that repo
  stays focused on finished, presentable projects.

## Setup

```bash
pip install -r requirements.txt
```

## Notes

Code here prioritizes speed of iteration over polish — expect minimal
comments, no tests, and scripts that assume a specific dataset is present
locally. Datasets used are mostly from Kaggle and aren't committed to the
repo; each script notes which dataset it expects.
