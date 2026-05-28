# ERP Linker OdooSync — Landing Page

Marketing site for **OdooSync Lite** and **OdooSync Pro**, built with Jekyll and deployed to GitHub Pages via GitHub Actions.

Live site: https://ackm04.github.io/erplinker-odoosync-website/

## Requirements

- **Ruby 3.0+** (macOS system Ruby 2.6 is too old)
- Bundler

Install Ruby 3.3 with Homebrew (recommended — avoids macOS system Ruby 2.6):

```bash
brew install ruby@3.3
export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"
```

## Local preview

```bash
cd /Volumes/projects/erplinker-odoosync-website
chmod +x bin/serve
bin/serve
```

Or manually:

```bash
bundle install
bundle exec jekyll serve
```

Open http://127.0.0.1:4000/erplinker-odoosync-website/

## Deploy

Pushes to `main` run `.github/workflows/pages.yml` using `actions/jekyll-build-pages`.

GitHub **Settings → Pages → Build and deployment** should use **GitHub Actions**.

## Related repositories

- [OdooSync Lite](https://github.com/ackm04/erplinker-odoosync-lite) — free, open source

## Sponsor links

| Channel | URL |
|---------|-----|
| Buy Me a Coffee | https://www.buymeacoffee.com/ackm04 |
| GitHub Sponsors | https://github.com/sponsors/ackm04 |
| Ko-fi | https://ko-fi.com/ackm04 |
| PayPal | https://paypal.me/officialajayindia |

**Sponsor perk:** $19+ sponsorship → **24-hour OdooSync Pro evaluation**. Details on the live site [#support](https://ackm04.github.io/erplinker-odoosync-website/#support) section.

GitHub `FUNDING.yml` is in `.github/FUNDING.yml` for the Sponsor button on the repository.

