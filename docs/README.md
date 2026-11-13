# Nexus documentation

New here? Start with **[Setting up the whole ecosystem](SETUP.md)**.

## Apps

| Guide | Repository |
|---|---|
| [Nexus for iPhone](apps/IOS.md) | [NexusiOS](https://github.com/ljcatherine/NexusiOS) |
| [Nexus Desktop for Linux](apps/LINUX.md) | [NexusNix](https://github.com/ljcatherine/NexusNix) |
| [Nexus Desktop for Windows](apps/WINDOWS.md) | [NexusWindows](https://github.com/ljcatherine/NexusWindows) |
| [Nexus Online](apps/ONLINE.md) | [NexusOnline](https://github.com/ljcatherine/NexusOnline) |

## Backend

Source: [ljcatherine/NexusBackend](https://github.com/ljcatherine/NexusBackend) (gateway, Workers, orchestrator, workspace agent).

| Guide | What it covers |
|---|---|
| [Debian server](backend/DEBIAN.md) | Hardening, gateway, tunnel, orchestrator, workspace agent, `nexus-ro` |
| [Cloudflare](backend/CLOUDFLARE.md) | Tunnel, Workers VPC, Access and Managed OAuth, both Workers, custom domain |
| [NexusAI](backend/NEXUSAI.md) | The custom NexusAI PS5 app, model-control API, agent orchestrator, Hermes |

## Across the ecosystem

| Guide | What it covers |
|---|---|
| [Full setup](SETUP.md) | End-to-end deployment, in order |
| [Architecture](ARCHITECTURE.md) | Components, request paths and ports |
| [Security](SECURITY.md) | Threat model and where each control is enforced |
| [Configuration](CONFIGURATION.md) | Per-app deployment settings in one place |
