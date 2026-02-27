# Supported Frameworks

**Click. Speak. Fix.**

ClickSay detects popular web frameworks and maps URLs to file paths, making your AI prompts even more actionable.

---

## Framework Detection (Pro)

When you capture an element, ClickSay identifies the framework your app is built with and includes the **component name** and **file path** in the output. This helps AI tools understand exactly where to make changes in your codebase.

Supported frameworks include:

- React
- Vue
- Angular
- Svelte
- Next.js
- SvelteKit
- And more

---

## URL-to-File Mapping

ClickSay can map the URL of the page you're viewing to the corresponding file in your project. This means your AI prompt includes the actual file path - so the AI knows exactly which file to edit.

### Setting Up File Mapping

1. Right-click the ClickSay icon and select **Options**
2. Set your **Project Root** (e.g., `/Users/you/projects/my-app`)
3. Choose a **URL-to-File Mapping** preset or create custom rules

### Available Presets

| Preset | Best For |
|--------|----------|
| Static Site | Plain HTML/CSS/JS projects |
| Next.js | Next.js apps (App Router and Pages Router) |
| SvelteKit | SvelteKit projects |
| React CRA | Create React App projects |

You can also define custom mapping rules if your project has a non-standard structure.

---

## How It Works

When you capture an element on a page:

1. ClickSay detects the framework from the page's HTML and scripts
2. It identifies the component that rendered the captured element
3. It applies your URL-to-File Mapping rules to resolve the file path
4. The component name and file path are included in your clipboard output

This gives AI tools the full picture: what element, which component, and where the code lives.

---

## Pro Feature

Framework detection, component names, and file path output are **Pro features**. On the Free plan, you still get element capture with selectors, HTML, and styles - just without the framework-specific context.

[Upgrade to Pro](https://clicksay.net/#pricing) to unlock framework detection.

---

## Learn More

- [Features Guide](features.md) - Full feature overview
- [Getting Started](getting-started.md) - Setup and configuration
- [Pricing](pricing.md) - Compare Free and Pro
