# Portfolio Workspace

This repository is the top-level planning and archive workspace for the portfolio. The primary
client/employer-facing work now lives in the dedicated project repositories below.

## Primary Repositories

| Project                           | GitHub                                         | Local folder           | Purpose                                                  |
| --------------------------------- | ---------------------------------------------- | ---------------------- | -------------------------------------------------------- |
| Infrastructure Operations Toolkit | <https://github.com/Cickks/infra-ops-toolkit>  | `IT-ENGINEER-TOOLKIT/` | Homelab operations documentation, runbooks, and evidence |
| LocalOps Assistant                | <https://github.com/Cickks/localops-assistant> | `AISTEVE/`             | Local-first FastAPI/Ollama assistant API foundation      |
| Portfolio Workspace               | <https://github.com/Cickks/Portfolio>          | `C:\Portfilio`         | Master-plan DOCX files, prompts, and workspace routing   |

## Current Phase

Active infrastructure work is in Phase 12 of the homelab roadmap:

- Phase 12.0A: LINUX01 practice/readiness complete
- Phase 12.1: Samba complete
- Phase 12.2: NFS complete
- Phase 12.3: Cron jobs complete
- Phase 12.4: Custom systemd services complete
- Phase 12.5: SSH key expansion complete
- Phase 12.6: Linux backups and restore testing complete
- Phase 12.7: First self-hosted app decision next

LocalOps Assistant is aligned to Phase 22 and remains downstream of the infrastructure foundation.
It should not operate against lab systems until services are documented, monitored, backed up, and
covered by rollback procedures.

## Key Local Entry Points

- `IT-ENGINEER-TOOLKIT/README.md`
- `IT-ENGINEER-TOOLKIT/Documentation/HomeLab/Architecture/MASTER_PLAN.md`
- `IT-ENGINEER-TOOLKIT/docs/ROADMAP.md`
- `IT-ENGINEER-TOOLKIT/docs/PHASE_TRACKER.md`
- `AISTEVE/README.md`
- `AISTEVE/docs/HOMELAB_ALIGNMENT.md`
- `MASTERPLAN/ROADMAP.docx`
- `MASTERPLAN/PORTS.docx`
- `MASTERPLAN/Scripts.docx`
- `MASTERPLAN/Commands.docx`
- `MASTERPLAN/Tickets.docx`
- `MASTERPLAN/Lessons Learned.docx`

## Repository Hygiene

Large binaries, installers, VM exports, compressed images, secrets, logs, and build outputs are
ignored by Git. Keep notes, checksums, versions, commands, screenshots, validation summaries, and
rollback evidence in Markdown or the master-plan DOCX files.
