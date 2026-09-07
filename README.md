# Developer Skills Library

Reusable skills for developers who want their AI agents, coding tools, and workflows to produce better work with less hand-holding.

This repository is a growing library of practical, copy-paste-ready skills that developers can plug into their projects, agents, prompts, and internal workflows. Each skill is written to do one job clearly: improve output quality, reduce repeated instructions, and make AI-assisted development more reliable.

## Why this exists

Most AI-assisted workflows fail for the same reason: the model is asked to “do the task” without being taught how good work should look.

This repo fixes that.

Instead of writing the same long instructions again and again, you can use focused skills for specific jobs like copywriting, code review, frontend taste, documentation, research, testing, debugging, product thinking, and more.

The goal is simple:

> Give developers reusable skill files that turn vague AI output into sharper, more useful, more production-ready work.
## Who this is for

This repository is for:

- developers using AI coding agents
- founders building products with AI-assisted development
- teams creating internal engineering workflows
- builders who want reusable prompt systems instead of one-off prompts
- anyone tired of generic AI output that sounds good but does not actually help

## Core idea

A good skill should not just tell an AI model what to do.

It should define:

- the role the model should take
- the exact job to be done
- the standards the output must meet
- the mistakes to avoid
- the structure of the final response
- the quality bar before the task is considered complete

That is what this repo is built around.

## Repository structure

```txt
skills/
  copywriting/
    README.md
    SKILL.md

  anti-slop/
    README.md
    SKILL.md

  frontend-taste/
    README.md
    SKILL.md

  code-review/
    README.md
    SKILL.md

  debugging/
    README.md
    SKILL.md

  documentation/
    README.md
    SKILL.md

  research/
    README.md
    SKILL.md

  testing/
    README.md
    SKILL.md

  devops/
    README.md
    SKILL.md
```

Each skill folder should contain:

- `SKILL.md` — the actual reusable skill instruction
- `README.md` — what the skill does, when to use it, and examples
- optional templates, checklists, examples, or supporting files

## What makes a good skill

Every skill in this repository should be:

### Specific

A skill should solve a clear problem.  
Not “make this better,” but “review this README for clarity, developer usefulness, missing setup steps, and generic language.”

### Practical

The output should help someone ship, debug, improve, review, or decide something.

### Reusable

The same skill should work across multiple projects without needing to be rewritten every time.

### Opinionated

A good skill should have standards. It should know what weak output looks like and push against it.

### Developer-friendly

Skills should use clear structure, direct language, and examples that developers can apply immediately.

## Example use cases

Use these skills when you want an AI assistant or coding agent to:

- write a better `README.md`
- review a pull request
- improve a landing page
- debug a failing build
- audit a codebase
- create sprint documentation
- design a testing plan
- research competitors
- map features from a PRD
- improve UI quality
- remove vague AI-sounding language
- generate implementation prompts
- create project handoff documentation

## Example prompt

```md
Use the copywriting skill and anti-slop skill.

Task:
Write a README.md for this repository.

Context:
This repo contains reusable developer skills that can be used with AI agents, coding assistants, and project workflows.

Goal:
Make the README clear, practical, and useful for developers.

Quality bar:
- Avoid generic AI language.
- Explain what the repo is for.
- Show clear use cases.
- Make the repo feel credible.
- Keep the tone direct and developer-friendly.
```

## Suggested skill format

Each `SKILL.md` should follow a consistent structure:

```md
# Skill Name

## Purpose

What this skill helps with.

## When to use this skill

Clear situations where this skill is useful.

## Inputs needed

The information the user or developer should provide.

## Process

The reasoning framework or workflow the skill should follow.

## Output format

The exact structure the final answer should use.

## Quality checklist

Standards the output must meet before it is considered complete.

## Common mistakes to avoid

Patterns that usually lead to weak results.
```

## Quality standards

Before adding a skill to this repository, check that it passes this bar:

- Does it solve one clear job?
- Is it useful without extra explanation?
- Can another developer apply it immediately?
- Does it reduce repeated prompting?
- Does it produce better output than a generic instruction?
- Does it include enough context to guide the model properly?
- Does it avoid vague phrases like “make it engaging,” “optimize it,” or “improve it” without defining what that means?

## Roadmap

Planned skill categories include:

- AI copywriting
- anti-slop review
- frontend design taste
- code review
- debugging and RCA
- documentation writing
- product requirement analysis
- sprint planning
- API research
- competitor research
- test case generation
- deployment troubleshooting
- security review
- database schema review
- prompt engineering
- agent workflow design

## Contributing

Contributions are welcome if they make the skill library more useful for real developer workflows.

A good contribution can be:

- a new skill
- an improved skill structure
- better examples
- stronger checklists
- real-world usage notes
- fixes to unclear instructions
- removal of generic or low-value language

Please keep contributions practical, specific, and easy to reuse.

## Philosophy

This repository is built on one belief:

> AI tools become more useful when developers give them standards, not just tasks.

Skills are those standards, packaged into reusable files.

## License

Add your preferred license here.
