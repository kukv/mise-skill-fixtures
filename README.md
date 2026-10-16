# mise-skill-fixtures

Test fixtures for [kukv/mise-skill](https://github.com/kukv/mise-skill): fictional agent skills,
tags and branches that its tests install. Nothing here is a real skill. Do not move or delete the
refs below; the tests depend on them.

| Ref | Contents |
|---|---|
| tag `v0.1.0` | `skills/alpha`, `skills/beta`, `nested/deep/gamma` |
| tag `v0.2.0` | same skills, README changed (used for upgrade tests) |
| tag `draft-v9` | not a version; must be ignored by version listing |
| branch `no-skills` | no `SKILL.md` at all |
| branch `invalid-name` | the `v0.1.0` skills plus `skills/escape`, whose name tries to leave the link directory |
