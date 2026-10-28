# Psych IA — the guide's data-collection requirements, checked line by line

Verified 2026-10-29 against `psychology-first-assessment-2027-guide-sbs.pdf` pp. 62–63, read directly.
The guide states **three** requirements under "Data collection" and **three** under "Discussion". This file
records which exist in `main.tex` and which do not — because two of them were never in my requirement list
and so were never checked.

---

## Data collection — three requirements

### 1. A tool with ≥5 items, with a copy in the appendix

Guide, verbatim: *"The data collection tool should contain a minimum of five items and a copy of the tool
should be provided in the appendix."*

| | |
|---|---|
| Tool described in the prose | **partly** — `\subsection{Designing the Data Collection}` names the construct (absorption / timelessness / effort) but never presents the items |
| Tool in an appendix | **NO** — `main.tex` has no `\appendix` and no appendix heading |

The tool itself is fully drafted in `data-collection-tool-draft.md` (FRS-10, 10 items, scoring, validity
discussion). The LaTeX snippet there is ready to paste. **This is the cheapest of the three.**

### 2. An explanation of the decisions made when creating the tool

Guide: *"Students are required to explain why they created the data collection tool… selection or
categorization of variables… types of questions… an explanation of how the tool measures what is intended
to be measured."*

| | |
|---|---|
| Present | **partly** — line 89–90 argues *why this classification instead of the four-channel model*, which is a real justification |
| Missing | why **10** items, why a 1–5 rating rather than a checklist, why retrospective-immediately-after rather than concurrent, and what evidence there is that the items measure the intended component |

### 3. A discussion of potential challenges when collecting data — **entirely absent**

Guide lists: participant variability · practice effects (fatigue/boredom) · order effects · researcher
bias · response bias · validity of the tool · controlling variables · demand characteristics.

In `main.tex` this exists only as **comments** at lines 120 and 124 asking himself to write it. There is no
prose. The guide names it as a requirement, not a suggestion.

This is the fourth structural gap in this document, and unlike the appendix it needs writing rather than
pasting. Two or three of the listed challenges genuinely fit his design:

- **Practice effects** — his design has participants attempt tasks repeatedly across times of day, so
  fatigue across sessions is a direct threat.
- **Demand characteristics** — he records face and screen while telling participants only "the program
  will be collecting data", so participants may perform focus rather than experience it.
- **Response bias** — a self-report scale completed by 10th-graders about their own concentration invites
  socially desirable answers.

## Discussion — three requirements

| Requirement | State |
|---|---|
| Potential findings + implications for policy/practice | **absent** (0 words — `discussion-fill-2026-10-27.md` covers it) |
| Researcher bias, across the guide's three questions | **absent** (same fill sheet, Part 2) |
| One additional method | **absent** (same fill sheet, Part 3) |

## Title page — four details required

Guide: title · IB student code · date/month/year · **number of words**.

| | |
|---|---|
| Title | present |
| Student code | **blank rule** |
| Submission date | **blank rule** |
| Word count | present (1,099) |

## The count of what is actually missing

1. **Appendix with the complete tool** — paste from the draft (30 min)
2. **Explanation of tool design decisions** — partly there, needs the "why 10 items / why rating scale" half
3. **Data-collection challenges** — write from scratch, 3 named challenges (≈200 words)
4. **The whole Discussion** — 480 words, three parts, fill sheet ready
5. **Student code and date on the title page**

Items 1 and 5 need no thought at all. Item 4 is scaffolded. Items 2 and 3 are the two that had never been
counted before today, and they are the reason this file exists.

## What I have not done

Written any of it. Items 2 and 3 are assessed prose about his own design decisions, and the academic
integrity rule applies — the guide wants *his* reasoning about why he built the tool that way.
