# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Jekyll-based static academic website for Peter Höfner (Associate Professor, ANU), built on the Beautiful Jekyll theme (v6.0.1). No Node/npm — pure Ruby/Jekyll stack.

## Commands

```bash
bundle install                   # Install dependencies
bundle exec jekyll serve         # Dev server at http://localhost:4000
bundle exec jekyll build         # Production build → _site/
bundle exec jekyll clean         # Remove _site/ and .jekyll-cache/
```

## Architecture

**Collections** (defined in `_config.yml`):
- `_publications/` — 150+ files, each generates its own page at `/publications/:name`
- `_teaching/` — 28 files, rendered only via the teaching overview page (no individual pages)
- `_people/` — 80 files, rendered only via the people overview page (no individual pages)
- `_grants/` — one file per grant; rendered only via the CV "Grants" section (`_cv/09-grants.md`)

**Layouts** (`_layouts/`): Custom templates including `publication.html`, `cv.html`, `people.html`, `teaching-overview.html`. These override Beautiful Jekyll defaults.

**Theme overrides**: Customization lives in `_config.yml`, `_layouts/`, and `_includes/`. The gem (`beautiful-jekyll-theme`) provides the base; local files take precedence.

**Assets**: `assets/pdf/`, `assets/pdf_original/`, `assets/pdf_theses/` hold 250+ PDFs linked from publication entries.

## Content Front Matter Conventions

Publications use fields like `title`, `venue`, `year`, `authors`, `pdf`, `abstract`. Teaching entries use `title`, `type`, `year`. People entries include `name`, `role`, `image`. Check existing entries in the respective `_` directories before adding new ones to match the established schema.

## Key Config (`_config.yml`)

- Timezone: `Australia/Canberra`
- Collections output: publications → `true` (individual pages), teaching/people → `false`
- Plugins: `jekyll-paginate`, `jekyll-sitemap`
- Comments, analytics, and search are all disabled
