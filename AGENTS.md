# Repository instructions

- This repository publishes Mokisu release assets; application source and build workflows remain in the private source repository.
- Default-branch changes go through pull requests. CI must pass, all review threads must be resolved, and the branch must include the latest base before merging.
- Maintainers use the trusted meta checkout's `scripts/merge-pr.mjs` entrypoint. A passing check does not authorize a merge; wait for explicit user authorization. Do not bypass it with direct default-branch pushes or direct merge API calls.
- Keep CI on GitHub-hosted runners. Public workflows cannot call private meta workflows.
- Do not create or publish releases, replace release assets, or move tags as part of CI configuration work.
