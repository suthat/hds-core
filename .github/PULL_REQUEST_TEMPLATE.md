## What this PR does

<!-- 1–3 sentences: what changed and why. -->

Closes #

## Type of change

<!-- Check one. Must match the changeset bump below. -->

- [ ] Bug fix (patch)
- [ ] New feature or component (minor)
- [ ] Breaking change (see Public API note below)
- [ ] Documentation only
- [ ] Tooling or CI (no effect on published CSS)

## How to review

<!-- Point reviewers at what to look at: screenshots, or the Storybook
stories to open and the palettes / viewports that actually matter here.
Flag anything that needs a design or accessibility eye. For docs-only or
tooling PRs, write "N/A". -->

## Before requesting review

<!-- CI re-runs all of these — this is a courtesy pass, not a second gate.
Full command list: CONTRIBUTING.md. -->

- [ ] `npm run lint`, `npm run format`, and `npm test` pass locally
- [ ] Verified across the palettes and viewports this change affects
- [ ] **If it touches `src/scss/**`:** added a changeset (`npx changeset`) at the level in the [semver rubric](../CONTRIBUTING.md#semver-rubric), and re-ran any `update:*` command CI flags (public API snapshot / CSS baseline)

## Notes for reviewers

<!-- Anything unusual, known limitations, or planned follow-ups. Optional. -->
