# calambur.github.io

Personal site (Calambur — Cybersecurity Blue Team & AI Engineer), served via
GitHub Pages from this `main` branch.

Built output is committed directly. The source lives in this host at
`~/hermes-workspace/projects/calambur-github-io/` (Vite + React 19 +
Tailwind v4). Rebuild locally:

```bash
pnpm install
pnpm build      # outputs ./dist/
```

Then sync `./dist/*` into the repo root (alongside `.nojekyll`).

Theme: dark / light / system, EN + ES translations, GitHub + X widgets,
blog + projects + activity sections.