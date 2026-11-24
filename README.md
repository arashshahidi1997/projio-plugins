# projio plugins

projio's portable Claude Code skills: they need git only, not projio. Versioned on their own: a release is a version bump, an export and a push.

Install in Claude Code:

```text
/plugin marketplace add arashshahidi1997/projio-plugins
/plugin install projio-workflow@projio
```

- `projio-workflow` 0.3.1: A standing manager session for any git project (incoming notes, session states, board, handoffs), its setup, a session wrap that commits by path and writes a handoff, and the 'always complete, never finished' check. Needs git and Python 3.9+, not projio.

Updates: `/plugin marketplace update projio`, then update the plugin from the `/plugin` menu.

This repository is generated from [projio](https://github.com/arashshahidi1997/projio) with `projio skills export --marketplace <dir>`; edit the skills there, not here. Guide: https://arashshahidi1997.github.io/projio/how-to/skills-without-projio/
