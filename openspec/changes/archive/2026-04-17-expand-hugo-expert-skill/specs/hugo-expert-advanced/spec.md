## ADDED Requirements

### Requirement: hugo-expert-advanced
The `hugo-expert` skill MUST support advanced Hugo topics and assist users in complex site configuration, development, optimization, and deployment.

#### Scenario: Support Template and Logic (模板/函数/方法/变量)
- **WHEN** the user needs assistance with creating or modifying Hugo themes or templates
- **THEN** the skill provides advanced examples using Hugo template syntax (Go text/template), built-in functions, variables, and custom shortcodes.

#### Scenario: Support Asset Pipeline (Hugo模块/Hugo管道)
- **WHEN** the user asks how to manage assets, SCSS/JS bundling, or dependencies
- **THEN** the skill explains how to configure and use Hugo Modules and Hugo Pipes (`resources.Get`, `resources.Minify`, etc.) effectively.

#### Scenario: Support Advance CLI & Troubleshooting (命令行/故障排除/开发者工具)
- **WHEN** the user encounters build errors, needs verbose logging, or wants to profile the build
- **THEN** the skill provides commands like `hugo server --gc --minify --cleanDestinationDir` or `hugo --templateMetrics --logLevel debug` to troubleshoot and optimize the site.

#### Scenario: Support Hosting and Deployment (托管和部署)
- **WHEN** the user asks how to deploy the generated `public/` folder to platforms like Netlify, Vercel, or GitHub Pages
- **THEN** the skill provides specific deployment configuration examples (e.g., `netlify.toml`, `.github/workflows/gh-pages.yml`) and guidance.
