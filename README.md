# From NLP to LLM — Student Materials

Everything you need to study with **From NLP to LLM: The Evolution of Language
Intelligence** by Mahmmoud A. Mahdi: the book, the student workbook, the lab
manual, and the Sanad project checkpoints.

The book is a draft edition released chapter by chapter. New chapters and
project levels are added here as they are published, so **Watch** the
repository for updates.

## What is here

| Folder | File | What it is |
| --- | --- | --- |
| `pdf/` | `from-nlp-2-llm.pdf` | The book (reader edition) |
| `pdf/` | `from-nlp-2-llm-student-workbook.pdf` | Worksheets and project logs to complete |
| `pdf/` | `from-nlp-2-llm-lab-manual.pdf` | Skill labs and the Sanad project levels |
| `project/` | `sanad-LN.zip` | Starter checkpoint for Sanad project level `N` |

## What to do after each chapter

Read the chapter, complete its workbook sheets, then build the matching
project level from the lab manual.

| Chapter | Workbook | Project |
| --- | --- | --- |
| 1 | Sheets 1–2, log L1 | Level 1: The yardstick (`sanad-L1.zip`) |

## Getting started with Sanad

You need Python 3.11 or newer (`python3 --version`).

```sh
unzip project/sanad-L1.zip && cd L1
python3 -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements-dev.txt
python -m pytest -v
python -m sanad report
```

The tests for the current level are held back for grading and show as skipped.
Leave those files unchanged and add your own tests next to them. The `README.md`
inside each checkpoint has the full rules.

## Problems or mistakes?

If something does not run as described, or you find an error in the book,
workbook, or lab manual, open an issue in this repository. Say which file and
page, what you expected, and what happened, and include your Python version and
the full error output.

---

Copyright © 2026 Mahmmoud A. Mahdi. Draft edition.
