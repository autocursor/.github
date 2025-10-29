# Auto Cursor

<div align="center">

**Autonomous AI-Powered Software Development**

Build complete software projects through natural conversation.

[Features](#key-features) • [Install](#quick-start) • [Docs](https://autocursor.github.io) • [Contribute](#contributing)

</div>

---

## What is Auto Cursor?

**Auto Cursor** is a revolutionary multi-agent AI orchestration plugin for Cursor IDE that transforms software development from a complex technical task into a simple conversation.

### The Magic

```
You: "I want to build a task management web app"

Auto Cursor: *Creates specialized AI team*
            *Gathers requirements*
            *Designs architecture*
            *Implements backend & frontend*
            *Writes comprehensive tests*
            *Sets up CI/CD*
            *Generates documentation*

Result: Complete, production-ready project!
```

### Key Features

- **Zero Commands** - Just natural conversation
- **Fully Autonomous** - From requirements to deployment
- **8 Project Types** - Web, Mobile, Game, API, CLI, ML, Desktop
- **Multi-Agent System** - 11 specialized AI agents
- **Complete Output** - Code, tests, docs, infrastructure
- **Extensible** - Add custom purposes and agents

## Supported Project Types

| Type | Stack |
|------|-------|
| **Web Apps** | Go + React + PostgreSQL |
| **Mobile Apps** | Swift / Kotlin |
| **Games** | Unity + C# |
| **APIs** | Go + gRPC |
| **CLI Tools** | Go + Cobra |
| **ML/AI** | Python + FastAPI |
| **Desktop Apps** | Electron + React |
| **...and more!** | Extensible |

## Architecture

<div align="center">

```
┌─────────────────────────────────────────┐
│         User (Natural Language)          │
└────────────────┬────────────────────────┘
                 │
                 ▼
┌─────────────────────────────────────────┐
│           Lead Agent (Visible)           │
│    "Your friendly AI architect"          │
└────────────────┬────────────────────────┘
                 │
                 ▼
┌─────────────────────────────────────────┐
│            Event Bus System              │
│       (Orchestrates everything)          │
└──┬──────┬──────┬──────┬──────┬──────┬──┘
   │      │      │      │      │      │
   ▼      ▼      ▼      ▼      ▼      ▼
┌────┐ ┌────┐ ┌────┐ ┌────┐ ┌────┐ ┌────┐
│Req │ │Arch│ │Dev │ │Test│ │Ops │ │Docs│
│uire│ │itec│ │elo │ │ing │ │    │ │    │
│ment│ │ture│ │pers│ │    │ │    │ │    │
└────┘ └────┘ └────┘ └────┘ └────┘ └────┘
   Hidden AI Agents Working Autonomously
```

</div>

## Quick Start

```bash
# Install
npm install autocursor

# Use in your code
import { autoCursor } from 'autocursor';

await autoCursor.initialize();
const leadAgent = autoCursor.getLeadAgent();

const result = await leadAgent.execute({
  userMessage: "Build a web application"
});
```

## Our Repositories

### [autocursor](https://github.com/autocursor/autocursor)
Main plugin repository with complete implementation

### [Documentation](https://autocursor.github.io)
Comprehensive guides, API reference, and examples

## Contributing

We welcome contributions! See our [Contributing Guide](https://github.com/autocursor/autocursor) to get started.

### Ways to Contribute

- Report bugs
- Suggest features
- Improve documentation
- Submit pull requests
- Star our repositories

## Community

Join our growing community:

- [Discord](https://discord.gg/autocursor) - Chat with the team and community
- [Twitter](https://twitter.com/autocursor) - Follow for updates
- Email: hello@autocursor.dev

## License

All our projects are licensed under the MIT License - see individual repositories for details.

---

<div align="center">

**Built by the Auto Cursor Team**

*Making software development as simple as having a conversation*

[Website](https://autocursor.github.io) • [GitHub](https://github.com/autocursor)

</div>

