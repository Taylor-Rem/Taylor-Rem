# Taylor Remund

Full-stack engineer in American Fork, Utah. I build with LLMs and agents, and
I ship whole products on my own.

**Day job:** at a property-management company since June 2023, a software
developer on its Laravel, Vue and MySQL platform since November 2024. I own projects from the data model
to the rollout: the resident-ledger system and its allocation engine, a
rewrite of the company-wide support desk, and a Flutter inspections app. I
started on the support team, automating its work in Python (below), and later
rebuilt that work as platform features.

**[Patchlamp](https://github.com/Taylor-Rem/patchlamp)**: a website you
change by texting it. The owner texts a number; Patch opens the site's files,
makes the change, checks that it is live and texts back, usually in a minute.
A Laravel site, a Python relay that runs Claude Code inside one client's
folder under that folder's permissions, and a toolbelt of small CLIs. Live at
[patchlamp.com](https://patchlamp.com); I build and run it, working with
Claude. The code is the business, so the overview repo is the part you can
read.

**[Artificer](https://github.com/Taylor-Rem/artificer)**: a self-hosted agent
system in Rust. An orchestrator agent plans, delegates to specialist agents
and keeps its task state in SQLite, outside the transcript, so a specialist
never replays its own history. A GPU pool hands user requests and background
jobs to the GPUs listed in a config file. Three crates, about 6,200 lines of
Rust. Built January to March 2026; dormant since.

**[Sharewire](https://github.com/Taylor-Rem/sharewire)**: a self-hosted
music-sharing app (Laravel 13, Vue 3, Inertia), built for an interview on a
2.5-day deadline. Skinny controllers, Action classes and policies, no raw SQL
in the app layer, and 110 Pest tests, all passing (measured November 2026).
Not maintained since May 2026.

**[db](https://github.com/Taylor-Rem/db)**: a small embedded database engine in
Rust, written to learn what sits under SQL: on-disk B+ trees, paged storage,
an LRU page cache, secondary indexes. Learning-scale; built February to June
2026.

**Automation at work:** [support_tool](https://github.com/Taylor-Rem/support_tool)
and [utilities-master](https://github.com/Taylor-Rem/utilities-master), PyQt5
desktop apps that drive property-management and utility-vendor portals with
Selenium, built for my employer, 2023 to 2025.

**Stack:** Rust (Tokio, Axum), PHP and Laravel with Vue and Pest, Python;
SQLite, PostgreSQL, MySQL.

**How I work with AI:** I run a multi-agent setup (Claude Code, Cursor, MCP
servers, custom skills) and own the architecture, the review and the
verification.

Résumé: [taylorremund.com/resume](https://taylorremund.com/resume/)
