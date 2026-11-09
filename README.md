# Stealth Pro — Cloudflare Shield

**Stealth Pro** is a complete, production Cloudflare **WAF custom rule pack** that blocks secret-file scanners and config probes at the edge — with **safe matching** that keeps ACME challenges, docs, and real pages online.

| | |
|---|---|
| **Product** | Cloudflare Shield · Stealth Pro |
| **Author** | Imran Ahmed |
| **License** | MIT |
| **Demo site** | [`index.html`](./index.html) |
| **Rule pack** | [`rules/stealth-pro.txt`](./rules/stealth-pro.txt) |
| **Support / future work** | [imrandev.bd/contact](https://imrandev.bd/contact) |

---

## Dashboard preview

![Stealth Pro radar dashboard](docs/images/dashboard-overview.svg)

---

## Features

- Blocks `.env*`, backups, dumps, keys, htpasswd/htaccess probes
- Blocks `/.git/`, `/.aws/`, `/.azure/`, `/.vscode/`, `/.idea/`, `/.ssh/`
- Protects against `wp-config.php` and `server-status` probes
- **Does not** blanket-block `.md`, `.map`, or `/.well-known` (ACME-safe)
- Zero origin deploy — paste into Cloudflare Custom Rules → **Block**

---

## Install

1. Cloudflare Dashboard → domain → **Security → WAF → Custom rules**
2. Create rule → Expression editor
3. Paste [`rules/stealth-pro.txt`](./rules/stealth-pro.txt)
4. Action: **Block** → Deploy

---

## File structure

```text
index.html              Product website
rules/stealth-pro.txt   Full production expression
waf-rules.txt           Compact compatibility copy
docs/images/            README dashboard visual
LICENSE                 MIT
```

---

## Author — Imran Ahmed

| Platform | Link |
|----------|------|
| Portfolio | [imrandev.bd](https://imrandev.bd) |
| Contact / hire | [imrandev.bd/contact](https://imrandev.bd/contact) |
| Email | [me@imrandev.bd](mailto:me@imrandev.bd) |
| WhatsApp | [+880 1576-918420](https://wa.me/8801576918420) |
| LinkedIn | [linkedin.com/in/imranbru99](https://linkedin.com/in/imranbru99) |
| GitHub | [github.com/imranbru99](https://github.com/imranbru99) |
| X / Twitter | [@imrandev_bd](https://x.com/imrandev_bd) |
| YouTube | [@ImranDevBD](https://youtube.com/@ImranDevBD) |
| Instagram | [@imranbru99](https://instagram.com/imranbru99) |
| Facebook | [ExpertImranDev](https://facebook.com/ExpertImranDev) |
| TikTok | [@imrandev_bd](https://tiktok.com/@imrandev_bd) |
| Threads | [@imranbru99](https://www.threads.net/@imranbru99) |
| Pinterest | [@imrandev_bd](https://pinterest.com/imrandev_bd) |
| All links | [linktr.ee/ExpertImranDev](https://linktr.ee/ExpertImranDev) |

---

© Imran Ahmed · Stealth Pro · Future development: [imrandev.bd/contact](https://imrandev.bd/contact) · [me@imrandev.bd](mailto:me@imrandev.bd) · WhatsApp [+880 1576-918420](https://wa.me/8801576918420)
