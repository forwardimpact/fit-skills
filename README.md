# Forward Impact Skills

Agent skills for the [Forward Impact](https://forwardimpact.team) engineering standard.

## Install

With [APM](https://microsoft.github.io/apm/):

```bash
apm install forwardimpact/fit-skills
```

## Available Skills

| Skill | Description |
| --- | --- |
| **fit-benchmark** | Prove whether a skill-pack change made agents better at writing code. Use when a single passing eval doesn't prove anything and you need multi-run pass@k evidence, when grading coding tasks with hidden tests the agent cannot see, or when comparing outcomes across skill-set versions. |
| **fit-codegen** | Generate JavaScript types, service base classes, typed clients, gRPC definitions, and MCP field metadata from proto contracts. Use when a proto definition changed and the generated code must be regenerated to match, or when setting up a gRPC product for the first time. |
| **fit-doc** | Ship a documentation site that agents and humans can both navigate. Use when building a static site from markdown, when previewing with live reload, or when configuring front matter, templates, llms.txt augmentation, content partials, or the pre-build hook. |
| **fit-guide** | Get career guidance and output review grounded in your organization's engineering standard. Use when a promotion conversation ended without specifics and you need evidence of what to improve, when reviewing agent output and you want a second opinion against the standard, or when asking about skills, levels, and career expectations. Also covers setting up the Guide service stack and ingesting knowledge content. |
| **fit-harness** | Prove whether agent changes improved outcomes with reproducible evidence. Use when an eval passes locally but fails in CI and the only output is 'assertion failed', when you need a pass/fail verdict from a judge agent, or when coordinating multiple specialist agents in one session. Pair with `fit-trace` for trace analysis. |
| **fit-landmark** | Demonstrate engineering progress without making individuals feel surveilled, and show evidence of growth. Use when the quarterly review has only ticket counts and you need system-level trends, when checking promotion readiness, when assessing whether culture investments are working, or when exploring GetDX snapshot trends, marker evidence, engineer voice, and growth timelines. |
| **fit-logger** | Capture a command's stdout into rotated log files. Use when you need to persist a long-running process's output with size-based rotation and a bounded archive count, without configuring a logging framework. |
| **fit-map** | Define what good engineering means so roles have clear, defensible expectations, and provision activity-database substrates. Use when defining or updating skills, capabilities, behaviours, disciplines, tracks, levels, or questions; when pushing rosters, syncing GetDX snapshots, or ingesting GitHub artifacts; or when staging a seeded substrate. |
| **fit-outpost** | Keep track of people, projects, and threads without depending on memory. Use when context is scattered across email, calendar, and notes and you need a daily briefing, when managing email drafts, or when scheduling background AI tasks, maintaining a personal knowledge base, checking agent status, and waking agents on demand. |
| **fit-pack** | Distribute a skill pack so agents and engineers can install it through their package manager. Use when publishing skills and agents to a shared repository, when a bare install pulls skills but silently drops agents, or when you need the install to land in APM's conventional layout. Stages skills, agents, and references into one repository tree with a generated manifest and README. |
| **fit-pathway** | See what's expected at your level, configure agents to meet your organization's engineering standard, and make staffing decisions you can defend. Use when expectations are unclear and you need role definitions by discipline, track, and level, when agents follow generic practices instead of your standard, when analyzing career progression gaps, or when generating job definitions, interview questions, or a published engineering standard site. |
| **fit-query** | Query an RDF graph index with a triple pattern to answer relationship questions — which people belong to an organization, which projects reference a capability. Use when you need graph relationships without writing join logic or standing up a SPARQL endpoint. |
| **fit-rc** | Start, stop, restart, check status, and read logs for configured services through one interface. Use when you need to manage a set of services without remembering each one's specific command, port, and flags. |
| **fit-search** | Find content related to a query by meaning, not keywords, from a vector index. Use when you need ranked semantic results over a few hundred to a few thousand embeddings without standing up a vector database. |
| **fit-subjects** | List the subjects in an RDF graph index, optionally filtered by type. Use when you need to enumerate which entities of a given type exist in a knowledge graph — people, organizations, capabilities — without writing a SPARQL query or loading the whole graph into your application. |
| **fit-summit** | Make staffing decisions you can defend by modeling team capability as a system. Use when a post-mortem surfaces the same skill gap again, when evaluating whether a hire, transfer, or promotion strengthens the team, when detecting structural risks like single points of failure, or when simulating what-if scenarios, aligning growth with team gaps, comparing teams, and tracking capability trajectory over time. |
| **fit-svscan** | Run the supervision daemon that keeps a tree of services alive and accepts control commands over a Unix socket. Use when you need a pure supervisor behind `fit-rc` — it knows nothing about service order or oneshots, only how to keep processes running. |
| **fit-terrain** | Produce a complete eval dataset from a single DSL file so you can prove agent changes with reproducible evidence, and run substrate identity verbs against any Supabase stack implementing the Substrate Contract. Use when setting up an eval, bootstrapping a realistic environment, regenerating a dataset after a schema change, or provisioning, picking, and issuing personas for an interview run. |
| **fit-trace** | See exactly what an agent did and whether a change improved outcomes. Use when an agent workflow failed and you need to understand why, when you want to measure token usage, cost, and efficiency across runs, or when studying agent behavior patterns from NDJSON traces. |
| **fit-unary** | Make a single unary gRPC call to a running service from the command line, with a JSON request and a JSON response. Use when you need to probe or smoke-test a gRPC endpoint without writing a client. |
| **fit-visualize** | Query recorded traces with JMESPath and render them as Mermaid sequence diagrams. Use when you need to read back spans from the trace index, filter by trace or resource id, and see the call flow without wiring up a tracing UI. |
| **fit-wiki** | Give agent teams stable memory that persists across sessions. Use when an agent finishes a session and its findings would vanish without shared memory, when sending a memo to a teammate, when refreshing storyboard XmR charts, when auto-fixing wiki audit findings after editing memory, or when bootstrapping and syncing a wiki. |
| **fit-xmr** | Distinguish signal from noise so the team acts on real changes, not fluctuations. Use when a metric changes and the team debates whether it is a real shift or just noise, when you need a compact status chart for a wiki, PR, or report, or when recording and analyzing time-series metrics with Wheeler/Vacanti XmR control charts. |
