# Homeowner Decision Micro-Apps specification hub

This Mintlify site is the living product, design, calculation, integration, and launch specification for Rapha's homeowner decision micro-apps.

It is deliberately separate from the future production application repository.

## Preview

Install the Mintlify CLI and run it from the repository root:

```bash
npm i -g mint
mint dev
```

## Publishing

Mintlify's GitHub app deploys the default branch. Review changes through pull requests and preview deployments before merging into `main`.

## Review workflow

1. Rapha approves product direction and unresolved decisions.
2. Claude challenges the frozen specification.
3. Codex implements accepted documentation changes and later hardens generated application code.
4. Lovable generates application code only after the Phase 1 gate is approved.
