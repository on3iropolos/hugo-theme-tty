# TTY Theme — Agent Guide

## Project

Hugo theme — terminal-inspired design.

- **Repository**: github.com/on3iropolos/hugo-theme-tty
- **License**: MIT

## Theme Structure

| Directory | Purpose |
|-----------|----------|
| `layouts/` | Hugo templates |
| `static/tty/` | CSS and JS assets |
| `archetypes/` | Content archetypes |
| `i18n/` | Internationalization |
| `exampleSite/` | Example configuration |

## Theme Parameters

| Parameter | Description | Default |
|-----------|-------------|---------|
| `tty.username` | Shell username | - |
| `tty.hostname` | Shell hostname | - |

## Development

### Testing the Theme

```bash
# Using exampleSite
cd exampleSite
hugo server -D
```

### Building Assets

The theme uses plain CSS. No build steps required.

## Standards

- **Hugo Version**: 0.160.1+
- **Features**: Standard Hugo (no extended features required)
- **CSS**: Plain CSS, no preprocessing