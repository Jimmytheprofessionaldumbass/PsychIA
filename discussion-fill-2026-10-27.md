# Psych IA Discussion — fill sheet

**Section:** `~/PsychIA/main.tex`, `\section{Discussion}` — currently **0 words of prose**, only `%` comments.
This is the last empty section in any of the five documents.

**Report cap:** 2,200 words. **Current body:** 1,100, so **1,100 words of headroom**.
Allocate **500–600** here and keep ~500 for strengthening the tool and sampling sections, which read thin.

Everything below is a **question to answer and a budget** — not prose to paste. The guide's three parts are
all mandatory.

---

## Part 1 — Potential findings and implications (≈180 words, 3 paragraphs)

| ¶ | Words | The question |
|---|---|---|
| 1 | 60 | What would each *outcome* look like in your measurement? Three cases: perceived control raises the flow score, no relationship, or an inverted one (too much control removes challenge). Name what the **absorption / timelessness / effort** ratings would look like in each case — not "it would be higher". |
| 2 | 60 | Where does that sit against `Mazid2024`, `AINLEY2008109` and the challenge–skill model already in your introduction? If control raises flow *only when challenge is held constant*, that is a boundary condition — say it. |
| 3 | 60 | What could a school actually change? One small, concrete practice (letting students choose task difficulty or working conditions) beats a grand one. And one caution: flow should not become a compliance metric. |

**Trap:** every sentence conditional. You have not collected data, and the guide asks for *potential*
findings — a sentence that reads as a result is a fabrication.

## Part 2 — Researcher bias (≈180 words, 3 paragraphs — one per guide question)

The guide asks **three separate questions**; do not merge them into one paragraph about "bias".

| ¶ | Words | The question |
|---|---|---|
| 1 | 60 | **Personal history** — why flow, why this population? You are an IB student writing about students' focus. That is the motivation and the risk. |
| 2 | 60 | **Relation to participants** — opportunity sample of 10th-graders at your own school, picked by humanities grades; you are older than them. Your own comment ("relatively blithe compared to us IB die-hards") is, in academic terms, **sampling bias**. |
| 3 | 60 | **Values and interpretation** — confirmation bias (you expect control to matter). Name one precaution (pre-register the scoring rule before collecting; second rater on a sample) and then the limitation that **remains after** it. The guide's wording is "how might it still affect the investigation even after that precaution", so a mitigation with no residual limitation does not answer it. |

## Part 3 — One additional method (≈120 words, 1–2 paragraphs)

Pick **one**: experience sampling (short repeated probes during real study sessions) or a qualitative
interview. Say what it reveals that your rating scale cannot — *why* control felt absent, not just that the
score was low — then its own limitation (reactivity; or that it cannot compare magnitudes across people).

**Trap:** the guide says one method. A second one costs marks rather than adding them.

---

## Order to write it in

1. **Part 2 first.** It is the part with the most material already sitting in your own comments, and it needs
   no experiment.
2. **Part 3 second** — it is short and mechanical once you have chosen the method.
3. **Part 1 last.** It is the one most likely to drift into invented results, so write it when the other two
   are done and the section already sounds like you.

## After writing

```
python3 ~/.openclaw/workspace/tools/empty-sections.py ~/PsychIA/main.tex
python3 ~/.openclaw/workspace/tools/submission-check.py
```

The first should stop reporting `Discussion 0 words`. The second confirms you stayed under 2,200.

## Still open elsewhere in this file

- The data collection tool (FRS-10, 10 items) exists as a draft in `data-collection-tool-draft.md` but is
  **not yet in the appendix**, and the guide requires the complete tool there.
- Title page: student code and submission date are still blank rules.