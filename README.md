# AI Clipboard — Prompt Backup & Recovery

**Never lose an AI prompt again.**

AI Clipboard automatically saves your prompts when you send them on supported AI chat websites. If your message fails because of an unstable internet connection, VPN problems, a page reload, rate limit, or another unexpected issue, you can quickly find and restore your prompt.

Your prompts stay **on your device**. The extension does not send your data to any external server.

## ✨ What does AI Clipboard do?

When you send a prompt on a supported AI chat website, AI Clipboard automatically creates a local backup of it.

You can then:

* 🔒 Keep a local backup of your prompts
* 📋 Optionally copy prompts to your clipboard when sending
* 🔄 Restore a previous prompt with one click
* 🔍 Search through your saved prompts
* 🌐 Filter prompts by website
* ⚠️ Get a warning when a message may not have been sent successfully
* 💾 Export your prompt history as a backup file
* 📥 Import your history whenever you need it
* ⌨️ Restore your latest prompt with a keyboard shortcut

---

## 🌐 Supported websites

AI Clipboard currently supports:

* ChatGPT
* Gemini
* Claude

The extension is designed specifically for AI chat interfaces and automatically detects the message composer.

---

## 📥 Installation

### Chrome

Install AI Clipboard from the **Chrome Web Store**.

> Chrome Web Store link: **Coming soon**

### Firefox

Install AI Clipboard from **Firefox Add-ons (AMO)**.

> Firefox Add-ons link: **Coming soon**

No account or registration is required.

---

## 🚀 How to use

After installing the extension, simply use your AI chat website normally.

### Save a prompt

Write your message and send it normally by:

* Pressing **Enter**
* Clicking the **Send** button

AI Clipboard automatically saves a backup of the prompt.

You don't need to press any additional buttons.

### View your saved prompts

Click the **AI Clipboard** extension icon in your browser toolbar.

Your saved prompts will appear in the history.

From there you can:

* Restore a prompt
* Copy a prompt
* Delete a prompt
* Search your history
* Filter prompts by website

### Restore a prompt

Select a prompt and click **Restore**.

The prompt will be placed back into the AI chat input so you can continue editing or send it again.

You can also restore your latest saved prompt using:

**Windows / Linux:** `Ctrl + Shift + Z`

**macOS:** `Command + Shift + Z`

The keyboard shortcut can be changed from your browser's extension shortcut settings.

---

## ⚠️ Failed message detection

Sometimes an AI website clears your message even though the message was not successfully sent.

AI Clipboard can detect some of these situations.

If a message appears to have failed, the extension may show:

> ⚠️ Message may not have been sent

A **Restore prompt** button can then appear, allowing you to quickly recover your message.

This feature uses local browser information and does not inspect or send your conversations to an external service.

You can disable this feature from **Settings** if you don't want these warnings.

---

## ⚙️ Settings

AI Clipboard includes several options so you can choose how it behaves.

### Enable extension

Turn the extension on or off.

### Copy prompt to clipboard on send

When enabled, your prompt is also copied to your clipboard whenever you send it.

This option is **off by default**.

> Enabling this option means the extension will replace the current contents of your clipboard when you send a prompt.

### Show toast notifications

Show small notifications such as:

> ✅ Prompt saved

You can disable these notifications if you prefer a completely silent experience.

### Warn about suspected failed sends

Enable or disable the failed-message detection feature.

### Floating restore button

Choose whether the **Restore prompt** button should appear when a message may have failed.

### Prompts to keep

Choose how many prompts should be kept in your local history:

* 10
* 50
* 100

The default is **50 prompts**.

When the limit is reached, older prompts are automatically removed to make room for newer ones.

---

## 💾 Backup & Restore

Your prompt history is stored locally in your browser.

You can create your own backup at any time from:

**Settings → Backup → Export History**

The extension creates a file similar to:

```text
prompt-history-2026-08-08.json
```

### Importing a backup

You can later import the file from the same settings page.

Importing a backup **does not replace your existing history**.

Instead, AI Clipboard:

* Keeps your existing prompts
* Adds prompts from the backup
* Removes exact duplicates
* Keeps the newest prompts when the history limit is reached

This makes it safe to import the same backup file more than once.

### Important

Because your history is stored only on your device:

**Uninstalling the extension or resetting your browser profile may permanently remove your saved prompts.**

If your prompt history is important to you, we recommend exporting a backup periodically.

---

## 🔐 Privacy

Privacy is a core part of AI Clipboard.

### Your prompts stay on your device

AI Clipboard does **not** send your prompts to a server.

There are:

* ❌ No accounts
* ❌ No analytics
* ❌ No tracking
* ❌ No telemetry
* ❌ No external AI API
* ❌ No cloud storage

Your prompt history is stored locally using your browser's extension storage.

### No external network communication

The extension does not need an internet connection to store or restore your prompts.

Your prompts are not uploaded anywhere.

For complete details, see our:

**[Privacy Policy](privacy-policy.md)**

---

## 🛡️ Your data

AI Clipboard only needs access to the supported AI chat websites in order to detect when you send a prompt and save it locally.

The extension does not request access to every website.

Your saved prompt history is not synchronized between browsers or devices.

If you use AI Clipboard on another computer, it will have its own separate history unless you manually export and import your backup.

---

## ❓ Frequently Asked Questions

### Does AI Clipboard send my prompts anywhere?

No.

Your prompts remain in your browser's local extension storage.

### Does it work without an internet connection?

The extension itself can save and restore prompts locally. However, the AI website you are using obviously needs an internet connection to send and receive messages.

### Does it automatically send restored prompts?

No.

Restoring a prompt only puts the text back into the AI chat input. You remain in control of whether and when to send it.

### Will it save every message I send?

It saves prompts when it detects a submission through the supported AI chat interface.

### What happens if I send the same prompt twice?

The extension prevents accidental duplicate saves when the same prompt is triggered multiple times within a short period.

### Can I delete my history?

Yes.

You can delete individual prompts from the history or clear the entire history from Settings.

### Can I move my history to another computer?

Yes.

Use **Export History** on the old browser and **Import History** on the new one.

---

## 🌍 Browser support

AI Clipboard is designed to work across modern Chromium-based browsers and Firefox.

The project provides separate builds for:

* Google Chrome
* Mozilla Firefox

Other Chromium-based browsers may also work, depending on their extension compatibility.

---

## 💙 About the project

AI Clipboard was created to solve a simple but frustrating problem:

**You shouldn't lose a long AI prompt just because the message failed to send.**

The project is privacy-first, lightweight, and designed to stay out of your way while you work.

### Developer

**[Your Name]**

[View the project on GitHub](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY)

### Other projects

Check out my other browser extensions and projects on GitHub:

[View all projects](https://github.com/YOUR_USERNAME)

---

## 🐛 Found a problem?

If AI Clipboard isn't working correctly on a supported website, please open an issue on GitHub.

When reporting a problem, it is helpful to include:

* Browser and browser version
* AI website where the problem occurred
* What you expected to happen
* What actually happened

Please **do not include private conversations or sensitive prompts** in bug reports.

[Report a problem on GitHub](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY/issues)

---

## 📄 License

See the [LICENSE](LICENSE) file for license information.
