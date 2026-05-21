
# Practical AI for academics

A course in Practical AI for academic researchers. These slides were developed by [Claes Bäckman](https://claesbackman.com).

## Slides

The deck is split into a morning and an afternoon session. PDFs are in [Slides/](Slides/).

### Morning — [PracticalAI_Morning.pdf](Slides/PracticalAI_Morning.pdf)

Concepts and setup. Seven sections covering where the field has moved and how to start working with agentic tools.

1. **The landscape.** Three generations of AI (chat → reasoning → agentic), the jagged frontier of capabilities, and where AI pays off in research, coding, and admin work.
2. **Choosing your tool.** Chat (ChatGPT, Claude.ai) versus agentic (Codex, Claude Code); pricing tiers; model tiers; and the surfaces (VS Code, CLI, desktop, web) where the agent runs.
3. **How the tools work.** The agent as a harness around the model — files, editing, shell, search, web, MCP — and what that implies for usage.
4. **Setting up your workspace.** Installing Codex inside VS Code in five steps, plus useful extensions for Stata, Python, LaTeX, and data.
5. **Working with the agent.** Session structure, context budgets, file formats, `AGENTS.md` and `voice.md`, Ask vs. Code mode, permission tiers, prompting rules, and common failure modes.
6. **Working with secure data.** A workflow for using Codex alongside restricted servers — codebooks, simulated data, and iterating on `.do` files locally before running on the real data.
7. **Skills, subagents, and MCP.** Reusable workflows (`$review-paper`, `$paper-version`, etc.), spawning subagents for adversarial checks, and what MCP is for.

### Afternoon — [PracticalAI_Afternoon.pdf](Slides/PracticalAI_Afternoon.pdf)

Hands-on blocks where participants apply the tools to their own materials.

1. **A referee report on your paper.** Live demo and hands-on with the `$review-paper` skill — six subagents running in parallel on a draft.
2. **Organising a conference.** Building a conference budget from a call for papers as a worked example of admin tasks.
3. **Building a `voice.md` file.** Using the `voice-extractor` skill to capture your own prose style so future edits sound like you.
4. **Slides and websites.** Generating Beamer decks and standalone HTML sites from project folders, with a shared `slides-style.md`.
5. **Implications and getting started.** What changes for academic work as friction drops, verification habits, disclosure and data-handling norms, and three things to try on Monday.
