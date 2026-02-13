# 📝 Summary | Résumé

_TODO:_
- Provide a concise summary of the change(s).
- Explain why this change is needed (motivation/context). Provide enough context for anyone reviewing this PR now or in the future.
- Include screenshots or screen recordings where applicable.
- If applicable, include specifications, design references, or related documentation.

## 🧩 Related Issues | Cartes liées

_TODO: Link to related issue(s) that this PR addresses or fixes, e.g. "Closes #124", "Fixes #456"._

- Issue #
- Zenhub issue:


## 🧪 Test instructions | Instructions pour tester la modification

_TODO: Replace the instructions below as needed. Describe any steps required to verify the changes work as expected._

### Preview / Validation steps

- [ ] Run the build or dev environment: `npm run build` or `npm run dev`
- [ ] Verify CSS classes render as expected in examples or test pages
- [ ] Confirm no unexpected visual regressions occur
- [ ] Confirm responsive and state variants behave as expected (if applicable)

## ✍️ Author checklist | Liste de vérification de l'auteur

**Choose one:**
- [ ] This PR is a patch (use `fix:`) — bug fixes or non-breaking corrections.
- [ ] This PR introduces a minor change (use `feat:`) — new CSS classes or non-breaking enhancements.
- [ ] This PR introduces breaking changes (use `feat!:`) — removes, renames, or changes existing CSS class behaviour.
- [ ] This PR does not introduce changes that need to be published on NPM (use `chore:`, `docs:`, `ci:`).

---

**Breaking / impact flag:**
- [ ] This PR does not remove, rename, or change existing CSS class behaviour.
- [ ] If it does, backwards compatibility, migration guidance, or deprecations are documented under **Impact/Risks**.

---

**Ready for review (all items must be checked):**
- [ ] I have verified CSS classes render correctly across supported browsers.
- [ ] I have verified CSS classes behave correctly across responsive breakpoints.
- [ ] I have verified CSS classes do not introduce unintended visual or layout regressions.
- [ ] I have verified CSS classes remain aligned with design tokens and semantic standards (if applicable).
- [ ] I have verified accessibility requirements continue to meet standards. :accessibility:
- [ ] I have verified documentation and usage examples reflect the changes.
- [ ] For visual or design changes, I have posted in the dev-design Slack channel.
- [ ] I have ensured test instructions are clear and reproducible.


## 🧐 Reviewer checklist | Liste de vérification du réviseur

**Developer checklist (if applicable)**

For complex PRs, in lieu of a simple approval or "LGTM" ✅, include the following with your approval:

- [ ] I have verified CSS classes compile and build successfully.
- [ ] I have verified generated CSS output matches expected behaviour.
- [ ] I have reviewed implementation for clarity, maintainability, and performance considerations.

---

**Design checklist (if applicable)**

For designers, include the following with your approval:

- [ ] I have verified layout, spacing, and visual behaviour produced by CSS classes.
- [ ] CSS classes align with design system standards and token scales.
- [ ] I have verified accessibility considerations (contrast, motion, etc.).
- [ ] I have verified responsive and state behaviour works as expected.
- [ ] Any design inconsistencies have been raised in Slack or tracked via an issue.

---

**Content / Documentation checklist (if applicable)**

For documentation reviewers, include the following with your approval:

- [ ] I understand the context and intent of the documentation changes.
- [ ] I have reviewed usage guidance, clarity, and examples.
- [ ] I have verified English and French documentation for accuracy and parity.
- [ ] I have verified examples reflect correct CSS class usage.
- [ ] Terminology and naming follow design system standards.

## ⚠️ Impact/Risks | Risques

_Optional: Highlight any potential implications, risks, or important notes for reviewers or maintainers (e.g., breaking CSS classes, visual regressions, bundle size impacts, build pipeline changes, dependency updates, etc.)._
_Highlight any deprecations or migration guidance here._
