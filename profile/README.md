# Welcome

![BlenderMentor Logo](LogoType.png)

Open-source Blender tools built around one idea: the best way to learn is by actually doing it ourseleves than letting an AI do it for us.

> This is a small side project, vibe coded after work hours, and very much a work in progress, and prone to break easily. Licensed under **GPL v3**.

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

- 💡 **For full, detailed setup, key features, and troubleshooting instructions, please read our [Installation and Usage Guide](https://github.com/blendermentor/blendermentor/blob/e7d97624e5e63ad05957442d0dc986fcecca7213/INSTRUCTIONS.md).**

---

## You're Welcome Here

Whether you're a Python developer, a technical writer, a 3D artist willing to install the addon and tell us what broke, or someone experienced with managing open-source GitHub projects — your contribution would be genuinely appreciated.
Please feel free to clone/fork the [Repository](https://github.com/blendermentor/blendermentor) and submit your changes.

---
