## Why

The current `hugo-expert` skill focuses only on the basic "Getting Started" guide of Hugo. It lacks coverage of advanced and high-level Hugo usages (such as Templates, Functions, Variables, Hugo Modules, Hugo Pipes, etc.), which are essential for a true "Hugo Expert" to assist users with complex site building, theme customization, and deployment workflows. Expanding the skill will make the assistant much more capable and helpful.

## What Changes

- Update the `hugo-expert` SKILL.md to include advanced topics.
- Add sections on Hugo Templates (模板), Functions & Methods (函数/方法), and Variables (变量).
- Add knowledge about Hugo Modules (Hugo模块) and Hugo Pipes (Hugo管道) for asset processing.
- Add information on Hosting and Deployment (托管和部署) and Troubleshooting (故障排除).
- Provide examples of advanced CLI usage.

## Capabilities

### New Capabilities
- `hugo-expert-advanced`: Expand the `hugo-expert` skill to cover high-level usages of Hugo, enabling the assistant to guide users in template editing, asset pipelines, and modules.

### Modified Capabilities

- No existing capabilities are being modified at the specification level (since we are just expanding a single `.github/skills/hugo-expert/SKILL.md` file).

## Impact

- `d:\HoGo\MockWeb\.github\skills\hugo-expert\SKILL.md` will be significantly expanded.
- The assistant's behavior when acting as a Hugo Expert will cover much more ground, allowing better support for advanced Hugo developers.
