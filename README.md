# Christian Nachtigall

**Developer tooling and AI agents in Go and Rust · near Munich, Germany**

I build developer tools and tooling for AI agents: a terminal coding agent, a
local memory server for coding agents, and a Go SDK for Mistral's agentic APIs.
My work connects Linux systems, practical AI integrations, and local-first
software, with open source at the center.

[Portfolio & case studies](https://nachtigall.dev) · [LinkedIn](https://www.linkedin.com/in/christian-nachtigall/en) · [Email](mailto:hello@nachtigall.dev)

## Selected projects

> ### [gnoma](https://somegit.dev/Owlibou/gnoma)
> **Go · TUI · MCP · LLM routing**
>
> A terminal coding agent that routes prompts across local and cloud models.
> Combines a Go TUI with MCP integration, plugins, and content scanning at model
> and tool boundaries. Currently pre-1.0.

> ### [mindspace](https://github.com/VikingOwl91/mindspace)
> **Rust · SQLite · MCP**
>
> A local-first persistent memory and code search tool for AI coding agents.
> Written in Rust, it stores its data in a local SQLite database and is used
> through the `mind` command-line tool or as a stdio MCP server. Current release:
> `v0.1.0-alpha.2`, a source-only public Alpha for Linux x86_64.

> ### [mistral-go-sdk](https://github.com/VikingOwl91/mistral-go-sdk)
> **Go · Mistral API · MCP · Workflows**
>
> A Go SDK for Mistral's Workflows, Conversations, and Connectors APIs, alongside
> the rest of the Mistral AI API. Standard library only, no third-party
> dependencies. Current release: v1.4.0.

> ### [PolyScribe](https://github.com/VikingOwl91/polyscribe)
> **Rust · Whisper · ffmpeg · JSON-RPC**
>
> A local-first transcription CLI built on whisper.cpp, with model management,
> integrity-checked downloads, and JSON-RPC plugins. Optional CUDA and ROCm/HIP
> builds provide experimental GPU support.

> ### [Infinity Tales](https://github.com/VikingOwl91/infinity-tales-case-study)
> **Go · PostgreSQL · Svelte · TypeScript** · Closed-source product · Public case study
>
> An AI-assisted storytelling platform with persistent quests, inventory, and
> character progression. Rebuilt from Firebase and React around a Go API,
> PostgreSQL, and a Svelte frontend, with model integrations through OpenRouter.
> [Case study repository](https://github.com/VikingOwl91/infinity-tales-case-study) ·
> [Write-up on nachtigall.dev](https://nachtigall.dev/work/infinity-tales)

> ### [Owlry](https://github.com/VikingOwl91/Owlry)
> **Rust · GTK4 · Wayland · Lua**
>
> A keyboard-first Wayland launcher with a warm daemon and extensible search
> providers. One binary combines the GTK4 interface, Unix-socket IPC, systemd
> integration, and optional Lua configuration.

### More

- **[ResearchBench](https://github.com/VikingOwl91/research-bench)** (TypeScript · SvelteKit · Rust/WASM · ONNX Runtime Web): A browser research prototype with document import, semantic search, and answers linked to source passages. Parsing, embeddings, and search run locally; generation uses a user-provided Mistral or OpenRouter API key.
- **[OwlenShell](https://github.com/VikingOwl91/owlenshell)** (Linux · Wayland · Rust · Experimental): An experimental Linux desktop shell exploring Wayland integration, UI frameworks, renderer architectures, and compositor behavior. Currently focused on prototyping, compatibility testing, and evidence-driven technical decisions.

## Technical focus

- **Agentic AI & developer tooling:** MCP, model routing, SDKs, and workflow automation.
- **Go & Rust backend & APIs:** Go and Rust services, API integrations, and PostgreSQL.
- **Linux & platforms:** Wayland desktop integration, IPC, systemd, and service operation.
- **Local AI:** On-device transcription, model management, and browser inference.
- **Fullstack applications:** TypeScript and SvelteKit interfaces connected to application data and APIs.
- **Open source:** Useful tools with documentation, explicit interfaces, and practical contribution paths.

## How I work

I favor clear boundaries, testable components, and documented trade-offs.
Security work means checking what crosses a process, model, or network boundary;
local-first design means being explicit about what stays on the device and what
leaves it. I use open protocols and automation to make tools easier to connect,
maintain, and use.

## Let's connect

Developer tooling and AI agents in Go and Rust.

[Portfolio](https://nachtigall.dev) · [LinkedIn](https://www.linkedin.com/in/christian-nachtigall/en) · [GitHub](https://github.com/VikingOwl91) · [hello@nachtigall.dev](mailto:hello@nachtigall.dev)
