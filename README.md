# Shared Ranger Config

Shared [Repo Ranger](https://reporanger.com) configuration for all Mikecranesync repositories.

All repos extend this config via:

```yaml
# .github/ranger.yml
_extends: Mikecranesync/default
```

## What it does

- **Auto-merge PRs** labeled `approved` or `merge when passing`
- **Auto-close issues** labeled `duplicate`, `invalid`, `wontfix`, `stale`
- **Auto-delete branches** after PR merge
- **Auto-tag releases** on merge (Patch/Minor/Major)
- **Auto-lock threads** 30 days after close
- **Welcome new contributors**
- **Delete spam comments** (+1, profanity)

## Docs

https://reporanger.com/docs
