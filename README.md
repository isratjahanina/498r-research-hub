# 498r Research Hub

A simple research workspace for the 498r project on private-object localization in images taken by people with visual impairments (VizWiz BIV-Priv-Seg domain).

It is a planning page. **No experiment has been run, no idea is approved, and no idea is confirmed novel.**

## Open it

Double-click `index.html`. It works offline in a modern browser. Keep the `assets/` folder next to it.

## Files

```text
index.html
assets/paper-ntt-architecture.png   (a figure from the NTT paper; the only image)
README.md
```

## Pages

- **Overview:** the Current Research Goal (large, editable, with history; the starting text is a proposed broader goal, not yet supervisor-approved), the four Research Questions (RQ1 to RQ4, proposed wording), the Current Focus (Current Focus, Immediate Target, Next Milestone) and a list of Open research questions. The Open research questions are undecided points (what training-free means, how many examples count as few-shot, the scope of OCR and text prompts, which datasets have masks, how to evaluate, and the BIV-Priv-Seg count mismatch); none is an approved decision. A collapsed "Backup of my edits" section at the bottom has export and import.
- **Research Ideas:** the four RQs, each with its ideas. Open an idea to see: A Idea, B Motivation, C Previous research, D Research gap, E Proposed approach, F Implementation, G Evaluation, H Status.
- **Previous Research:** a comparison table of 14 papers, then one table per paper (title, authors, objective, method, models, dataset, experiments by the authors, metrics, results, limitations, relevance to the RQs). SituationalPriv and MultiPriv are included as related work, not as segmentation baselines. A separate "Datasets and resources" entry describes the MultiPriv-PII repository.
- **Team Progress:** a placeholder. Team progress tracking will be added when collaborative experiments begin.

## How to

- **Update the goal:** Overview, *Edit goal*, change the text, *Save new goal*. The old goal moves to *Goal history* with its dates and is never deleted. Unchanged or empty text is not saved.
- **View previous goals:** Overview, *Goal history*. Old goals are struck through; click one to read it in full.
- **Update the Current Focus:** Overview, *Edit focus*, fill the three fields, *Save*.
- **Add an idea:** Research Ideas, *Add an idea under RQn*, fill in what you know (empty sections show "Not filled in yet"), *Save*.
- **Edit an idea or change its status:** open the idea, *Edit this idea*. Statuses: Under consideration, Literature review, Proposed, Selected, Experimenting, Rejected (menu under H). Built-in ideas have *Restore original text*; ideas you added can be deleted.

## What can and cannot be edited

Editable: goal, focus, and every text field of an idea, including the evaluation text and your own implementation notes. **Not editable on the page:** the built-in step-by-step experiment plans (under F and G) and the paper tables. Change those by editing `index.html`.

## What is saved where (important)

- **Saved only in your own browser, not shared:** the goal and its history, the focus fields, idea edits, added ideas and statuses. Another person or browser does not see them, and clearing browser data erases them. Use *Backup of my edits* on the Overview to export them to a file and import them again (goal history with dates, focus, ideas and statuses are included).
- **Shared with the team:** only what you commit to the repository. There is no shared editing or task board yet; that would need extra setup (for example a GitHub Project) and is not included.

## Upload to GitHub

Copy `index.html`, `assets/` and `README.md` into the repository root and commit. For a web page, enable GitHub Pages (Settings, Pages, main branch, root). The page contains your research plans, so check the repository is private if you want that. Dataset images are not included.

## Evidence notes

- Titles, authors and headline numbers for Agent2Seg, VLM-Guided Detection and Rematching, Few-Shot Semantic Segmentation Meets SAM3, No Time to Train!, VLGP (Training-Free Few-Shot Segmentation via Vision-Language Guided Prompting), BIV-Priv-Seg SituationalPriv and MultiPriv were checked against their PDFs. SituationalPriv is an anonymous submission, so it has no authors listed.
- Everything else is marked "Not verified" or "Not reported" where it was not checked. Authors of the six other related papers are not verified.
- Table, figure and section numbers are given only where they were found in the paper text. Phrases such as "our interpretation" mark our reading, as opposed to what the authors report.
- The only image is a figure from the NTT paper. Earlier pipeline diagrams were redrawn by us rather than taken from the papers, so they were removed.
- The starting goal text and the research-question wording are proposed; the supervisor has not yet confirmed them.
