# Contributing to this fork

This fork focuses on an Android home-screen widget and small improvements to checking bus ETAs. The original project is [hkbus/hk-independent-bus-eta](https://github.com/hkbus/hk-independent-bus-eta).

## Issues and labels

For a bug or feature, describe the rider's problem, the current and expected behavior, and how to verify the result. Include the route, direction, and stop for ETA examples. Identify any open data questions and mark design mockups as proposals.

Use GitHub's standard labels, such as `bug`, `enhancement`, and `documentation`. Add an `area:` label when it helps people find related work, such as `area: eta` for ETA behavior, `area: widget` for Android widgets, or `area: tooling` for builds and CI.

- A contribution workflow PR uses `documentation`.
- The 268C special-departure feature uses `enhancement` and `area: eta`.

## Branches and pull requests

1. Start from this fork's `master` and create a short, descriptive branch, such as `feat/kmb-special-departure-labels`.
2. Keep each PR focused on one change and target this fork's `master`. Open a draft PR if you want feedback while work is in progress.
3. Link the relevant issue. Use `Closes #123` when merging the PR should close that issue.
4. For code changes, run `yarn lint` and `yarn build`, check the GitHub Actions result, and verify the affected behavior. Include before and after screenshots for visible changes. Record the checks you actually ran and any gaps.
5. Sync from upstream in a dedicated PR so the sync and the fork's changes are easy to review independently.

See the [README](README.md) for local setup.
