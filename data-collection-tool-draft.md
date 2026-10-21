# Psych IA — data collection tool (DRAFT for Jimmy to edit)

**Status: draft, not his design.** The guide requires *"one data collection tool… a minimum of five items
and a copy of the tool should be provided in the appendix"*. `main.tex` currently names the construct
(absorption / timelessness / effort, per `AINLEY2008109`) but **the tool itself does not exist anywhere in
the file**. This is a workable draft built strictly from the three components he already committed to, so
he can edit wording rather than start from a blank page.

**Verify against the guide before submitting:** the ≥5-item rule and the appendix requirement were read
from the 2027 Psychology guide, pp. 62–63.

---

## Design decisions embedded in this draft (change any of them)

| Decision | Why | If he disagrees |
|---|---|---|
| **Self-report rating scale**, 1–5 per item | Fits "a questionnaire or Likert-type scales"; can be completed immediately after a study session, so it measures *that session*, not general beliefs about flow | An observation checklist is the alternative the guide allows |
| **10 items**, 3–4 per component | Comfortably above the 5-item minimum, and lets each component carry its own sub-score | Trimming to 6–8 is fine; below 5 is not |
| **Retrospective, immediately post-task** | The guide warns against tools that only capture what students *generally believe* about flow | Experience sampling would be stronger but much heavier to run |
| **Anchored wording ("during that session")** | Forces the rating to a specific episode | — |
| **Reverse-scored item #9** | Detects straight-lining / inattention | Drop it if it confuses 10th-graders |

## The tool — Flow Rating Scale (FRS-10)

**Instructions given to the participant (read aloud, verbatim):**

> "Think about the study session you have just finished — not how you usually study, and not how you felt
> before it. For each statement, circle the number that best describes **that session**.
> 1 = not at all true, 2 = slightly true, 3 = moderately true, 4 = mostly true, 5 = completely true.
> There are no right answers and this is not a test."

### Absorption (A)

1. I was completely focused on what I was doing.
2. I lost track of things happening around me.
3. My attention did not wander to other things.
4. I would have found it hard to stop what I was doing.

### Timelessness (T)

5. Time seemed to pass differently from normal.
6. I was surprised by how much (or how little) time had passed.
7. I did not notice time passing while I worked.

### Effort (E)

8. The work felt effortless even though it was demanding.
9. I had to force myself to keep going. *(reverse-scored)*
10. Working on this felt natural rather than like hard labour.

## Scoring

- **Component scores:** A = mean of items 1–4; T = mean of items 5–7; E = mean of items 8, 10 and
  (6 − item 9).
- **Total flow score:** mean of the three component scores (each component weighted equally, so the
  3-item timelessness block is not outvoted by the 4-item absorption block).
- **Range:** 1.00–5.00. Higher = more flow.
- **Report the component scores as well as the total** — the research question is about *magnitude* of flow,
  and a total alone hides which component moved.
- **Missing data:** if a participant skips an item, use the component mean of the remaining items; if more
  than two items are missing, exclude that participant and report how many were excluded.

## Validity and reliability (the guide asks for this explicitly)

- **Face validity:** each item is worded from the published description of its component (`AINLEY2008109`),
  not invented.
- **Content validity:** all three components of his chosen classification are represented; no component is
  measured by a single item.
- **Internal consistency:** report Cronbach's α per component if the sample allows (n = 10 will not give a
  meaningful α — say so rather than quoting a number).
- **Inter-rater reliability does not apply** to a self-report scale; say that explicitly if the guide's
  generic advice mentions raters, because a marker will otherwise wonder why it is missing.
- **Known limitation to state:** self-report of flow is retrospective, so it is subject to recall bias; a
  concurrent probe would reduce it but is not feasible here.

## Appendix snippet (drop into `main.tex` before `\printbibliography`)

```latex
\appendix
\section{Appendix A: Flow Rating Scale (FRS-10)}
\label{app:frs10}

\textbf{Instructions read to each participant.} ``Think about the study session you have just
finished --- not how you usually study\ldots'' (full wording as above).

\begin{enumerate}
  \item I was completely focused on what I was doing.
  \item I lost track of things happening around me.
  \item My attention did not wander to other things.
  \item I would have found it hard to stop what I was doing.
  \item Time seemed to pass differently from normal.
  \item I was surprised by how much (or how little) time had passed.
  \item I did not notice time passing while I worked.
  \item The work felt effortless even though it was demanding.
  \item I had to force myself to keep going. (reverse-scored)
  \item Working on this felt natural rather than like hard labour.
\end{enumerate}

Each item is rated 1 (not at all true) to 5 (completely true) for the session just completed.
```

## What is still missing in `main.tex` for this section

- The prose under `\subsection{Designing the Data Collection}` names the construct but **never presents
  the tool** — the guide wants the tool described *and* appended.
- `Operationalized variables:` and `Potential speculated factors affecting it` are **bare headings with no
  content** (lines ~89–91).
- No statement of what counts as **higher vs lower** flow — the scoring section above supplies one.
- No mention of **confounding variables** (sleep, food, prior activity, time of day) even though his own
  comments list them as considerations.
