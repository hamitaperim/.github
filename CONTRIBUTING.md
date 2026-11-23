# Contributing

This guide covers every repository in the hamitaperim organization.

## How work flows

1. Pick an issue from the [roadmap](https://github.com/orgs/hamitaperim/projects/1) or the repository's issue list, and assign yourself.
2. Create a branch from `main`. Name it `type/short-description`, for example `feat/week-view-filters` or `fix/calendar-timezone`.
3. Commit in small steps using [Conventional Commits](https://www.conventionalcommits.org): `feat(home): add week view filters`.
4. Open a pull request and fill in the template. Link the issue with `Closes #123`.
5. A maintainer reviews every pull request. A designer also reviews changes to screens, styles and copy.
6. Merge with squash or rebase once a code owner has approved and CI is green. `main` accepts changes only this way. The branch is deleted on merge.

## What a good pull request has

- One purpose. Split unrelated changes.
- Tests for changed logic.
- Before and after screenshots for anything visible, at 375, 768 and 1280 px.
- Hebrew and RTL checked by eye.

## Labels

- Issues use a native type, Epic, Feature, Bug, Spike, Design, Chore or Task. Use Chore for documentation and refactoring issues. Repository contribution guides define PR label conventions. Site PRs use one `type:*` label and at least one affected `area:*` label.
- Forms add `needs-triage`. Bug and Feature forms also add `area:site`. Maintainers review intake, set its native type and affected areas, then remove `needs-triage`. For items tracked in project #2, set Status, Horizon and Discipline as appropriate. Use Todo for accepted work that is ready to pick up. Keep priority and effort separate from workflow state.

## Secrets and data

- Keep tokens, connection strings and personal details out of commits, issues and pull requests.
- Private data (form submissions, the private store) stays out of every repository.

## Security

Report vulnerabilities privately. See [SECURITY.md](SECURITY.md).
