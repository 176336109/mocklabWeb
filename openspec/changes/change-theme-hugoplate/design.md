## Context
The OPC (One-Person Company) site is currently running on the Ananke theme. We want to upgrade to the Hugoplate theme (https://themes.gohugo.com.cn/themes/hugoplate/) to provide a more modern and tailored appearance.

## Goals / Non-Goals
**Goals:**
- Replace Ananke with Hugoplate as the core Hugo theme.
- Ensure the site still builds correctly via hugo server.
- Configure the homepage and services pages appropriately for the new theme's layout engine.

**Non-Goals:**
- Modifying the underlying OPC business text.
- Developing custom Hugo templates (unless strictly required by the theme).

## Decisions
- **Theme Installation:** Download the Hugoplate theme and place it in the \	hemes/hugoplate\ folder. Alternatively use git submodule if the repository is provided.
- **Configuration Migration:** We will switch the 	heme variable in hugo.toml to hugoplate and copy over any essential Hugoplate configuration boilerplate (tailored modules, params).
- **Content Adaptation:** Adjust the Front Matter in content/_index.md and the services/ directory to match Hugoplate's expected structure (like _index.md for sections and blocks).

## Risks / Trade-offs
- **Risk:** Existing Markdown front matter might not play well with the new theme's expected variables (e.g. menu behavior can differ).
  - **Mitigation:** We'll review the Hugoplate documentation and adjust the Front Matter during implementation.
- **Risk:** Local server build failure. 
  - **Mitigation:** Run hugo server locally to catch errors immediately.
