## ADDED Requirements

### Requirement: Hugoplate Theme Installation
The site MUST use the Hugoplate theme instead of Ananke.

#### Scenario: Site uses Hugoplate
- **WHEN** the site is built or served
- **THEN** it renders using the Hugoplate theme layouts and assets.

### Requirement: Front Matter compatibility
The site's content MUST be compatible with Hugoplate's Front Matter schema.

#### Scenario: Services are displayed correctly
- **WHEN** navigating to the services pages
- **THEN** the content renders appropriately without front-matter related build errors.