# FutureLab AI Usage Documentation

This is where FutureLab keeps the Markdown (`.md`) files we use when working with AI. They are rules, guides and instructions that you attach to a prompt or drop into a project so your AI tools follow them. Files are sorted into categories by the kind of work they're for: coding, content, images, social media, and anything else we use AI for.

**Public and free to use.** Anyone can use, copy and adapt these files, for personal or commercial work.

## Categories

| Category | What it covers | Files |
|---|---|---|
| **Coding** | Building apps and websites with AI coding tools | [AI Security Rules](coding/AI_SECURITY_RULES.md) |
| **Content** | Writing and editing text with AI | Coming soon |
| **Images** | Generating and editing images with AI | Coming soon |
| **Video** | AI video and animation | Coming soon |
| **Social media** | Posts, captions and campaigns made with AI | Coming soon |

More categories will be added as we publish new files.

## Files

### Coding

- **[AI Security Rules](coding/AI_SECURITY_RULES.md)**: security rules for apps built with AI coding tools ("vibe coding"), written for people who aren't developers. It tells the AI how to handle API keys, databases, login, file uploads, payments and AI features safely, and gives you 17 simple tests to run yourself before launch.

## How to use these files

### 1. Get the file

Open the file on GitHub and use the **Download raw file** or **Copy raw file** button at the top right of the file view.

Or download it straight into your project from a terminal:

```bash
curl -O https://raw.githubusercontent.com/futurelabnz/AI-Usage-Documentation/main/coding/AI_SECURITY_RULES.md
```

### 2. Give it to your AI

| Where you use AI | What to do |
|---|---|
| **Chat apps** (Claude, ChatGPT, Gemini) | Attach the file to your message. To use it in every chat, add it to a Claude Project, a ChatGPT Project or a Gemini Gem. |
| **Claude Code** | Save the file in your project folder and add `@FILE_NAME.md` to your `CLAUDE.md`. |
| **Cursor** | Add it as a Project Rule set to always apply, or attach it in chat with `@`. |
| **Codex and other coding agents** | Save it in your project and reference it from `AGENTS.md`. |
| **Lovable, Bolt, Replit, v0 and similar** | Paste it into the project's knowledge or custom instructions, or attach it to your prompt. |

### 3. Tell the AI to follow it

For example: *"Follow the rules in the attached file for everything you build in this chat."*

Many files start with their own instructions and ready-made prompts. Read the top of the file first.

### 4. Keep it up to date

We improve these files over time. Download them again now and then, and check the commit history to see what changed.

## Contributing

Found a mistake or have an improvement? Open an issue or a pull request. Keep files in plain Markdown, put them in the right category folder, and write them so someone who isn't an expert can follow them.

## Disclaimer

These files are provided as is, without warranty. They make AI tools work more safely and consistently, but they don't replace professional advice. For example, get a proper security review before your app handles sensitive data or payments.

---

Made by [FutureLab](https://futurelab.digital).
