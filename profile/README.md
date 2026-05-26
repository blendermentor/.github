# Welcome

![BlenderMentor Logo](LogoType.png)

Open-source Blender tools built around one idea: the best way to learn is by actually doing it ourseleves than letting an AI do it for us.

> ⚠️ This is a small side project, vibe coded after work hours, and very much a work in progress, and prone to break easily. Licensed under **GPL v3**.

---

## BlenderMentor

🎓 [BlenderMentor](https://github.com/BlenderMentor/blendermentor) — An AI-powered addon that walks you through Blender's interface step by step, instead of altering your file on behalf of you.


### 🌟 Key Features

- **Context-Aware AI Chat**:<br>
Integrated directly into the Blender N-panel. The AI reads your current scene state (active objects, materials, modifiers, etc.) to provide tailored advice.

- **Guided Step-by-Step Navigation**:<br>
Procedures are broken down into digestible steps.

- **Dynamic UI Highlighting**:<br>
The AI doesn't just tell you what to do, but also highlights editor area, tab groups etc. to guide you where to look.

- **Flexible UI Layouts**:<br>
You may use it in the Sidebar, pop it out into a floating window for dual-monitor setups, or dock it as a split area in your workspace.

- **AI Model options**:<br>
Uses your own API keys for **Gemini** or **Claude**. Supports **Ollama** for running open-source models locally. No hardcoded models — the list is fetched live from the providers.

### ⚠️ Things BlenderMentor doesn't do just yet

- **It's limited to your AI Model's knowledge**:<br>
Since dynamic websearch is not enabled yet, ai will not be able to answer about latest changes in blender.

- **It cannot 'see' your screen**:<br>
Right now, the addon is visually blind. It figures out what you're doing in your project by looking at Blender's internal data model (like mesh names, materials, and active modifiers).

- **It responds only when you ask it to**:<br>
It functions as a simple back-and-forth chat panel in the sidebar. It won't continuously track the actions on screen.

- **Privacy & Control**:<br>
Although BlenderMentor doesn't collect any data, your API provider may, as per their terms. Please check with your provider if you're concerned.

---

### 🚀 Getting Started

- 💡 **For full, detailed setup, key features, and troubleshooting instructions, please check the [BlenderMentor Repository](https://github.com/blendermentor/blendermentor).**

---

## Your contributions are welcome.

Whether you're a Python developer, a technical writer, a 3D artist willing to install the addon and tell us what broke, or someone experienced with managing open-source GitHub projects — your contribution would be genuinely appreciated.

If you'd like to help improve the project, please check out our [CONTRIBUTING.md](https://github.com/blendermentor/blendermentor/blob/98c04bdaebb39e080cd42fe08c17536e5cccdc6c/CONTRIBUTING.md) file for details on how to get started, our development workflow, and coding standards.

---
