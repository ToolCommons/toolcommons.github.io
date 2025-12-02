# Contributing to Tool Commons

Tool Commons is a directory of free, open-source, single-purpose web tools. We welcome submissions from anyone who has built a tool that meets our criteria.

## Submitting a Tool

To submit a tool for inclusion:

1. **Verify your tool meets all criteria** (see below)
2. **Open an issue** using the [Submit a Tool](https://github.com/ToolCommons/toolcommons.github.io/issues/new?template=submit-tool.md) template
3. **Fill out all fields** in the template
4. **Wait for review** - We'll review your submission and may ask questions

## Criteria for Inclusion

Every tool listed on Tool Commons must meet these requirements:

### Open Source
- Code must be publicly available
- Must use an [OSI-approved license](https://opensource.org/licenses/)
- Repository must be accessible (GitHub, GitLab, etc.)

### No Login Required
- Core functionality must work without creating an account
- Optional accounts for saving preferences are acceptable, but not required for basic use

### Local-First
- User data must stay in the browser by default
- No data sent to servers unless the user explicitly exports/shares
- If data is sent anywhere, it must be clearly disclosed

### No Ads, No Tracking
- No advertisements
- No surveillance-style tracking (no user IDs, no behavior tracking)
- Privacy-respecting analytics are acceptable (aggregate, anonymous data only)
- See our [analytics guidelines](https://github.com/mickdarling/merview/issues/74) for what's acceptable

### Static Hostable
- Must be able to run from static hosting (GitHub Pages, Netlify, Cloudflare Pages, etc.)
- No required backend servers (optional backends for specific features are okay if core works without them)

### Single Purpose
- Tool should do one thing well
- Focused functionality over feature bloat
- Users should understand what the tool does within seconds of landing on it

## Adding the Tool Commons Badge

Once your tool is listed, you can add a Tool Commons badge to show users it meets our criteria:

```html
<a href="https://toolcommons.org">
  <img src="https://toolcommons.org/badge.svg" alt="Tool Commons">
</a>
```

## Contributing to the Site Itself

If you want to improve Tool Commons itself:

1. Fork the repository
2. Make your changes
3. Submit a pull request

The site is intentionally simple - a single HTML file. Keep it that way.

## Code of Conduct

Be kind. Build useful things. Share them freely.
