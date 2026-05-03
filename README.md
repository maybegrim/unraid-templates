# Unraid Docker Templates

Community Application templates for [Unraid](https://unraid.net/).

## Applications

| Application | Description |
|---|---|
| [NextExplorer](https://github.com/nxzai/NextExplorer) | Modern, self-hosted web-based file explorer with secure access control (Tailscale supported) |
| [Forgejo Runner](https://code.forgejo.org/forgejo/runner) | CI/CD workflow runner for Forgejo Actions |

## Installation

These templates are available through the Unraid Community Applications plugin. Search for **NextExplorer** or **Forgejo Runner** in the Apps tab.

### Manual Installation

In the Unraid web UI, go to **Docker → Add Container → Template** and paste the XML URL for the template you want:

| Application | Template URL |
|---|---|
| NextExplorer | `https://raw.githubusercontent.com/maybegrim/unraid-templates/main/NextExplorer/NextExplorer.xml` |
| Forgejo Runner | `https://raw.githubusercontent.com/maybegrim/unraid-templates/main/ForgejoRunner/ForgejoRunner.xml` |

Or add the full repository under **Docker → Add Container → Template Repositories** with `https://github.com/maybegrim/unraid-templates` to get all templates at once.

## Support

- **NextExplorer**: [Unraid Forums Support Thread](https://forums.unraid.net/topic/197867-support-nextexplorer-modern-web-based-file-explorer/) · [Bug Reports](https://github.com/nxzai/NextExplorer/issues) · [Docs](https://explorer.nxz.ai)
- **Forgejo Runner**: [Unraid Forums Support Thread](https://forums.unraid.net/) · [Bug Reports](https://code.forgejo.org/forgejo/runner/issues) · [Docs](https://forgejo.org/docs/next/admin/actions/)
