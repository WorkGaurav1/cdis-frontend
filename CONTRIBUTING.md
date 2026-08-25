# Contributing

This repo is an independently clone/build/run-able export of the `front-end/` folder in [CDIS Template](https://github.com/WorkGaurav1/cdis-engineering-template) — the canonical, complete CDIS template, where new work happens first and full documentation (architecture, workflows, standards) lives. If you're extending the template itself rather than just using this repo standalone, work there instead; changes here get overwritten on the next sync.

## Before opening a PR

```bash
npm run lint && npx tsc -b && npm test
```

These are exactly the checks CI runs — green locally means green in CI.

## Reporting a security issue

See [`SECURITY.md`](SECURITY.md).
