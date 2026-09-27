<h1 align="center">NigaByte</h1>
<p align="center"><em>Browser extensions · self-hosted tooling · automation</em></p>

I build small, dependency-light software that does one job properly — and I care most about the
unglamorous parts: what leaves your machine, what happens when a server dies, and whether the
interface still makes sense in a second language.

## Featured project

### [Proxy Switch](https://github.com/NigaByte031/Proxy-Switch) — one-click proxy switching for Chrome

A Manifest V3 extension that moves the browser between **system, direct, manual HTTP/SOCKS and PAC**
proxies without a reload, and keeps the choice honest.

- **Domain routing** — only the sites you list take the proxy. The rules are compiled into a PAC
  script and handed to Chrome as text (`pacScript.data`) instead of being downloaded, so a listed
  site is never quietly sent direct.
- **Automatic failover** — a stop answering streak only makes a route *worth checking*; a probe has
  to fail before anything switches. One round visits each server once, then stops cleanly.
- **Bilingual UI** — English and Persian (فارسی) with full RTL support, plus offline preview pages
  that render the popup and settings without loading the extension.
- **Nothing hidden** — no telemetry, zero dependencies, vanilla JavaScript, MIT licensed, and a
  test suite that runs with `npm test` after a clone, no install step.

`JavaScript` · `Manifest V3` · `chrome.proxy` · `SOCKS5` · `PAC` · `i18n / RTL`

## What I work with

| | |
| --- | --- |
| **Languages** | JavaScript (vanilla and Node), Python, HTML/CSS |
| **Browser** | Chrome extensions — Manifest V3, service workers, `chrome.proxy`, storage and alarms |
| **Backend** | Node.js, Express, SQLite, Docker, Caddy with automatic HTTPS |
| **Frontend** | Responsive, RTL-aware UI built without a framework |
| **Habits** | Privacy-first defaults, real i18n, self-hosting over SaaS |

## Also building

- **Orbit Panel** — a self-hosted VPN user-management panel: VLESS/VMess/Trojan/Shadowsocks clients
  with traffic quotas and expiry, QR links, live stats and a built-in security audit.
  Node.js + Express + SQLite, shipped with Docker and automatic HTTPS.
- **User Information** — a modular Python Telegram bot that collects and manages user profiles
  through a seven-language interface, with admin broadcast and structured logging.

*Both are private for now; happy to walk through them on request.*

---

Most of what I learn comes out of shipping and then fixing — if something here was useful, or you
spotted a bug, open an issue and tell me about it.
