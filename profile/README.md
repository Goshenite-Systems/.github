# Goshenite Systems

**Goshenite Linux** — a security-focused **immutable** Linux OS built on the [Universal Blue](https://universal-blue.org) ecosystem.

We extend **Aurora (KDE)** and **Bluefin (GNOME)** the way [Bazzite](https://bazzite.gg) extends Fedora Atomic for gaming — bringing a curated, Kali-style security experience to an OCI-based, reproducible, cosign-signed operating system.

> *Goshenite is the colorless, glass-clear variety of beryl. Codename: **Project Glass**.*

### Projects

| Repo | What |
|------|------|
| **[glass](https://github.com/Goshenite-Systems/glass)** | Main immutable image definition + bundle generator |
| **[glass-bundles](https://github.com/Goshenite-Systems/glass-bundles)** | Declarative security-tool bundle manifests |

### Why not just use Kali?

Kali is excellent but mutable Debian. Goshenite keeps Kali's best idea — **layered, categorized tool organization** — while gaining immutability, atomic updates, reproducible OCI builds, and easy rebasing from upstream Aurora/Bluefin. The core innovation: **declarative bundle manifests** that define RPMs, Flatpaks, containers, config, and desktop integration from a single source of truth.

*Apache-2.0 licensed, matching the uBlue ecosystem.*
