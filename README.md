# fountain-demos

The landing page at [demos.inevitable.fyi](https://demos.inevitable.fyi): an
index of applications built on the
[Fountain](https://github.com/BinaryBourbon/fountain) API — agents on
sandboxes, driven over HTTP.

| App | For | Where |
|---|---|---|
| Briefing Room | everyone | [briefs.inevitable.fyi](https://briefs.inevitable.fyi) |
| Table Talk | everyone | [tables.inevitable.fyi](https://tables.inevitable.fyi) |
| Fountain Team | everyone | [github.com/jhgaylor/fountain-team](https://github.com/jhgaylor/fountain-team) |
| Repo Sage | engineers | [reposage.inevitable.fyi](https://reposage.inevitable.fyi) |
| Mission Control | engineers | [mission.inevitable.fyi](https://mission.inevitable.fyi) |
| Watchtower | infrastructure | [watchtower.inevitable.fyi](https://watchtower.inevitable.fyi) |
| Mend | infrastructure | [mend.inevitable.fyi](https://mend.inevitable.fyi) |
| DNS Desk | infrastructure | [github.com/jhgaylor/dns-desk](https://github.com/jhgaylor/dns-desk) |
| Arena | AI engineers | [arena.inevitable.fyi](https://arena.inevitable.fyi) |

Static HTML in `site/`, served by nginx; built to
`ghcr.io/jhgaylor/fountain-demos` by `.github/workflows/build.yml` and rolled
out by Flux from `k8s/` (home-cloud).

## License

MIT
