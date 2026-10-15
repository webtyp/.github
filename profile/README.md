# WebTyp

### Software you cultivate, not software that piles up.

Full-stack web applications in **Go** — backend, frontend and shared logic in one language, compiled to the browser as small WebAssembly. Typed components, simple architecture, for humans and for AI.

👉 **Start here:** [**webtyp/app**](https://github.com/webtyp/app) — install the `webtyp` binary and build. **Why it exists, who it's for and its honest limits:** [**WHY.md**](https://github.com/webtyp/app/blob/main/docs/WHY.md) · [Español](https://github.com/webtyp/app/blob/main/docs/WHY.es.md)

---

## Why you might love it

- 🟦 **One language everywhere** — share types, validation and logic across client and server. No TypeScript, no npm, no bundlers.
- 🧱 **Typed components** — a component is a Go type; the compiler checks how components fit together.
- 🔧 **Simple architecture** — the project layout *is* the configuration. Conventions, without magic.
- 🤖 **Human or AI** — the TUI (`webtyp dev`) and the MCP daemon (`webtyp mcp`) drive the same project, so a developer or an agent builds inside the same structure.
- 🪶 **Tiny WASM** — TinyGo-first, with lightweight replacements for `fmt`, `json` and `time` that keep the browser binary small.

---

## Packages

The libraries you'll use to build apps. The **Activity** badge shows each repo's last commit, pulled live from GitHub — click it to open that library's history.

| Package | Description | Activity |
| :--- | :--- | :--- |
| [app](https://github.com/webtyp/app) | Full stack TUI development environment with live reload, test, deploy, CI/CD for web applications (PWA). | [![last commit](https://img.shields.io/github/last-commit/webtyp/app?label=&color=2ea44f)](https://github.com/webtyp/app/commits) |
| [binary](https://github.com/webtyp/binary) | High-performance binary serialization library for Go, specifically designed for TinyGo compatibility. | [![last commit](https://img.shields.io/github/last-commit/webtyp/binary?label=&color=2ea44f)](https://github.com/webtyp/binary/commits) |
| [components](https://github.com/webtyp/components) | HTML components for the WebTyp Go web framework. | [![last commit](https://img.shields.io/github/last-commit/webtyp/components?label=&color=2ea44f)](https://github.com/webtyp/components/commits) |
| [context](https://github.com/webtyp/context) | Minimalist context library for TinyGo. | [![last commit](https://img.shields.io/github/last-commit/webtyp/context?label=&color=2ea44f)](https://github.com/webtyp/context/commits) |
| [crypto](https://github.com/webtyp/crypto) | CryptoAutoLib port for TinyGo. | [![last commit](https://img.shields.io/github/last-commit/webtyp/crypto?label=&color=2ea44f)](https://github.com/webtyp/crypto/commits) |
| [deploy](https://github.com/webtyp/deploy) | Automated deployment service for Go applications. | [![last commit](https://img.shields.io/github/last-commit/webtyp/deploy?label=&color=2ea44f)](https://github.com/webtyp/deploy/commits) |
| [devflow](https://github.com/webtyp/devflow) | Complete Go development automation: project init, testing, versioning, updates, and backups. | [![last commit](https://img.shields.io/github/last-commit/webtyp/devflow?label=&color=2ea44f)](https://github.com/webtyp/devflow/commits) |
| [dom](https://github.com/webtyp/dom) | Ultra-minimal DOM & event toolkit for Go (TinyGo WASM-optimized). | [![last commit](https://img.shields.io/github/last-commit/webtyp/dom?label=&color=2ea44f)](https://github.com/webtyp/dom/commits) |
| [fetch](https://github.com/webtyp/fetch) | A lightweight Go library that unifies HTTP requests across environments. | [![last commit](https://img.shields.io/github/last-commit/webtyp/fetch?label=&color=2ea44f)](https://github.com/webtyp/fetch/commits) |
| [fmt](https://github.com/webtyp/fmt) | Lightweight Go library that provides comprehensive string manipulation and formatting. | [![last commit](https://img.shields.io/github/last-commit/webtyp/fmt?label=&color=2ea44f)](https://github.com/webtyp/fmt/commits) |
| [form](https://github.com/webtyp/form) | Form generation using DOM and structs. | [![last commit](https://img.shields.io/github/last-commit/webtyp/form?label=&color=2ea44f)](https://github.com/webtyp/form/commits) |
| [goflare](https://github.com/webtyp/goflare) | Lightweight handler for building and deploying Go-based WebAssembly and JavaScript modules to Cloudflare. | [![last commit](https://img.shields.io/github/last-commit/webtyp/goflare?label=&color=2ea44f)](https://github.com/webtyp/goflare/commits) |
| [imagemin](https://github.com/webtyp/imagemin) | Image size reduction tool for web projects. | [![last commit](https://img.shields.io/github/last-commit/webtyp/imagemin?label=&color=2ea44f)](https://github.com/webtyp/imagemin/commits) |
| [indexdb](https://github.com/webtyp/indexdb) | IndexDB implementation with WebAssembly compiled with Go. | [![last commit](https://img.shields.io/github/last-commit/webtyp/indexdb?label=&color=2ea44f)](https://github.com/webtyp/indexdb/commits) |
| [json](https://github.com/webtyp/json) | A lightweight JSON wrapper for Go that optimizes WebAssembly binary size. | [![last commit](https://img.shields.io/github/last-commit/webtyp/json?label=&color=2ea44f)](https://github.com/webtyp/json/commits) |
| [jsvalue](https://github.com/webtyp/jsvalue) | Efficient conversions between JavaScript and Go for a WebAssembly environment. | [![last commit](https://img.shields.io/github/last-commit/webtyp/jsvalue?label=&color=2ea44f)](https://github.com/webtyp/jsvalue/commits) |
| [kvdb](https://github.com/webtyp/kvdb) | TinyGo–compatible key–value store with a minimal API. | [![last commit](https://img.shields.io/github/last-commit/webtyp/kvdb?label=&color=2ea44f)](https://github.com/webtyp/kvdb/commits) |
| [mcp](https://github.com/webtyp/mcp) | Go implementation of the Model Context Protocol (MCP). | [![last commit](https://img.shields.io/github/last-commit/webtyp/mcp?label=&color=2ea44f)](https://github.com/webtyp/mcp/commits) |
| [pdf](https://github.com/webtyp/pdf) | PDF library designed for web rendering with WebAssembly, optimized for TinyGo compatibility. | [![last commit](https://img.shields.io/github/last-commit/webtyp/pdf?label=&color=2ea44f)](https://github.com/webtyp/pdf/commits) |
| [postgres](https://github.com/webtyp/postgres) | PostgreSQL adapter implementing the `webtyp/orm` Adapter interface. | [![last commit](https://img.shields.io/github/last-commit/webtyp/postgres?label=&color=2ea44f)](https://github.com/webtyp/postgres/commits) |
| [sqlite](https://github.com/webtyp/sqlite) | WebAssembly-first port of modernc.org/sqlite. | [![last commit](https://img.shields.io/github/last-commit/webtyp/sqlite?label=&color=2ea44f)](https://github.com/webtyp/sqlite/commits) |
| [sse](https://github.com/webtyp/sse) | Client and event server, SSE protocol compatible with TinyGo. | [![last commit](https://img.shields.io/github/last-commit/webtyp/sse?label=&color=2ea44f)](https://github.com/webtyp/sse/commits) |
| [time](https://github.com/webtyp/time) | TinyGo-compatible time package for Go. | [![last commit](https://img.shields.io/github/last-commit/webtyp/time?label=&color=2ea44f)](https://github.com/webtyp/time/commits) |
| [unixid](https://github.com/webtyp/unixid) | Go library for generating unique, time-based IDs using Unix timestamps. | [![last commit](https://img.shields.io/github/last-commit/webtyp/unixid?label=&color=2ea44f)](https://github.com/webtyp/unixid/commits) |
| [user](https://github.com/webtyp/user) | User management library. | [![last commit](https://img.shields.io/github/last-commit/webtyp/user?label=&color=2ea44f)](https://github.com/webtyp/user/commits) |

---

## Follow the project

WebTyp is in active development by one person ([@cdvelop](https://github.com/cdvelop)) and is being proven on a real application before a wider release.

- 👀 Follow releases: [webtyp/app](https://github.com/webtyp/app) → *Watch → Custom → Releases*.
- ⭐ Star the libraries you find useful — it helps others discover the ecosystem.
