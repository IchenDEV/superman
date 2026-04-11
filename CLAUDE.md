# Superman — Claude Plugin Config

This project is a collection of 58 thinking framework skills. Each skill in `skills/` is a cognitive perspective distilled from a real person or domain using the **Nuwa v4.0** standard from [alchaincyf/nuwa-skill](https://github.com/alchaincyf/nuwa-skill).

## Installation (Claude Code)

To use these perspectives as a plugin in Claude Code:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/IchenDEV/superman.git
    ```
2.  **Load the plugin**:
    Inside a Claude Code session, use:
    ```bash
    /plugin install /absolute/path/to/superman
    ```
    *Alternatively, start Claude with the plugin directory:*
    ```bash
    claude --plugin-dir /absolute/path/to/superman
    ```

## Skills Available

Claude Code automatically discovers skills in the `skills/` directory. Each skill is namespaced as `superman-perspectives:[skill-name]`.

Example triggers:
- `superman-perspectives:confucius-perspective` - 社会契约、正名、和而不同
- `superman-perspectives:turing-perspective` - 计算理论、逻辑审计、可验证性
- `superman-perspectives:miyamoto-perspective` - 游戏设计、玩法体验、Nintendo

## Conventions

- Each skill directory is self-contained — `SKILL.md` plus `references/`
- Skill files use frontmatter for discovery: `name`, `description`, `type: perspective`
- All skills follow the **Nuwa** 3D distillation standard (DNA, Profile, Logic)
