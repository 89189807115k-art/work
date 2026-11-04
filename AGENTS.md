# Codex project instructions

## Purpose
Build and maintain high-quality websites, applications, prototypes, and automation workflows.

## Workflow
1. Inspect the existing repository, README, package manifests, and tests before editing.
2. For multi-step work, describe a brief plan and then implement it.
3. Prefer small, reviewable changes. Preserve working functionality.
4. Never invent integrations, APIs, prices, reviews, credentials, or client data.
5. Run available tests, lint, typechecks and build commands; report actual results.
6. Summarize changed files, verification, and outstanding blockers.

## Communication and quality
- Communicate with the project owner in Russian; write code identifiers in English.
- Favor complete working functionality over static mockups.
- Build accessible, responsive interfaces with clear visual hierarchy.
- Respect prefers-reduced-motion; use heavy visual effects only where justified.
- Follow the repository's existing stack and conventions.

## Privacy and security
- Never commit secrets, API tokens, passwords, personal data or internal client documents.
- Use environment variables for credentials and .env.example for placeholders.
- Never commit Claude memory exports or other private context bundles.
- Ask for explicit authorization before destructive, externally visible, costly, or production-affecting actions.
- Do not disable safety approvals or sandbox controls.

## Git hygiene
- Use a dedicated working branch for substantial changes.
- Prefer pull requests for review before merging.
- Do not rewrite unrelated files or overwrite the owner's work.
