![Logan Bresnahan — LLM integration engineer](assets/hero.svg)

---

## Projects

### [pharos-mcp](https://github.com/LoganBresnahan/pharos-mcp) · Gleam, Elixir, Erlang

An MCP server that exposes Language Server Protocol (LSP) capabilities. Utilizes the BEAM (Erlang Virtual Machine) to supervise multiple LSP servers for a polyglot environment. Distributed as a single self-contained binary via [Burrito](https://github.com/burrito-elixir/burrito), shipped through GitHub Releases and npm.

### [DeepSeek-Moby](https://github.com/LoganBresnahan/DeepSeek-Moby) · TypeScript, VS Code

A fully agentic AI coding assistant for VS Code, inspired by and built for DeepSeek. Streams native tool calls; shell-command approval system with allow/blocklists; conversation forking; Tavily and SearXNG-backed web search, and so much more. OpenAI-compatible BYOM. [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=LoganBresnahan.deepseek-moby).

### [j_r_r_token](https://github.com/LoganBresnahan/j_r_r_token) · Ruby + Rust

Ruby bindings for [tiktoken-rs](https://github.com/zurawiki/tiktoken-rs) — *Just Ruby, Rust, & Tokens*. Ships pre-compiled native extensions, so end users skip the Rust toolchain. Published to [RubyGems](https://rubygems.org/gems/j_r_r_token).

### [birds-of-paradise-zed](https://github.com/LoganBresnahan/birds-of-paradise-zed) · Zed

The only theme I will use. A warm, brown-based, light-on-dark theme for the Zed Editor — the latest link in a chain that started with Joe Bergantine's original Coda theme. Published on the Zed extension registry.

---

## Open source contributions

- **[gleam-lang/gleam#5702](https://github.com/gleam-lang/gleam/pull/5702)** — fixed `gleam publish` writing the wrong OTP application name into hex metadata when the hex package name differed from the OTP app name. Matched the pattern rebar3 uses for transitive-dep resolution. *Merged.*
- **[JuliusBrussee/cavemem#16](https://github.com/JuliusBrussee/cavemem/pull/16)** — diagnosed and fixed `cavemem mcp` exiting silently: the CLI dispatched via dynamic import while the server bootstrap was guarded behind an `isMainEntry()` check that returns false for non-entrypoint loads. *Merged.*
- **[zed-industries/extensions#6151](https://github.com/zed-industries/extensions/pull/6151)** — added Birds of Paradise to the official Zed extension registry. *Merged.*
- **[synrc/fs#68](https://github.com/synrc/fs/pull/68)** — fixed a spurious "macOS 10.7 or later required" error caused by relying on the deprecated Gestalt Manager when run on macOS 11+. *Merged.*

---

Working in: **Eixir · Ruby · TypeScript · Rust · Gleam · Erlang**

Reach me: [github](https://github.com/LoganBresnahan) · [loganbbres@gmail.com](mailto:loganbbres@gmail.com)
