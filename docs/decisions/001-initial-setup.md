# ADR 001 – Initial Setup

**Status:** Accepted  
**Date:** 2025-09-09

## Context
We need a minimal, secure Git/GitHub setup to start collaborating.

## Decision
- Use SSH (ed25519) for authentication.
- Global identity set to personal account.
- Default branch: `main`.
- Initial files: README, .gitignore, LICENSE.
- Versioning: X.Y.Z (start at 0.1.0).

## Consequences
- Secure pushes/pulls and consistent structure.
- Clear versioning for later sprints and tags.
