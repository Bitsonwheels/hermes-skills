# 🧠 Hermes Skills

Skills für [Hermes Agent](https://hermes-agent.nousresearch.com) rund um **MuninnDB** — persistentes, KI-natives Memory.

## Skills

| Skill | Beschreibung | Version | Links |
|-------|-------------|---------|-------|
| **muninndb-auto-memory** | Proaktive Nutzung von MuninnDB als Memory-Schicht via MCP. Immer laden, kein manuelles Triggern nötig. | [![v1.1.1](https://img.shields.io/badge/version-1.1.1-blue)](https://clawhub.ai/bitsonwheels/muninndb-auto-memory) | [ClawHub](https://clawhub.ai/bitsonwheels/muninndb-auto-memory) |
| **muninndb-integration** | Integriert MuninnDB als kognitives Memory-System für Hermes Agent (Setup + MCP-Konfiguration). | [![v1.0.0](https://img.shields.io/badge/version-1.0.0-blue)](https://clawhub.ai/bitsonwheels/muninndb-integration) | [ClawHub](https://clawhub.ai/bitsonwheels/muninndb-integration) |

## Installation

```bash
# Repo als Tap registrieren
hermes skills tap add Bitsonwheels/hermes-skills

# Skills installieren
hermes skills install muninndb-auto-memory
hermes skills install muninndb-integration
```

> Hinweis: Localhost-Referenzen führen zu CAUTION-Verdict im Security-Scan.
> Installation mit `--force` überschreiben falls nötig.

## Lizenz

MIT
