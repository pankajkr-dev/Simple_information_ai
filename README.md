# Simple_information_ai

This repository contains a small information-focused AI agent example that demonstrates how an assistant can use workspace content as context to answer questions.

**Features:**
- **Context-aware answers:** Uses files placed in the workspace as the agent's knowledge source.
- **Easy to extend:** Add documents or tweak prompts to improve answers.
- **Minimal demo:** Includes a simple frontend example for quick exploration.

**How it works:**
- The agent reads the files you provide in the workspace and builds a contextual prompt.
- Prompts are sent to an AI backend (configure the model or API in your code), and the agent returns concise answers with references to source files.

**Usage:**
- Open [index2.html](index2.html) in your browser to view the simple demo.
- Add or update files in the workspace to change the agent's knowledge base.
- Configure the AI backend or prompt settings in your project code before running real queries.

**Development notes:**
- Add new documents to the repository to expand the agent's context.
- Keep prompts and backend configuration separated so you can swap models or endpoints easily.

**License & Contributing:**
- This project is provided as a simple demo. Feel free to fork, adapt, and improve it. Open a PR for contributions.

For more details see [README.md](README.md).
