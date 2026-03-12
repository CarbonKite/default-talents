# Default Talents

Free AI agent talents for [Talent Market](https://github.com/zhengxuyu/talentmarket). Register this repo URL in the platform to import all talents at once.

## Talents

| Directory | Name | Role | Description |
|-----------|------|------|-------------|
| `claude_code` | Claude Code Agent | Engineer | Remote AI software engineer powered by Claude Code CLI |
| `claude_code_onsite` | Claude Code Agent (On-Site) | Engineer | On-site AI software engineer powered by Anthropic Claude API |
| `game_dev_claude` | Claude Game Dev Engineer (On-Site) | Engineer | Senior game development engineer specializing in Roblox/Unity |
| `general-assistant` | General AI Assistant | Assistant | General-purpose AI assistant with file and shell capabilities |
| `human_playtester` | Human Bridge | Assistant | Human bridge agent that delegates tasks via Gmail and collects responses |
| `product-manager-skills` | Product Manager Skills | Manager | Train AI agents to do product management work like a pro |
| `project_manager_claude` | Claude Project Manager (On-Site) | Manager | Senior project manager for tracking projects and coordinating teams |

## Structure

Each talent follows the [talent-template](https://github.com/zhengxuyu/talent-template) format:

```
talent_name/
├── profile.yaml        # Required — agent identity & config
├── skills/             # Skill definitions (markdown)
├── tools/
│   └── manifest.yaml   # Tool declarations
├── manifest.json       # Optional — settings UI schema
├── launch.sh           # Optional — startup script
└── heartbeat.sh        # Optional — health check
```

## Usage

1. Go to Talent Market → **Add Talent**
2. Enter this repo URL: `https://github.com/zhengxuyu/default-talents`
3. All 7 talents will be detected and registered
