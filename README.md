# TTY Theme

A minimal, lightweight Hugo theme inspired by the Linux console, featuring the Ayu Dark color scheme.

## Quick Start

```bash
hugo new site mysite
cd mysite
git submodule add https://github.com/on3iropolos/hugo-theme-tty.git themes/tty
echo "theme: tty" >> config.yaml
hugo server
```

Open http://localhost:1313 to view the site.

## Configuration

Add to `config.yaml`:

```yaml
theme: tty
params:
  tty:
    username: user
    hostname: hostname
```

### Theme Params

| Param | Description | Default |
|-------|-------------|---------|
| `tty.username` | Shell username in prompt | `user` |
| `tty.hostname` | Shell hostname in prompt | - |
| `tty.path` | Current path in prompt | `~` |
| `tty.showTerminalHeader` | Show "~/path" terminal header on pages | `true` |
| `tty.showLatestPosts` | Show latest posts on homepage | `true` |
| `tty.showPostsList` | Show posts in list views | `true` |

### Custom ASCII Art

Create an `ascii-art.txt` file in your project's root directory to display custom ASCII art in the terminal header. You can generate ASCII art at [patorjk.com/software/taag](https://patorjk.com/software/taag).

If `ascii-art.txt` is not present, the theme displays a default ASCII art logo.

## License

MIT — See LICENSE file.

## Note

The exampleSite content was generated with AI assistance.