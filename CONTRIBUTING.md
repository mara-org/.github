# Contributing

Thanks for helping improve Mara public repositories. Keep changes small, clear, and easy to review.

## Before Opening Work

- Check existing issues and pull requests first.
- Open an issue for larger changes before spending time on implementation.
- Do not include secrets, real customer data, production logs, private keys, or real personal data.
- Match the style, tooling, and scope of the target repository.

## Pull Requests

- Explain what changed and why.
- Include tests or a clear manual validation note.
- Keep unrelated formatting and refactors out of functional changes.
- Update README or docs when user-facing behavior changes.
- Link related issues when available.

## Local Checks

Each repository owns its own checks. Prefer the commands listed in that repository's README,
`AGENTS.md`, `Makefile`, `package.json`, or project config.

Common examples:

```bash
python3 -m unittest discover -s tests
python3 -m compileall src tests
npm run lint
npm run test
npm run build
```

If a check cannot run locally, say why in the pull request.

## Maintainer Review

Maintainers may ask for narrower scope, clearer tests, documentation updates, or a different design
before merging. For security reports, use the security policy instead of a public issue.
