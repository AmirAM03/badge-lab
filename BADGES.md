# GitHub Achievements — badge-lab archive

This repository is a self-contained, documented sandbox used to earn GitHub profile achievements through **legitimate platform workflows only**: normal git branches, pull requests, merges, an issue, and Q&A discussions. No fake accounts, no spam targeting other people's repos, no automation outside ordinary `git` and `gh` commands against this repository.

> Profile achievements page: <https://github.com/users/AmirAM03/achievements>
> Achievements are awarded asynchronously and can take **up to 24 hours** to appear after the qualifying action.

## Achievements earned

| Achievement | Requirement | How it was earned here |
|-------------|-------------|------------------------|
| **YOLO** | Merge a pull request without review | [PR #1](https://github.com/AmirAM03/badge-lab/pull/1) was opened and squash-merged with no reviews ([my own PRs cannot be self-approved](https://docs.github.com/en/pull-requests)). |
| **Quickdraw** | Close an issue or pull request within 5 minutes of opening | [Issue #3](https://github.com/AmirAM03/badge-lab/issues/3) was opened and closed ~30 seconds later. |
| **Pull Shark — bronze** | 2 merged pull requests | [PR #1](https://github.com/AmirAM03/badge-lab/pull/1) and [PR #2](https://github.com/AmirAM03/badge-lab/pull/2). |
| **Pull Shark — silver** | 16 merged pull requests | All 16 merged PRs in this repo ([merged list](https://github.com/AmirAM03/badge-lab/pulls?q=is%3Apr+is%3Amerged), [CHANGELOG.md](CHANGELOG.md)) — every PR is squash-merged. |
| **Galaxy Brain — bronze** | 2 accepted answers in Discussions | [Discussion #17](https://github.com/AmirAM03/badge-lab/discussions/17) and [Discussion #18](https://github.com/AmirAM03/badge-lab/discussions/18) in the Q&A category, each with an accepted answer. |

## Workflow used

1. **Branch per change** — every change (including this document) is made on a short-lived branch created from up-to-date `main`.
2. **Pull request per branch** — `gh pr create` opens the PR immediately; the body documents the change.
3. **Squash merge without review** — `gh pr merge --squash --delete-branch` keeps history linear and the branch list clean. Because no review is requested and GitHub does not allow approving your own PR, the first of these granted **YOLO**.
4. **Issue + fast close** — **Quickdraw** came from opening issue #3 and closing it (`--reason "not planned"`) within the same minute.
5. **Q&A discussions** — Discussions were enabled on the repo, two Q&A threads were created with a documented answer each, and the answers were marked as accepted (**Galaxy Brain**).
6. **Co-authored commits (planned)** — a future pull request will add a commit with a `Co-authored-by:` trailer crediting a second GitHub account, which is what **Pair Extraordinaire** requires. The other account receives the badge too.

## Full index

- Pull requests: <https://github.com/AmirAM03/badge-lab/pulls?q=is%3Apr+is%3Amerged> (all 16+ merged)
- Issue: [#3](https://github.com/AmirAM03/badge-lab/issues/3) (Quickdraw)
- Discussions: [#17](https://github.com/AmirAM03/badge-lab/discussions/17), [#18](https://github.com/AmirAM03/badge-lab/discussions/18) (Galaxy Brain)
- Changelog with per-PR mapping: [CHANGELOG.md](CHANGELOG.md)

## Notes and limits

- **Starstruck** (16 stars) requires other people to star a repo — it cannot honestly be self-farmed and is not pursued here.
- **Pair Extraordinaire** is pending: it needs a commit co-authored with a second real GitHub account (a friend), which will be added as a follow-up pull request.
- **Public Sponsor** requires sponsoring a developer or organization.
- Historical achievements (Arctic Code Vault, Mars 2020) are no longer obtainable.
- Heavy automation against third-party repositories could trip GitHub's abuse detection; everything in this repo deliberately stays within normal, human-scale usage of your own repository.
