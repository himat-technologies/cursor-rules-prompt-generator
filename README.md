<div align="center">

# ✨ Cursor Rules &amp; System Prompt Generator

### Give your AI coding assistant a better rulebook.

Create, customize, and export project-specific instructions for Cursor and AI coding tools.

[![Live Demo](https://img.shields.io/badge/🚀_LIVE_DEMO-Open_the_tool-7C3AED?style=for-the-badge)](https://himat.tech/free-tools/cursor-rules-prompt-generator)
[![GitHub](https://img.shields.io/badge/GitHub-View_repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/himat-technologies/cursor-rules-prompt-generator)
[![Built with React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

**Created with 💜 by [Himat Technologies](https://himat.co.in)**

[🌐 Website](https://himat.co.in) · [📘 Facebook](https://www.facebook.com/people/Himat-technologies/61593829197445/) · [💼 LinkedIn](https://www.linkedin.com/in/himat-technologies-14b1051b4) · [📸 Instagram](https://www.instagram.com/himat_technologies?stkn=djdmcGxweWtwYWI0)

[✉️ info@himat.co.in](mailto:info@himat.co.in) · [📱 94452 34023](tel:+919445234023) · [💬 WhatsApp](https://wa.me/919445234023)

</div>

---

## 🎯 What is this?

A browser-based workspace for creating project-specific AI coding instructions. Choose a stack preset, tune engineering and security standards, add custom rules, and preview, copy, or download your configuration.

<div align="center">

### 🚀 [Try the live demo](https://himat.tech/free-tools/cursor-rules-prompt-generator)

</div>

## 🌈 Features

| ✨ Feature | 📝 Details |
|---|---|
| **Stack presets** | Start with Next.js + React, FastAPI + Pydantic, AI Agents + MCP, React SPA, Node.js, Go, Rust, or a Custom setup. |
| **Flexible instructions** | Edit role, purpose, architecture, coding standards, type safety, errors, testing, performance, accessibility, and security. |
| **Custom rules** | Add, edit, reorder, and remove project-specific rules. |
| **Four output modes** | Generate `.cursorrules`, modern `.mdc`, a raw system prompt, or MCP JSON. |
| **Live workflow** | Preview changes, validate, copy to clipboard, and download your output. |
| **MCP editor** | Configure server names, commands, arguments, and environment variable references. |
| **Local-first** | Generate everything in your browser—no AI API key or backend required. |

## 📦 Output formats

| 📄 Mode | 🗂️ Filename | 📍 Suggested location |
|---|---|---|
| Root Cursor rules | `.cursorrules` | Project root |
| Modern Cursor rules | `main.mdc` | `.cursor/rules/main.mdc` |
| System prompt | `system_prompt.txt` | Prompt library or project notes |
| MCP config | `mcp.json` | `.cursor/mcp.json` |

> **Note:** Downloading a file does not install it automatically. Move it to the suggested location in your project.

## 🧭 How to use

1. Choose a preset or start with **Custom**.
2. Edit the instructions and manage your custom rules.
3. Select one of the four output tabs.
4. For MDC, adjust globs and `alwaysApply` in **Advanced** settings.
5. For MCP, configure server details and use environment-variable references—never real secrets.
6. Validate, copy or download, then place the file at the suggested path.

## 🛠️ Tech stack

<div align="center">

![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-6-646CFF?style=flat-square&logo=vite&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-validation-3E67B1?style=flat-square)
![Vitest](https://img.shields.io/badge/Vitest-tests-6E9F18?style=flat-square&logo=vitest&logoColor=white)

</div>

Also uses Lucide React, browser clipboard, and file APIs.

## 💻 Run locally on Windows

Install a supported [Node.js](https://nodejs.org/) release, then run these commands in PowerShell:

```powershell
git clone https://github.com/himat-technologies/cursor-rules-prompt-generator.git
cd cursor-rules-prompt-generator
npm install
npm run dev
```

Open the local URL printed by Vite.

### 🧪 Build and test

```powershell
npm run test
npm run build
npm run preview
```

Tests cover preset defaults, output generators, custom rule order, MDC frontmatter, MCP JSON, filenames, and empty-rule validation.

## 🔐 Privacy and security

Generation runs in browser memory and requires no API key, backend, or database. Never put real secrets in prompts or MCP files. Review commands and permissions, and prefer least privilege. Local processing does not encrypt downloaded files.

## 🧰 Troubleshooting

- **`npm` is not recognized:** Install Node.js, reopen the terminal, then check `node --version` and `npm --version`.
- **Install errors:** Check your connection and Node.js version, then retry `npm install`.
- **Page not loading:** Keep the Vite process running and open the exact local URL shown in the terminal.
- **MCP config rejected:** Validate the JSON and check the supported format for your Cursor version.

## 📁 Project structure

```text
cursor-rules-prompt-generator/
├── index.html / package.json / tsconfig*.json / vite.config.ts
├── README.md
└── src/
    ├── App.tsx / main.tsx / index.css
    ├── data/presets.ts
    ├── lib/generators.ts / download.ts / validators.ts
    ├── types/config.ts
    └── test/generators.test.ts
```

## 🤝 Contributing

Issues and pull requests are welcome. Visit the [GitHub repository](https://github.com/himat-technologies/cursor-rules-prompt-generator) to get started.

---

<div align="center">

### 💜 Built by Himat Technologies

[🌐 himat.co.in](https://himat.co.in) · [✉️ Email](mailto:info@himat.co.in) · [📱 Call 94452 34023](tel:+919445234023) · [📸 Instagram](https://www.instagram.com/himat_technologies?stkn=djdmcGxweWtwYWI0) · [💼 LinkedIn](https://www.linkedin.com/in/himat-technologies-14b1051b4) · [📘 Facebook](https://www.facebook.com/people/Himat-technologies/61593829197445/)

**[🚀 Open the live demo](https://himat.tech/free-tools/cursor-rules-prompt-generator)**

</div>
