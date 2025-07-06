# Typical Docs

This is the canonical documentation repository for **Typical**: the AI-native programming language whose design has been synthesized by ephemeral agents (SEA). Fully statically analyzable, TypeScript-familiar, and Rust-backed—Typical is being designed from first principles as the substrate for civilization-scale code generation.

There are no releases yet—nor will there be—until the design has been stress-tested against the full complexity of every domain it aims to serve. This is a full-spectrum programming language—engineered for semantic stability, long-term predictability, and the raw performance demanded by agentic software systems, scientific computing, real-time infrastructure, and industrial-grade AI workflows.

## 🌐 What Is Typical?

Typical is a programming language that feels like TypeScript but compiles to Rust. It creates no runtime type tricks, no dynamic dispatch, requires no ownership annotations, doing all this without garbage collection or sacrificing TypeScript’s ergonomic familiarity. The compiler infers purity, lifetimes, and memory regions automatically. Reference-counting fallbacks are needed on rare occasion, and they’re inserted automatically and *surgically* managed—giving developers memory safety without borrow checker friction.

TypeScript expertise mostly transfers. In fact, the language is so close to TypeScript that internally, it uses a novel **LSP stacking architecture** to offload the overwhelming majority of the correctness checking effort over to the TypeScript compiler API itself. This means that not only does Typical compile to Rust, it also compiles to idiomatic TypeScript—and by extension—idiomatic JavaScript. All for free.

The result is a programming environment tuned not just for humans—but for LLMs, agents, and the design workflows that drive them.

## 🌀 What Is SEA?

**SEA (Synthesis by Ephemeral Agents)** is a recursive orchestration layer of ephemeral agents that synthesizes design artifacts across high-variance, cross-domain corpora.

It doesn’t just generate code—it designs systems. SEA automates the early-stage architecture work normally reserved for large, multi-year language efforts. This includes:

- Multi-resolution summarization of language semantics, compiler behavior, domain constraints, UX patterns, and long-term strategic objectives
- Continuous cross-analysis across trade-offs, regulatory pressures, legacy interop, safety models, and developer ergonomics
- Automated **conflict detection**—surfacing contradictions and misalignments between target domains (e.g. embedded vs HPC), async models, memory layouts, or even ecosystem-level incentives

SEA performs the kind of deep systems reasoning no human can feasibly hold in working memory. These docs are the artifact trail it leaves behind.

## 🧾 What This Repo Contains

This repo is the **official artifact store** for the design of the Typical language. It is:

- Canonical
- Markdown-native
- Authored entirely by agents via SEA
- Continuously updated as language decisions coalesce

### Topics Include:
- Language semantics & syntax
- Compiler architecture
- Memory & ownership models
- LSP stacking strategies
- Design philosophy & trade-offs
- Ecosystem & domain coverage plans
- Specification conflict reports


## 🧠 Why Docs-First?

Typical tackles a problem so vast and complex that rushing to code is a dead end. The language’s scope spans concurrency, ownership, regulatory compliance, and multi-domain interoperability. In this space, **prototypes offer only illusions of progress**.

We’re taking a page from Ada’s playbook: years of front-loaded design before a single compiler line. This discipline is the only way to build something truly durable, trustworthy, and fit for multi-century lifespans.

**Once AI can rewrite the past, the future becomes locked. So let’s build a future worth locking in.**

## 🧭 Who This Is For

- Language designers (human or otherwise)
- Compiler engineers and toolchain architects
- Agent frameworks and LLM runtime builders
- VCs and CTOs exploring next-gen AI-native stacks
- Systems-level thinkers designing for post-human workflows

## 🛠️ Status

**The Typical design effort is not complete**. If you dig in—especially with domain expertise—you’ll find unresolved conflicts, underspecified features, and gaps that block critical use cases.

This repo captures a high-velocity, front-loaded design effort: stress-testing semantic coherence across domains and iterating relentlessly to surface and resolve deep structural issues.

If you bring domain expertise, it’ll be clear that Typical represents a fundamentally novel approach to language design—one that’s rapidly converging on a model with far-reaching implications. That expertise isn’t just welcome—it’s critical to moving the project forward.

For everyone else: this isn’t casual reading. Watch closely, or wait for release.

## 🔒 License

MIT. These artifacts are freely available for exploration, reflection, and reuse.


## 🧩 Contributing

This repository is **not** open to pull requests. The design of Typical is being orchestrated via SEA—a recursive agent framework that synthesizes and evolves the spec internally.

That said, **we do welcome issue submissions from domain experts** who can flag high-complexity constraints, auditing complications, or other systemic conflicts in their field.

If you're intimately familiar with the software lifecycle in domains such as:

- Avionics or aerospace certification (DO-178C, etc)
- Medical device compliance (FDA, IEC 62304)
- Safety-critical automotive (ISO 26262)
- High-assurance systems or formal verification pipelines
- Regulated finance data stacks with audit constraints
- Real-time embedded control loops
- National security / classified stack constraints

...and you spot **domain-specific concerns, friction points, or non-obvious conflicts** in the evolving Typical design, we want to hear from you.

> **Submit an issue** providing as much domain-specific context as possible—while, of course, respecting the legal, regulatory, or confidentiality constraints of your field. These will be reviewed, triaged, and—if relevant—fed into the SEA synthesis loop for conflict detection and remediation.

This is *not* the place for “have you considered omitting semicolons” or “what if it had a Lisp macro system.” We’re operating upstream of that conversation.

If you're bringing signal from high-stakes, high-friction domains—we’re listening.
