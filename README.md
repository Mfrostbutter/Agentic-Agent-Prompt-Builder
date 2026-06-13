# Agent Prompt Builder

A free, single-file builder for well-structured AI agent prompts. Pick a starting preset, fill in the parts you need, and copy a clean, organized prompt. Everything runs in your browser; nothing is sent anywhere.

It's meant for people who are new to writing agent prompts and want a solid structure to start from instead of a blank page.

## Use it

Open `index.html` in any browser. That's the whole app, one file, no build step and no dependencies.

To host it for free, enable GitHub Pages on this repo (Settings → Pages → deploy from the `main` branch) and it serves at `https://<your-username>.github.io/Agentic-Agent-Prompt-Builder/`.

## What it does

- **Two modes.** *Standalone agent* for a normal assistant, or *Tool sub-agent* for an agent invoked by an orchestrator.
- **Presets.** Research, summarizer, social media copywriter, SEO writer, cold outreach, coding assistant, code reviewer, data extraction, SQL analyst, and customer support. Each one is a worked example of a good prompt.
- **Structured sections.** Identity, objective, tools, workflow, rules (always / never), output format, examples, and error handling.
- **Modern output.** Generates a markdown-structured prompt with clear headers and `<example>` blocks, the shape current models follow best.
- **Live preview, copy, and download.** The prompt updates as you type. Copy to clipboard or download as `.md`.
- **Autosave.** Your work is kept in the browser's local storage between visits.

## Why structure matters

A vague prompt produces an agent that wanders. A structured one, with a clear role, a defined workflow, explicit guardrails, and a precise output contract, produces an agent that does the job and stops. This tool just makes that structure easy to assemble and reuse.

## License

MIT. See [LICENSE.txt](LICENSE.txt). The original single-form version is preserved at [`tools-agent-prompt-builder-v2.html`](tools-agent-prompt-builder-v2.html).
