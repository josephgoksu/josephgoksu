# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is Joseph Goksu's personal profile repository, serving as a GitHub profile README and personal branding hub. It contains professional information, resume materials, and automated blog post updates.

## Repository Structure

```
josephgoksu/
├── README.md              # GitHub profile README
├── cover_letter.html      # Cover letter template
├── current_resume.html    # Current resume
├── yearly_plan.md         # Personal yearly planning document
├── dynamic-images/        # Dynamic images for GitHub profile
├── signatures/            # Email signature templates
├── wordings/              # Bio and other text content
└── .github/workflows/     # GitHub Actions workflows
```

## Key Files

- **README.md**: The main GitHub profile page showcasing open source projects and blog posts
- **current_resume.html**: HTML-formatted resume
- **cover_letter.html**: HTML-formatted cover letter template
- **.github/workflows/blog-post-workflow.yml**: Automated workflow that updates README with latest blog posts from josephgoksu.com

## Development Commands

### Formatting

The repository uses Prettier for code formatting with the following configuration:

- Print width: 240 characters
- Single quotes
- Trailing commas (ES5)
- Spaces (not tabs)

To format files manually:

```bash
npx prettier --write "**/*.{html,md,yml}"
```

## GitHub Actions

The repository has an automated workflow that:

- Runs every Monday at 1 PM UTC
- Can be manually triggered via GitHub Actions
- Fetches latest blog posts from https://josephgoksu.com/feed.xml
- Updates the README.md with the 4 most recent posts

## Content Updates

When updating content in this repository:

1. **Profile updates**: Edit README.md directly
2. **Resume updates**: Modify current_resume.html
3. **Blog posts**: Are automatically updated via GitHub Actions (no manual intervention needed)
4. **Bio updates**: Edit files in the wordings/ directory
