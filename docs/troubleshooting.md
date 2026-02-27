# Troubleshooting

**Click. Speak. Fix.**

Running into an issue? Check the solutions below.

---

## Keyboard Shortcut Not Working

The default shortcut is `Cmd + Shift + K` (Mac) or `Ctrl + Shift + K` (Win/Linux). If it's not responding:

1. Go to `chrome://extensions/shortcuts` in your browser
2. Find **ClickSay** in the list
3. Check if a shortcut is assigned - if not, click the pencil icon and set one
4. Make sure no other extension is using the same shortcut

---

## Microphone Not Working

If voice feedback isn't picking up your speech:

- **Check permissions:** Make sure you've allowed microphone access for Chrome. Look for the mic icon in the address bar or go to Chrome Settings > Privacy and Security > Site Settings > Microphone.
- **Close other apps:** If another application (like Zoom, Teams, or another browser tab) is using your microphone, close it first.
- **Browser support:** Voice feedback uses the Web Speech API. Make sure you're using a recent version of Chrome.
- **Try again:** Click the mic icon in the side panel to restart recording.

---

## Can't Capture Elements on a Page

ClickSay cannot capture elements on:

- `chrome://` pages (settings, extensions, etc.)
- The Chrome Web Store
- Other restricted browser URLs

This is a Chrome security restriction that applies to all extensions. Navigate to a regular web page to use ClickSay.

---

## Side Panel Not Opening

If clicking the ClickSay icon doesn't open the side panel:

1. Look for the ClickSay icon in your toolbar
2. If you don't see it, click the **puzzle piece** icon (Extensions menu)
3. Find ClickSay and click the **pin** icon to add it to your toolbar
4. Click the ClickSay icon to open the side panel

---

## Output Not Copying to Clipboard

If the structured prompt isn't copying when you press Enter or click copy:

- **Check clipboard permission:** Chrome should prompt you for clipboard access. Make sure you allow it.
- **Use the copy button:** Try clicking the copy button directly in the side panel instead of pressing Enter.
- **Try again:** Close and reopen the side panel, capture a new element, and try copying again.

---

## Voice Limit Reached

On the Free plan, you get **20 voice feedback captures per month**. If you've reached the limit:

- Your usage resets at the beginning of each month
- [Upgrade to Pro](https://clicksay.net/#pricing) for unlimited voice feedback

---

## Screenshot Limit Reached

On the Free plan, you get **5 screenshots per month**. If you've reached the limit:

- Your usage resets at the beginning of each month
- [Upgrade to Pro](https://clicksay.net/#pricing) for unlimited screenshots

---

## Extension Not Appearing

If ClickSay isn't showing up in Chrome:

1. Go to `chrome://extensions`
2. Make sure ClickSay is listed and the toggle is **enabled** (blue)
3. If it's not listed, [reinstall from the Chrome Web Store](https://chromewebstore.google.com/detail/clicksay-ai-feedback-copi/cpnmelphcmdcmejmjfnodmpdtifccfhj)
4. After reinstalling, pin it to your toolbar (puzzle piece icon > pin)

---

## Speech Recognition Quality

Voice feedback quality depends on your microphone and environment:

- **Use a quiet environment** - background noise can reduce accuracy
- **Speak clearly** - natural pace, not too fast
- **Use a decent microphone** - built-in laptop mics work, but a headset or external mic gives better results
- **Check your browser** - Chrome typically provides the best speech recognition results

---

## Still Need Help?

- **Community:** Ask in [Discussions](https://github.com/Fredlumiere/clicksay-community/discussions)
- **Bug reports:** Open an [Issue](https://github.com/Fredlumiere/clicksay-community/issues)
- **Website chat:** [clicksay.net](https://clicksay.net)
