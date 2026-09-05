# Historical repository guidance

## Purpose and map

Preserve a historical Delphi/Object Pascal Windows console game. The default
branch is `master`. Read [README.md](README.md) for chronology and provenance
limitations. The root Delphi project starts the game; `Liste des unitées/`
contains character, combat, map, story, interface and save units. Existing
compiled files, audio, resources, filenames and legal notices are historical
material, not a verified current distribution.

## Preservation boundaries

- Index the requested area and applicable instructions before editing. Preserve
  dirty work, historical names, source, project files, assets, credits and Git
  history. More specific nested guidance and stricter task restrictions apply.
- Documentation maintenance does not authorize modernization, source/resource
  changes, executing legacy binaries, installing a toolchain, CI, releases or
  provider access. Obtain separate scope authorization for such work.
- Do not infer sole authorship, contribution shares, asset rights, exact original
  dates or variable counts. Keep owner recollection distinct from Git evidence.
  Do not extend the existing license over material of uncertain provenance.
- Use synthetic examples only if needed. Do not introduce personal contact,
  private paths, identifying organization details or private audit material.

## Documentation validation

Run `git diff --check` and `git diff --cached --check`. For committed changes,
set `PR_BASE_SHA` to the exact verified PR base commit and run
`git diff --check "${PR_BASE_SHA:?}...HEAD"`. Do not infer the comparison ref
from a cloud checkout's local branch name; verify the repository target separately.
Inspect the complete proposed diff and file allowlist, Markdown rendering,
relative links, source-backed claims and redacted privacy/secret checks.
There is no verified current application build or test gate. Do not run the
historical game or claim that documentation checks validate its runtime.

## Reviewed delivery

For authorized new work, verify the actual upstream base and create an isolated
feature branch from its refreshed head. Continue an existing approved PR at its
verified head with normal commits; do not reset, stash, amend, rebase or force-push.
Push and create a ready PR only with publication authority.

Check whether automatic Codex review starts; request one `@codex review` if
needed. Inspect reviews, threads, comments, checks and PR/request reactions.
Eyes, silence and stale reactions are not completed review. Correlate any clean
signal with the exact substantive head. Fix valid in-scope findings, validate,
reply and resolve addressed threads; obtain fresh review after substantive
changes. Explain invalid feedback; keep material ambiguity unresolved.

Use bounded review waits and hand off the exact pending head when unavailable.
Leave the PR for human review unless merging is explicitly authorized. For an
authorized merge, refresh all gates, use an expected-head guard without bypass,
and verify the published result. Delete only the merged branch when authorized.
Corrections use reviewed commits, not history rewriting.

Keep this guidance concise and accurate during authorized work. Read-only tasks
do not trigger onboarding edits. Preserve custom/nested rules and avoid changes
on a second pass without new facts. Playbook maintenance requires both a reusable
gap and separate cross-repository authority.
