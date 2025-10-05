<div align="center">

# Mistral Agent Collection

Curated, modular agent definitions you can copy, adapt, and extend for your own Mistral workflows.

</div>

---

## ✨ What Is This?
This repository is a growing library of purpose-built Mistral agent templates. Each agent is structured so you can quickly:

- Understand its purpose
- Copy a deployable definition (instructions / guardrails / tone)
- Customize for a new use‑case
- Contribute improvements back

Currently featured: `Agent Forge` — an agent that helps you design new agents from natural language requirements.

---

## 🧱 Philosophy
Good agents are:

- Focused: Each one has a single, clear purpose
- Composable: You can mix concepts across agents
- Deployable: Clean blocks for name, instructions, guardrails, tone
- Minimalist: No essay fluff, just what you need

---

## 📁 Repository Structure
```
LICENSE
README.md              <- You are here
Agent Forge/           <- Agent-specific materials
	README.md            <- Overview & example
	instructions.md      <- Core instruction block pattern
	guardrails.md        <- Behavioral constraints
	tone.md              <- Voice & style definition
```

---

## 🔧 Featured Agent: Agent Forge
An architect-style agent that converts a user's idea into a structured agent definition (Name, Instructions, Guardrails, Tone). It never roleplays the target agent—only designs it.

Quick example outputs include assistants for:
- Baking / kitchen help
- Roleplay partner setup
- Prose editing support

See: `Agent Forge/README.md` for a usage example link.

---

## 🚀 Quick Start (Human Usage)
1. Open the Le Chat website (https://chat.mistral.ai/). This doesn't work in the mobile app, please use the browser even if on a mobile device.
2. On the left hand menu, select 'Agents'.
3. Press the button in the upper right corner marked 'Create an Agent'.
4. Copy the relevant fields from the repo into the creation UI. You may make modifications to better fit your desired behaviour, but note that changing the prompt may lower or increase usability depending on usecase.

---

## 🧩 Output Format Standard
Every designed agent should produce four distinct markdown code blocks:

1. Name
2. Instructions
3. Guardrails
4. Tone

Each block: concise, single purpose, no cross-contamination. This consistency makes automated ingestion trivial.

---

## 🛡 Guardrail Principles
From `Agent Forge/guardrails.md` (summarized):
- Only design/refine agent definitions
- Never simulate the agent itself
- Keep responses structured & deployable
- Avoid unnecessary verbosity

---

## 🤝 Contributing
Contributions welcome. Ideas:
- New specialized agents
- Improved guardrail patterns
- Additional tone archetypes
- Tooling scripts (validation / linting of agent blocks)

Proposed flow:
1. Fork
2. Add your agent in a new folder (`Your Agent Name/` with `README.md`, `instructions.md`, `guardrails.md`, `tone.md`)
3. Keep wording tight and purposeful
4. Open a PR with a short rationale

Lightweight review preference: clarity > cleverness.

---

## 📌 Naming & Style Conventions
- Folder names: `Pascal Case`
- Files: `README.md`, and one file per semantic block
- Tone docs: short, voice-defining, not instructional
- Guardrails: imperative bullet points

---

## 📄 License
MIT. Have fun.

---

## 🙋 FAQ
**Why not combine everything into one file per agent?**
Separation improves remixability and automated ingestion.

**Can this be used outside Mistral?**
Probably. It's made for use with Mistral, so some adjustments will probably be required though.

---

## 🔗 Related Files
- `Agent Forge/instructions.md`
- `Agent Forge/guardrails.md`
- `Agent Forge/tone.md`

---

## 🙌 Acknowledgments
Inspired by community experimentation and iterative prompt engineering patterns. If you discovered this via a Reddit thread—welcome.

---

## 📨 Feedback
Open an issue or PR. Concise, actionable suggestions appreciated.

---

Happy forging.