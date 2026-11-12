# Decision log

Every choice that could change a result is recorded here before the code is written. A reader should be able to see what was chosen, what else was possible, and why.

## How to add an entry

Copy the template, give it the next ID, and fill in every field. Entries are never deleted. If a decision changes, add a new entry and mark the old one `Superseded by D-0XX`.

```
## D-000: Short title of the decision

- Date: YYYY-MM-DD
- Status: Proposed | Accepted | Superseded by D-0XX
- Plan step: the step in docs/analysis_plan.md this belongs to

**Context.** What forced a choice? What did you see in the data?

**Options considered.**
1. Option A: what it is, what it costs
2. Option B: what it is, what it costs

**Decision.** The option chosen.

**Why.** The reason, in one or two sentences.

**Effect on results.** Rows or groups affected, and how a reader should
interpret findings differently because of this choice.
```

## Open questions

Choices this project will probably have to make. Move each one into a numbered entry when it is decided, and delete any that turn out not to apply.

- Unit of analysis: the review, the business, or the reviewer?
- Reviews with a star rating but no text: keep, drop, or analyse separately?
- Duplicate reviews: how is a duplicate defined, and which copy is kept?
- Languages: all reviews, or only one language? How is language detected?
- Time window: all dates, or a fixed period?
- Businesses with very few reviews: is there a minimum count for inclusion?
- Owner responses: used in the analysis or ignored?
- Star ratings: treated as a number (averages) or as ordered categories?

## Decisions

<!-- Add entries below, newest last. -->
