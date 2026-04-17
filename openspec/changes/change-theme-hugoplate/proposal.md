## Why

We want to change the Hugo theme of the website to Hugoplate (https://themes.gohugo.com.cn/themes/hugoplate/) to provide a better, more modern UI for the opc-company-site.

## What Changes

- Remove the existing Ananke theme.
- Download and configure the new Hugoplate theme as a submodule or standard Hugo theme within the opc-company-site/themes/ directory.
- Update the hugo.toml configuration to use the new theme.
- Migrate any theme-specific configuration or front matter.

## Capabilities

### New Capabilities
- 	heme-hugoplate: Implementation of the Hugoplate theme for the opc-company-site.

### Modified Capabilities
- opc-landing-page: Refactoring the landing page to work perfectly with the new Hugoplate theme components.

## Impact

- hugo.toml will be updated with new theme settings.
- Markdown content inside opc-company-site/content might need front-matter updates for compatibility.
- Git submodule for Ananke will be removed.