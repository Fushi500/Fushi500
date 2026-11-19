# Darius Șerban

Computer Science graduate (2026) from the Petroleum-Gas University of Ploiești, Romania.

I build web applications and run them on my own Linux server. Most of my work is TypeScript and Node.js with PostgreSQL or SQLite, Astro and React on the front end, and Python, C++ or Rust where the problem needs it.

Screenshots and the full write-up of each project are on my portfolio, **[plainsite.dev](https://plainsite.dev/en/)**.

## Client work

Client repositories are private. Each project links to its page on my portfolio.

- **[Dayro Distribution website](https://plainsite.dev/en/projects/dayro-distribution-website/)** (live at [dayrodistribution.com](https://dayrodistribution.com)). A bilingual catalogue and quote-request site for a Romanian distributor of construction fixings. The catalogue lists 277 products in 1,680 variants across 10 categories (November 2026) and shows whether each one is in stock. I host it on my own Ubuntu server.
  Astro, React, TypeScript, Playwright, GitHub Actions.
- **[Ordering app for a field sales team](https://plainsite.dev/en/projects/field-sales-ordering-app/)** (beta). Sales agents take orders on their phones, the office approves them and exports XML for the accounting software. The app never writes to the accounting database. Every read runs in a read-only transaction and an SQL guard blocks writes.
  TypeScript, Fastify, SQLite, Firebird, Kotlin (Android WebView), Vitest.

## My own projects

- **[dualspeakers](https://github.com/Fushi500/dualspeakers)**. Plays the same audio on two Windows outputs and keeps them aligned. Measured with a microphone at the listening position, the median offset is -0.021 ms, with a spread of 0.203 ms over five runs. The project works but is not finished.
  C++20, WASAPI exclusive mode, CMake, 241 tests.
- **[Workspace](https://plainsite.dev/en/projects/workspace/)** (private, in daily use). A self-hosted tracker with pages, tables, boards, a command-line tool and an API.
  TypeScript, Fastify, React, PostgreSQL, Docker Compose.
- **[Macro Micro](https://plainsite.dev/en/projects/macro-micro/)**. A nutrition and fitness tracker for Romania. Version 1 was the subject of my bachelor thesis and is now retired. I am rebuilding version 2 as an Android app.
  Version 1 used Flutter, Fastify, PostgreSQL, Redis, Meilisearch and Docker Compose, with self-hosted models for food photos and nutrition labels.
- **[nutrition-label-llm](https://github.com/Fushi500/nutrition-label-llm)**. A LoRA fine-tune of Qwen2.5-14B that turns OCR text from EU nutrition labels into JSON. The repository holds a synthetic dataset of 50,000 examples (40,000 for training) and the full QLoRA training pipeline.
  Python, Unsloth, TRL.
- **[LayerCure](https://plainsite.dev/en/projects/layercure/)** (in progress). A resin 3D-printing slicer with a desktop app.
  Rust.

Smaller repositories: [exercises-api](https://github.com/Fushi500/exercises-api) (static JSON on GitHub Pages) and [tourism-db](https://github.com/Fushi500/tourism-db) (MariaDB coursework).

## How I work

- I run my own Ubuntu server with systemd services, Docker Compose and Cloudflare Tunnel.
- On client and larger projects, every change goes through a branch, a pull request and automated tests before it reaches `main`. The Dayro site has 31 merged pull requests. Small personal projects I commit directly.
- I use AI coding agents every day. I write the brief and the checks, read what they produce, and test the result on the real system before I call it done.

## Contact

[plainsite.dev](https://plainsite.dev/en/contact/)

serbdari98@gmail.com
