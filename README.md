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

## License

MIT — See LICENSE file.

## Note

The exampleSite content was generated with AI assistance.