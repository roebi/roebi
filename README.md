<div align="center">

![roebi header](./header.svg)

⏱ **1 min read** &nbsp;·&nbsp; 🇨🇭 Switzerland &nbsp;·&nbsp; Open Source

</div>

---

## The New Work Way

I'm **roebi** — Robert Halter, Swiss software engineer with years of experience in test automation and CI/CD.

A while back I started asking: *what if the way we work with AI could be as structured and reusable as good code?*

That question led to **New Work with Skills** — a methodology where every task you give an AI agent is defined as a versioned, portable `SKILL.md` file. Not a vague prompt. A skill.

This is not just a theoretical idea. It is grounded in the way I actually work.

Based on the skills I created and used in my own framework, **@roebi/sw-dev-agent-framework**, I refined a practical process for building software in a disciplined, repeatable way. By using and improving those skills in real projects, I developed a workflow that is both **specification-driven** and **TDD-driven**:

- Start from clear requirements and a concrete specification
- Turn those requirements into architecture and implementation decisions
- Drive development through failing tests first
- Validate each step before moving on
- Review, refine, and release with traceable intent

So the model is not "ask AI to code" in a loose way. It is: define the work as a skill, execute it consistently, and improve the skill over time as the process matures.

```
You don't prompt. You invoke a skill.
Skills are composable. Skills are auditable. Skills ship.
```

---

## How it works

**1. Define** — Write a `SKILL.md` that captures *what* the agent should do, *how*, and *when it's done*.  
**2. Invoke** — Any LLM agent reads the skill and executes it deterministically.  
**3. Compose** — Skills call other skills. Complex workflows from simple building blocks.  
**4. Version** — Pin skills like dependencies. Reproducible today, next year, on any model.  
**5. Improve** — Use them in real projects, learn from the outcomes, and evolve the workflow.

This is the [agentskills.io](https://agentskills.io) open specification — and it matches the process I developed while building and refining **@roebi/sw-dev-agent-framework**: specification-first, TDD-first, and continuously improved through repeated use.

---

## Where to go next

| | |
|---|---|
| 🌐 **[new-work-skills.dev](https://new-work-skills.dev)** | The methodology, skill cards, live examples |
| 📝 **[Blog](https://roebi.github.io/roebi-halter-in-blog)** | What I'm learning, building, and discovering |
| 🤖 **[agent-skills](https://github.com/roebi/agent-skills)** | My personal skills library — open source |
| 🛠 **[aider-skills](https://github.com/roebi/aider-skills)** | Agent Skills integration for aider |

---

<div align="center">

*roebi · Robert Halter · New Work with Skills · new-work-skills.dev · Switzerland*

</div>
