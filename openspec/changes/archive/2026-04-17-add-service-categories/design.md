## Context

The Hugo OPC website was created successfully and has content pages for two key services (`technical-co-running.md` and `agent-transformation.md`). However, there are currently no main navigation items to let visitors navigate directly to these pages from the site header.

## Goals / Non-Goals

**Goals:**
- Update the navigation to include two new items: "创业技术陪跑" and "企业Agent构建".
- These should point directly to the existing markdown pages.

**Non-Goals:**
- Creating new complex sub-menus or a heavily customized new theme layout.

## Decisions

- **Hugo Menus**: We will add the pages to Hugo's main menu array. This is elegantly handled by modifying the front matter of the existing markdown service files (`content/services/technical-co-running.md` and `content/services/agent-transformation.md`) directly.
- By defining `menu: main` and an optional `weight` property in the markdown files, the Ananke theme will automatically render them at the top.

## Risks / Trade-offs

- The Ananke theme renders all main menu items. If we have too many, the header will wrap. two items are fine.