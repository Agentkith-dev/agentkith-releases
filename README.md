# Agentkith Releases

The public source of truth for **what has shipped in [Agentkith](https://agentkith.dev)**.

This repository holds no application code. It exists for two purposes:

1. **Releases** — every Agentkith version is published here as a [GitHub Release](https://github.com/Agentkith-dev/agentkith-releases/releases). Release notes here feed [agentkith.dev/changelog](https://agentkith.dev/changelog).
2. **Discussions** — the community feedback channel sits in [Discussions](https://github.com/Agentkith-dev/agentkith-releases/discussions). Ideas, questions, and conversations about a specific release live there. For real-time conversation, join [Discord](https://discord.gg/3NssT2Gz).

## Where to look

| Looking for | Go to |
|---|---|
| What's in the latest version? | [Releases →](https://github.com/Agentkith-dev/agentkith-releases/releases) |
| The pretty changelog page | [agentkith.dev/changelog](https://agentkith.dev/changelog) |
| Ask a question about a release | [Discussions](https://github.com/Agentkith-dev/agentkith-releases/discussions) |
| Talk to the community live | [Discord](https://discord.gg/3NssT2Gz) |
| The Agentkith application | [agentkith.dev](https://agentkith.dev) (app source is private) |

## How releases are cut

Releases are authored as GitHub Releases on this repo. When one is published, a workflow in `.github/workflows/announce.yml` posts a Discord embed to `#announcements`. The marketing site reads from this repo's public REST API and refreshes itself within ~5 minutes — no rebuild needed.

That's the whole pipeline.
