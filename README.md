# cloudbase

CloudBase AI Plugin — MCP Server + Agent Skills for AI Coding Agents

This repository is automatically synced from [TencentCloudBase/CloudBase-MCP](https://github.com/TencentCloudBase/CloudBase-MCP)
(`plugin/cloudbase/`, Open Plugin Spec artifacts only).

A CNB mirror is synced the same way as [cloudbase-skills](https://github.com/TencentCloudBase/cloudbase-skills):
this repo's `.github/workflows/sync-to-cnb.yml` mirrors to
[https://cnb.cool/tencent/cloud/cloudbase/cloudbase-plugin](https://cnb.cool/tencent/cloud/cloudbase/cloudbase-plugin).

Claude Code / Codex native marketplace install continues to use the main
[CloudBase-MCP](https://github.com/TencentCloudBase/CloudBase-MCP) repository.

## Installation

```bash
# Default (GitHub)
npx plugins add TencentCloudBase/cloudbase-plugin -y --scope user

# Fallback when GitHub clone fails (CNB mirror — use full URL; short owner/repo always hits GitHub)
npx plugins add https://cnb.cool/tencent/cloud/cloudbase/cloudbase-plugin.git -y --scope user
```

## Open Plugin Specification

This plugin conforms to the [Open Plugin Specification v1.0.0](https://open-plugins.com/plugin-builders/specification).

## License

MIT
