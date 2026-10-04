# .github

Organisation-level files for **Galvarya**.

| Path | What it does |
|---|---|
| `profile/README.md` | Renders as the public organisation page at [github.com/Galvarya](https://github.com/Galvarya) |
| `profile/banner.png` | The banner on that page — 1600×400, generated from the mark's own geometry and the brand palette |
| `SECURITY.md` | Default vulnerability-reporting policy, inherited by every repo in the org that does not define its own |

Community health files placed here (`SECURITY.md`, `CONTRIBUTING.md`,
`CODE_OF_CONDUCT.md`, issue and pull-request templates) apply org-wide as
defaults. A repo that ships its own copy overrides the default for that repo.

## Editing the profile page

`profile/README.md` is the company page — treat it as production copy. The image
is referenced by absolute `raw.githubusercontent.com` URL rather than a relative
path, because relative image paths do not resolve reliably when GitHub renders the
profile outside the repository.

Note that the profile is **public** while the organisation's product repositories
are private, so the page links only to `galvarya.com` and `tomomi.app`. Do not add
repository links until the repository in question is public — they render as
404s to anyone signed out.
