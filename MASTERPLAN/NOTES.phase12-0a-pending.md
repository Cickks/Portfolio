# Phase 12.0A LINUX01 Baseline Validation Notes - 2026-07-05

Phase 12.0A validation confirms LINUX01 remains the correct safe practice and staging host before applying risky storage, Docker, networking, or service changes to INFRA01.

Management plane:

- SSH on 192.168.56.50:22 passed from Windows source 192.168.56.1.

Service plane:

- Portainer on 192.168.56.50:9443 passed from Windows source 192.168.56.1.

Storage and runtime plane:

- Linux disk, mount, fstab, Docker, containerd, Docker inventory, volume, and network checks were captured in the terminal validation.

Decision:

- Good to proceed toward Phase 12.1 Samba baseline on LINUX01.
- Do not combine package updates with the first Samba change unless security urgency requires it.
- Keep INFRA01 in staging until NVMe SSD, persistent mount, Docker data placement, backup plan, monitoring expectation, and rollback documentation are complete.
