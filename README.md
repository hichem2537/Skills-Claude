# 📚 Skills-Claude — Research Paper Skills for Claude

![Claude AI](https://img.shields.io/badge/Claude-AI-blue?style=flat-square)
![License](https://img.shields.io/badge/license-MPL--2.0-green?style=flat-square)
![Publishers](https://img.shields.io/badge/publishers-6-orange?style=flat-square)
![Open Source](https://img.shields.io/badge/open-source-teal?style=flat-square)

A curated collection of **Claude AI skills** to help researchers write, format, and submit academic papers for major scientific publishers — directly from Claude.ai.

> ✨ Drop any `.md` skill file into your Claude project and Claude will instantly follow the exact formatting guidelines of your target journal. No code. No API. Just upload and chat.

---

## ✨ What is a Claude Skill?

A **Claude Skill** is a Markdown instruction file placed in a Claude project. When activated, it gives Claude deep knowledge about a specific task — like formatting an article for Elsevier or writing in Springer Nature style.

How it works:
1. You upload the skill file to a Claude.ai Project
2. Claude reads the instructions automatically
3. Every response follows the publisher's exact guidelines

---

## 📦 Available Skills

| Publisher | Skill File | Journals covered |
|-----------|-----------|-----------------|
| 🟠 **Elsevier** | `SKILL_article_scientifique_elsevier.md` | Cell, Lancet, ScienceDirect, 3000+ journals |
| 🔵 **Springer** | `SKILL_article_scientifique_springer.md` | Springer journals (excl. Nature group) |
| 🟣 **Springer Nature** | `SKILL_article_scientifique_springer_nature.md` | Nature, Scientific Reports, Communications... |
| 🟢 **Wiley** | `SKILL_article_scientifique_wiley.md` | Wiley-Blackwell, AGU, IEEE via Wiley |
| 🔴 **Taylor & Francis** | `SKILL_article_scientifique_taylor_francis.md` | Routledge, CRC Press, T&F journals |
| ⚫ **Inderscience** | `SKILL_article_scientifique_inderscience.md` | IJMIC, IJBSR, IJCAT and 400+ journals |

---

## 🚀 How to Use

### Option 1 — Claude.ai Project (recommended)

1. Go to **[claude.ai](https://claude.ai)** → Create a new **Project**
2. Click **"Add content"** → Upload the skill file matching your target publisher
3. Start chatting — Claude will automatically follow the publisher's guidelines

### Option 2 — System Prompt (API / advanced)

Copy the content of any `SKILL_*.md` file and paste it as your system prompt when calling the Anthropic API.

---

## 💬 Example Prompts

Once a skill is loaded in your project, try:

```
"Write the abstract for my paper on machine learning for climate prediction"
```
→ Claude generates a structured abstract matching the publisher's word limit and section requirements.

```
"Format my references in the correct style for this journal"
```
→ Claude applies APA, Vancouver, Chicago, or the publisher-specific citation style automatically.

```
"Review my introduction and check it against the submission guidelines"
```
→ Claude reviews structure, length, and required elements according to the skill.

```
"I'm submitting to Wiley — adapt this draft to their formatting rules"
```
→ Claude applies all Wiley-specific formatting, ethics statements, and checklist items.

---

## 🗂️ Repository Structure

```
Skills-Claude/
├── SKILL_article_scientifique_elsevier.md
├── SKILL_article_scientifique_springer.md
├── SKILL_article_scientifique_springer_nature.md
├── SKILL_article_scientifique_wiley.md
├── SKILL_article_scientifique_taylor_francis.md
├── SKILL_article_scientifique_inderscience.md
├── humanizer_app.html       ← Bonus: web app to humanize AI-generated text
├── paraphraser.skill        ← Bonus: paraphrasing skill for academic writing
└── README.md
```

---

## 🤝 Contributing

Want to add a skill for another publisher? **Pull requests are very welcome!**

Publishers we'd love to see added:
- [ ] IEEE
- [ ] MDPI / MDPI Open Access
- [ ] PLOS ONE
- [ ] ACM Digital Library
- [ ] Oxford University Press
- [ ] Cambridge University Press

Use any existing `SKILL_*.md` file as a template and follow the same structure.

---

## ⭐ Star this repo

If this saved you time on a paper submission, please consider leaving a ⭐ — it helps other researchers find this resource.

---

## 📄 License

[MPL-2.0](LICENSE) — Free to use, share, and adapt with attribution.

---

*Made with ❤️ for researchers using Claude · [github.com/hichem2537/Skills-Claude](https://github.com/hichem2537/Skills-Claude)*
