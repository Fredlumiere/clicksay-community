# ClickSay Features

**Click. Speak. Fix.**

Everything ClickSay can do, all in one place.

---

## Element Capture

Press `Cmd + Shift + K` (Mac) or `Ctrl + Shift + K` (Win/Linux) to enter capture mode. Hover over any element on the page and you'll see an orange outline. Click to capture it.

ClickSay captures rich context about the element, including:

- Tag name, ID, and classes
- Attributes and text content
- HTML snippet
- CSS selector and XPath
- Bounding rectangle and viewport dimensions
- Computed styles
- Surrounding context HTML and sibling elements
- Page metadata
- Framework detection (Pro)
- Accessibility audit (Pro)
- Timestamp

You can also right-click any element and select **"ClickSay this element"** from the context menu.

> **Note:** Element capture does not work on `chrome://` pages or the Chrome Web Store due to browser restrictions.

---

## Voice Feedback

After capturing an element, your microphone starts automatically. Just speak your feedback naturally.

- Uses your browser's built-in Speech API
- Continuous recognition mode with interim and final results
- A **"Listening..."** indicator shows when recording is active
- Click the **mic icon** or press **Enter** to stop recording
- You can also start and stop recording from the side panel

**Free plan:** 20 voice captures per month. **Pro:** Unlimited.

---

## Sweep Mode (Pro)

Capture multiple elements in a single session.

1. Hold **Shift** and **click** each element you want to include
2. Click normally (without Shift) on the last element to finish your selection
3. Speak a single piece of feedback that applies to all selected elements

Great for batch changes like "make all these buttons the same size" or "align these cards consistently."

---

## Screenshots (Pro)

ClickSay automatically captures a screenshot with the selected element highlighted. The screenshot is included in your output prompt so the AI can see exactly what you see.

**Free plan:** 5 screenshots per month. **Pro:** Unlimited.

---

## Output Presets

Control how much detail goes into your clipboard prompt by choosing a preset:

| Preset | Plan | Detail Level |
|--------|------|--------------|
| Simple | Free | Minimal - just the basics |
| Standard | Free | Balanced - good for most tasks |
| Detailed | Pro | Rich - includes extra context |
| Full | Pro | Everything - maximum detail |

---

## Output Pills

Toggle specific data types on or off to customize exactly what goes into your output.

**Free pills:**
- URL
- Selector
- Text content
- HTML
- Styles
- Context
- File path

**Pro pills:**
- Screenshot
- Component name
- Accessibility audit

---

## History

All your captures are saved in the side panel for easy access.

- **Free plan:** 7-day retention
- **Pro:** Unlimited history

You can purge your history at any time using the controls in the side panel.

---

## Copy to Clipboard

When you're done capturing and speaking, press **Enter** or click the **copy button** in the side panel. A structured, AI-ready prompt is copied to your clipboard - ready to paste into Claude, ChatGPT, Cursor, or any other AI tool.

---

## Summary

| Feature | Free | Pro |
|---------|------|-----|
| Element captures | Unlimited | Unlimited |
| Voice feedback | 20/month | Unlimited |
| Screenshots | 5/month | Unlimited |
| Sweep mode | - | Yes |
| Output presets | Simple, Standard | All four |
| Output pills | Basic | All (incl. screenshot, component, a11y) |
| Framework detection | - | Yes |
| Accessibility audit | - | Yes |
| History retention | 7 days | Unlimited |
| Context menu capture | Yes | Yes |

---

## Learn More

- [Getting Started](getting-started.md) - Installation and setup
- [Pricing & Plans](pricing.md) - Upgrade to Pro
- [Supported Frameworks](frameworks.md) - Framework detection details
- [Troubleshooting](troubleshooting.md) - Common issues and fixes
