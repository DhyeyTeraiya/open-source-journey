# 🌱 Open Source Journey

A running log of my contributions to the open-source data tools I use every
day — what I changed, what I learned, and where each change ended up.

Started **14 Feb** · environment set up **15 Feb**.

## Pull requests

| Repository | PR | Change | Status |
| :--- | :--- | :--- | :--- |
| **scikit-learn** | [#33297](https://github.com/scikit-learn/scikit-learn/pull/33297) | `DOC:` fix duplicated-word typos in `sklearn/_loss/loss.py` | ✅ **Merged** |
| **huggingface/datasets** | [#8008](https://github.com/huggingface/datasets/pull/8008) | `fix:` prevent duplicate keywords in `load_dataset_builder` (issue #4910) | 🟡 **Open** — awaiting review |
| **pandas** | [#64169](https://github.com/pandas-dev/pandas/pull/64169) | `TST:` regression test for `GH#54627` | ⚪ **Closed** — not merged |

Statuses last verified **2026-10-27** through the GitHub API. This table is
updated by hand whenever something changes.

## Forks used for contribution work

| Upstream | My fork |
| :--- | :--- |
| `pandas-dev/pandas` | [DhyeyTeraiya/pandas](https://github.com/DhyeyTeraiya/pandas) |
| `scikit-learn/scikit-learn` | [DhyeyTeraiya/scikit-learn](https://github.com/DhyeyTeraiya/scikit-learn) |
| `huggingface/datasets` | [DhyeyTeraiya/datasets](https://github.com/DhyeyTeraiya/datasets) |

## How this repo is organised

- [`JOURNAL.md`](JOURNAL.md) — the day-by-day learning log
- The table above is the authoritative status of every upstream PR
- Nothing here is generated; it is maintained by hand so the statuses stay honest

## What I've learned so far

- **Small, focused PRs get reviewed.** The typo fix in `scikit-learn` merged
  quickly because the diff was tiny and scoped to documentation.
- **Read `CONTRIBUTING.md` before opening.** Each project formats tests,
  docstrings and changelog entries differently, and a mismatched PR stalls.
- **A closed PR is not a wasted PR.** The `pandas` regression test was closed,
  but the discussion clarified how the existing fixture should be extended.
