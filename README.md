# Forward Impact Skills

Agent skills for the [Forward Impact](https://forwardimpact.team) engineering standard. The `gemba` platform skills moved to [`forwardimpact/gemba-skills`](https://github.com/forwardimpact/gemba-skills). Install that pack to keep them.

## Install

With [APM](https://microsoft.github.io/apm/):

```bash
apm install forwardimpact/fit-skills
```

## Available Skills

| Skill | Description |
| --- | --- |
| **fit-codegen** | Generate JavaScript types, service base classes, typed clients, gRPC definitions, and MCP field metadata from proto contracts, or download a pre-generated bundle. Use when a proto definition changed and you must regenerate the generated code to match, when you set up a gRPC product for the first time, or when a runtime image needs to fetch the generated bundle. |
| **fit-doc** | Ship a documentation site that agents and humans can both navigate. Use when you build a static site from markdown, when you preview with live reload, or when you configure front matter, templates, llms.txt augmentation, content partials, or the pre-build hook. |
| **fit-guide** | Get career guidance and output review grounded in your organization's engineering standard. Use when a promotion conversation ended without specifics and you need evidence of what to improve. Use when you review agent output and want a second opinion against the standard. Use when you ask about skills, levels, and career expectations. This skill also covers how to set up the Guide service stack and how to ingest knowledge content. |
| **fit-landmark** | Demonstrate engineering progress and do not make individuals feel surveilled. Show evidence of growth. Use when the quarterly review has only ticket counts and you need system-level trends. Use when you check promotion readiness. Use when you assess whether culture investments work. Use when you explore GetDX snapshot trends, marker evidence, engineer voice, and growth timelines. |
| **fit-logger** | Capture a command's stdout into rotated log files. Use when you need to persist a long-running process's output with size-based rotation and a bounded archive count. You do not configure a logging framework. |
| **fit-map** | Define what good engineering means so roles have clear, defensible expectations. Provision activity-database substrates. Use when you define or update skills, capabilities, behaviours, disciplines, tracks, levels, or questions. Use when you push rosters, sync GetDX snapshots, or ingest GitHub artifacts. Use when you stage a seeded substrate. |
| **fit-outpost** | Keep track of people, projects, and threads. You do not depend on memory. Use when context is scattered across email, calendar, and notes and you need a daily briefing. Use when you manage email drafts. Use when you schedule background AI tasks, maintain a personal knowledge base, check agent status, and wake agents on demand. |
| **fit-pack** | Distribute a skill pack so agents and engineers can install it through their package manager. Use when you publish skills and agents to a shared repository. Use when a bare install pulls skills but silently drops agents. Use when you need the install to land in APM's conventional layout. It stages skills, agents, and references into one repository tree with a generated manifest and README. |
| **fit-pathway** | See what's expected at your level, configure agents to meet your organization's engineering standard, and make staffing decisions you can defend. Use when expectations are unclear and you need role definitions by discipline, track, and level. Use when agents follow generic practices instead of your standard. Use when you analyze career progression gaps. Use when you generate job definitions, interview questions, or a published engineering standard site. |
| **fit-process** | Build the knowledge indexes from HTML sources: process resources, then graphs and vectors. Use when you populate the retrieval indexes an agent queries. It is a build-pipeline step. Run the stages in order before search or graph queries work. |
| **fit-rag** | Query the knowledge indexes: search by meaning, answer relationship questions with triple patterns, or list graph subjects by type. Use when you need ranked semantic results or graph relationships and you do not want to stand up a vector database or SPARQL endpoint. |
| **fit-rc** | Start, stop, restart, check status, and read logs for configured services through one interface. Use when you need to manage a set of services and you do not want to remember each one's specific command, port, and flags. |
| **fit-summit** | Make staffing decisions you can defend. To do this, model team capability as a system. Use when a post-mortem surfaces the same skill gap again. Use when you evaluate whether a hire, transfer, or promotion strengthens the team. Use when you detect structural risks like single points of failure. Use when you simulate what-if scenarios, align growth with team gaps, compare teams, and track capability trajectory over time. |
| **fit-svscan** | Run the supervision daemon that keeps a tree of services alive and accepts control commands over a Unix socket. Use when you need a pure supervisor behind `fit-rc`. It knows nothing about service order or oneshots. It knows only how to keep processes running. |
| **fit-terrain** | Produce a complete eval dataset from a single DSL file so you can prove agent changes with reproducible evidence. Also run substrate identity verbs against any Supabase stack that implements the Substrate Contract. Use when you set up an eval, bootstrap a realistic environment, or regenerate a dataset after a schema change. Use when you provision, pick, and issue personas for an interview run. |
| **fit-unary** | Make a single unary gRPC call to a live service from the command line, with a JSON request and a JSON response. Use when you need to probe or smoke-test a gRPC endpoint and you do not want to write a client. |
| **fit-visualize** | Query recorded OpenTelemetry spans with JMESPath and render them as Mermaid sequence diagrams. Use when you need to read spans back from the span index and filter by trace or resource id. Use when you want to see the call flow with no tracing UI. |
