# Contributing Guide

Thanks for your interest in contributing! This organization uses:
- **CC BY 4.0** for written content and learning materials.
- **MIT** for code and build scripts.

By opening a PR, you agree your **content** contributions are licensed under **CC BY 4.0**, and your **code** under **MIT**.

## How to contribute
1. **Fork and branch**
   - Branch name: `feat/...`, `fix/...`, or `docs/...`.
2. **Commits**
   - Use clear, imperative messages: `feat(curriculum): add ADV-201 lesson skeleton`.
3. **PRs**
   - Template is required. Link related issue. Keep PRs small.
   - Mark as **Draft** if still in progress.
4. **Reviews**
   - Be kind; prefer suggestions over blocking when possible.
5. **Content rules**
   - Only link to **free** resources; include license info in front-matter.
   - For translations, follow `/templates/atribuicao-traducao.md` and keep proof of permission.
6. **Checks**
   - Markdown lint, inclusive-language (alex), and link checker may run via reusable workflows.

## Local quick checks
```bash
# examples – project specific tools may vary per repo
npm run lint:md    # markdownlint (if configured)
npm run check:links
npm run lint:a11y  # alex or equivalent
```
## Security

Please see [SECURITY.md](SECURITY.md) for private reporting of vulnerabilities.