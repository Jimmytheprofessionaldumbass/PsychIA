# Psych IA — Discussion: worked example sentences

**Why this file exists.** `discussion-scaffold.md` says *what* the three required parts are. This file gives
worked **shapes of sentences** for each, built only from material already in `main.tex` — so writing the
section becomes adapting prose rather than starting from a blank page.

**Nothing here is his data.** He has not collected any, and the guide asks for *potential* findings, so every
claim below is conditional by construction. Take a shape, put his content in it, and check each factual
claim is one he would defend out loud.

**Source of the requirements:** 2027 Psychology guide pp. 62–63, read 2026-10-22.

---

## Part 1 — Potential findings and implications for policy/practice

### 1a. What each outcome would look like (≈1 paragraph)

The point of this paragraph is to show the examiner that the measure can *distinguish* outcomes — not to
predict which one will happen.

> Three patterns are possible in the data. If perceived control raises flow, participants in the
> high-control condition would score higher on the absorption and timelessness items of the FRS-10 while
> reporting *lower* effort — the three components would move in different directions, not together. If
> perceived control is irrelevant to flow, the component scores would be indistinguishable between
> conditions and any differences would fall inside the between-participant spread. A third pattern is worth
> naming because it is the one the challenge–skill model predicts: if raising control also lowers the
> perceived challenge of the task, flow could *fall*, producing an inverted relationship rather than a flat
> one. Distinguishing the second pattern from the third is why the component scores are reported separately
> rather than as a single total.

**Why this earns marks:** it specifies what evidence would look like for each outcome, which is the
difference between a proposal that can be tested and one that can only be described.

### 1b. Connecting to the two studies already cited (≈1 paragraph)

> Both sources this proposal builds on treat flow as a state with separable components rather than a single
> quantity. \textcite{AINLEY2008109} operationalise it through absorption, timelessness and effort precisely
> because the preconditions (such as challenge–skill balance) cannot be observed directly in a classroom;
> \textcite{Mazid2024} frames the same state as the outcome of an optimal learning schedule. Placing
> perceived control alongside the challenge–skill balance therefore tests something neither source settles:
> whether control acts on flow independently of challenge, or only through it. If the effect disappears
> once challenge is held constant, the practical implication is that control is not a lever in its own
> right — which would be a negative result with a clear interpretation, not a failed study.

### 1c. Policy and practice (≈1 paragraph)

His own note in the file already points this way ("how it can potentially be used for making policies of the
school"). Small and concrete scores better than grand.

> If the expected relationship holds, the practical implication is small-scale and specific: a school could
> let students choose the conditions of a task — order, seating, whether to use their own device — without
> changing the task itself, and treat that choice as a low-cost intervention on engagement rather than a
> reward. The caution matters as much as the recommendation. Flow is a self-reported state, so a school
> should not convert it into a compliance metric: if students learn that reporting high absorption is
> rewarded, the measure stops measuring absorption. Any policy use should also be checked against the
> possibility in 1a — that increasing control reduces the perceived challenge enough to lower flow — which
> is why the challenge level has to be held constant rather than left to the student.

---

## Part 2 — Researcher bias (three paragraphs, one per guide question)

The guide asks three distinct questions. Cover all three rather than one at length — and the mitigation
matters less than what limitation *remains* after it.

### 2a. Personal history

> This topic came out of my own experience of losing and recovering focus while studying, and of noticing
> that the language of "flow" and being "locked in" had become ordinary among students my age. That is a
> reason to be interested, but it is also a reason to expect a particular answer: having found perceived
> control useful myself, I am disposed to find it useful in the data.

### 2b. Relation to participants

> The participants would be 10th-grade students at my own school, selected by opportunity sampling from
> humanities classes. I am older than them, I know some of them, and I would be both the researcher and a
> familiar figure in the room — which raises the likelihood of demand characteristics: participants who know
> the hypothesis may report absorption they did not experience. The sampling choice compounds this. Choosing
> 10th graders because they are, in my own words, "relatively blithe compared to us IB die-hards" is a
> judgement about a group made from outside it, and it selects for a particular relationship to academic
> work rather than sampling the population neutrally.

### 2c. Values, interpretation, and what survives the mitigation

> Confirmation bias is the specific risk: with a small sample, a difference in the expected direction is
> easy to see as support and a difference in the other direction is easy to explain away as noise. The
> mitigation is procedural — fix the scoring rule for the absorption, timelessness and effort items before
> any data are collected, and have a second person score a sample of the responses independently so the
> agreement can be reported rather than assumed. What this does not remove is the interpretive bias: I still
> choose which anomalies to discuss, and I still write the paragraph that decides whether an ambiguous result
> counts as support. The mitigation makes the bias visible; it does not make it disappear.

---

## Part 3 — One additional method

One method, one contrast, one limitation. The strongest contrast to a retrospective self-report scale is a
method that samples the state while it is happening.

> The additional method worth considering is **experience sampling**: short probes delivered during real study
> sessions, at randomised intervals, asking the same three components in two or three items each. Its value
> is that it removes the recall problem this proposal cannot avoid — a rating completed after the session
> measures memory of flow as much as flow. It would also let the relationship be examined within a person
> across time, rather than between two groups at one moment, which is closer to what the challenge–skill
> model actually claims. Its own limitation is reactivity: being interrupted to rate your concentration
> changes the concentration being rated, and at high probe frequency the effect is not small. That is why it
> complements rather than replaces a single post-session measure.

---

## Word budget

Measured: the report is **1,101 words of 2,200**, so **1,099 words remain**. The Discussion needs roughly
**600–700** of them (Part 1 ≈250, Part 2 ≈250, Part 3 ≈120), leaving ~400 to strengthen the Methodology —
which currently reads thin, especially the sampling justification.

Do not spend the whole headroom on the Discussion: the guide assesses the whole report, and an unbalanced
proposal with a long discussion and a thin method reads worse than a proportionate one.

## Checks before this goes into `main.tex`

- [ ] Every claim about findings is **conditional** — nothing says data were collected.
- [ ] All three bias questions are answered separately.
- [ ] Exactly **one** additional method, with its limitation.
- [ ] Policy paragraph names a caution as well as a recommendation.
- [ ] Word count re-measured afterwards (`tools/submission-check.py`).

## What I did not do

I did not write this into `main.tex`. The personal-history paragraph in particular has to be true for him —
it is the one part of the Discussion an examiner can tell is borrowed.
