# Release notes: 2026-05-25 — github-description-seo

**Status:** Ready for review  
**Repo:** li-langverse/li-demo  
**Author:** agent (WP-A4)

## Summary (one sentence)

Replace template GitHub description with Li demo/HPC/AI-oriented blurb; README + `.github/repo-description`.

## Agent continuation (required)

1. Read: `.github/repo-description`.
2. Run: `gh repo view li-langverse/li-demo --json description`.
3. Then: demo samples and agent-kit workflow tests as needed.
4. Blocked on: WP-H2 — **none**.

## Changed (specific)

- `.github/repo-description`, `README.md`, `CHANGELOG.md`.

## Not changed (scope fence)

- Demo `.li` sources, `li-cursor-agents` workflow fixture paths — **not** touched.
- `lic` compiler — **not** in this PR.
- LICENSE mass-edit — WP-H2.

## Breaking changes

None.

## Security

N/A.

## Performance

N/A.

## Downstream

N/A.
