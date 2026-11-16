# .github

Default community files for every repository in the **forgelabs-id** organization.

Issue templates under `ISSUE_TEMPLATE/` apply to any repo in this org that has no
`.github/ISSUE_TEMPLATE/` of its own. A repo with its own folder ignores this one
entirely — the two are not merged per file.

| Template | Use it for |
| --- | --- |
| `bug.yml` | behaviour that deviates from expectation, measured evidence required |
| `feature.yml` | new capability or behaviour change, testable acceptance criteria required |
| `documentation.yml` | docs that are wrong, stale, or missing |

Blank issues are disabled via `config.yml`.
