---
type: Fixed
pr: 4103
---
**STATE.md frontmatter now quotes numeric-looking identifiers** — decimal phase ids such as `22.1` and `22.10` no longer collide as YAML floats on read-back. (#4053)
