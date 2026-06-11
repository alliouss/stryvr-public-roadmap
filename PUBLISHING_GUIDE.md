# Publishing Guide

Use this guide to share STRYVR publicly without exposing the private app repository.

## Recommended GitHub Setup

Create a separate public repository:

```text
alliouss/stryvr-public-roadmap
```

Keep the main application repository private.

## What To Publish

Safe public content:

- Product vision
- Public roadmap
- Milestone updates
- Screenshots
- Short demo videos or GIFs
- Non-sensitive changelog
- Public beta progress
- Waitlist or contact links

## What Not To Publish

Keep private:

- Source code
- API functions
- Base44 entities and app internals
- OpenAI prompts
- Polar or wearable sync implementation details
- Authentication logic
- Database structure
- Scoring formulas that are proprietary
- API keys, tokens, secrets, callback URLs, and environment files

## Suggested Repository Structure

```text
stryvr-public-roadmap/
  README.md
  ROADMAP.md
  PROJECT_STATUS.md
  CHANGELOG.md
  media/
    screenshots/
    demos/
```

## Suggested GitHub Settings

- Repository visibility: Public
- Issues: Optional
- Discussions: Recommended
- Wiki: Optional
- GitHub Pages: Recommended later

## Suggested Public README Message

STRYVR is being built in public at the product level while the application source remains private during active development.

This protects user-data systems, wearable integrations, and proprietary reliability work while still letting the community follow progress.

## Posting Rhythm

Recommended update rhythm:

- Weekly roadmap update
- Monthly changelog
- Short demo after each meaningful product milestone
- Public beta notes once testing opens
