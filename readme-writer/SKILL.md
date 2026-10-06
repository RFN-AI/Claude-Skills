---
name: readme-writer
description: "Write, review, or improve a clear README for a software project or repository. Use whenever the user asks to document a project, make a repo easier to understand or run, or polish a README—including AI/ML and portfolio projects. Inspect the repository first when available, and keep project-specific sections evidence-based and optional."
---

# README Writer Skill

Write a clear, scannable README that quickly explains what the project does, who it helps, and how to run it. Help a newcomer reach a working result without making the README longer than the project needs.

## Workflow

1. **Inspect the project first** when its repository or files are available. Check the existing README, repository metadata, dependency and configuration files, source code, scripts, documentation, license, and any demo or screenshot assets. Don't ask the user for facts that are already clear from those files.
2. **Use evidence, not guesses.** Ask only for important details that cannot be determined from the project. If the repository isn't available, request the minimum information needed to write an accurate README.
3. **Preserve what works.** When improving an existing README, keep accurate content and its language unless the user asks for a change. For a new README, use English by default unless the user or project context indicates another language.
4. **Write or update `README.md`** if the user asked for a file and the project is available. Otherwise, provide the README content directly. Don't modify unrelated files.
5. **Keep sections relevant.** Use the outline below as a guide, not a checklist that every project must satisfy. Avoid repeating the same setup instructions in both Quickstart and Installation.

## Suggested README Structure

Adapt this to the project; omit sections that don't apply.

- **Project name and one-line pitch** — what it does and who it's for.
- **Why this project** — a short, specific explanation when it adds useful context.
- **Features** — the few capabilities that matter.
- **Demo** — screenshots, video, or links only when real assets or links are available.
- **Quickstart** — the shortest complete path to a working result, with the expected result when helpful.
- **Usage** — common examples.
- **Installation and configuration** — include prerequisites and settings when needed.
- **Architecture or project structure** — only when it helps explain a non-trivial project.
- **Results** — include only real, user-provided or verifiable results.
- **Contributing and license** — include the actual policy and license information when available; don't invent either.

For AI/ML projects, explain the model, pipeline, training or inference flow, deployment approach, and hardware requirements only when the repository or user provides reliable information. For portfolio projects, emphasize what was actually built and the real demo or results. These sections are optional; don't force them into every README.

## Accuracy Rules

- Never invent features, commands, models, metrics, benchmarks, hardware requirements, API endpoints, links, demos, or project status.
- Base installation and usage commands on the repository's actual files. If a command cannot be verified, mark the assumption clearly or ask the user.
- Use only working, relevant badges; don't leave badge placeholders.
- If no license file is present, say that none was found rather than choosing or implying a license.
- Never copy secrets or API keys into the README. Describe required environment variables without revealing their values.

## Quality Checks

- The opening line makes the project's purpose clear.
- A newcomer can follow the Quickstart using commands that match the repository.
- Claims and examples are supported by project files or user-provided facts.
- The README is easy to scan, with short sections and no unnecessary repetition.
- Contributing, license, and other optional sections are included only when applicable—or consciously omitted.

## Avoid

- Asking for information that can be found in the repository.
- Burying the project purpose under badges or a long introduction.
- Adding generic marketing language or unsupported claims.
- Forcing AI/ML, architecture, demo, or results sections when they don't fit.
- Duplicating the full documentation in the README; summarize and link to real docs when available.
