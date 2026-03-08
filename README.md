<p align="center">
  <img src="logo.png" alt="Roxlit" height="120">
</p>

<h3 align="center">AI-powered Roblox development, one click away</h3>

<p align="center">
  <a href="https://roxlit.dev">Website</a> ·
  <a href="https://github.com/Roxlit/installer/releases/latest">Download</a> ·
  <a href="https://discord.gg/roxlit">Discord</a>
</p>

---

Roxlit is an open-source launcher that connects AI tools (Claude Code, Cursor, Windsurf, Copilot) to Roblox Studio. It installs the entire development environment, generates AI context so your assistant actually understands Roblox, and manages file sync + MCP with a single click.

## Repositories

| Repo | Description |
|------|-------------|
| [**installer**](https://github.com/Roxlit/installer) | Desktop app — launcher + installer (Tauri v2, React, Rust) |
| [**web**](https://github.com/Roxlit/web) | Landing page at [roxlit.dev](https://roxlit.dev) (Next.js, Cloudflare Pages) |
| [**docs**](https://github.com/Roxlit/docs) | Internal documentation |

## What Roxlit Does

1. **Installs everything** — Aftman, Rojo, Studio plugins, MCP server. No terminal needed.
2. **Generates AI context** — Curated Roblox documentation (context packs) so your AI writes correct Luau code instead of hallucinating APIs.
3. **Launches with one click** — Starts Rojo + MCP server, opens your editor, streams logs in real time.

## Roadmap

Full roadmap at [roxlit.dev/roadmap](https://roxlit.dev/roadmap).

### Done
- [x] Desktop launcher (Windows)
- [x] One-click Rojo + MCP setup
- [x] AI context generation (Claude, Cursor, Windsurf, Copilot)
- [x] Context packs — 7 curated Roblox documentation packs
- [x] Studio plugin auto-install
- [x] MCP server with 15+ tools (run code, logs, backups, telemetry)
- [x] Smart backups (snapshots, restore, diff)
- [x] Real-time telemetry system
- [x] Studio log capture with per-playtest rotation

### In Progress
- [ ] DevForum Community Resources post
- [ ] Discord server
- [ ] Video tutorials / demos

### Planned
- [ ] Advanced telemetry (collision logging, filtering)
- [ ] Sandbox testing environments
- [ ] Autonomous debug loop with safety rails
- [ ] Unified sync engine (own plugin, Rojo-compatible)
- [ ] Asset marketplace
- [ ] Team collaboration

## Contributing

Roxlit is fully open-source. Contributions are welcome — check individual repo READMEs for setup instructions.

## License

MIT — see individual repositories for details.
