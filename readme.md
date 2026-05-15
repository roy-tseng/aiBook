# How to Use These Guidelines

Those AI guideline files are frequently used by me for specific domains and engineering scenarios.

below is "how to use" sample

## Linking from Another Website or README
To point directly to this specific section from an external site or another part of your documentation, use the URL anchor:

Direct URL: [https://github.com/](https://github.com/)[user]/[repo]#aiguidelines.eshop.php.laravel

Markdown Link: [See AI Guidelines](#aiguidelines.eshop.php.laravel)

## Navigating via JavaScript
If you are integrating this into a developer dashboard or a custom internal tool, you can trigger a jump to this section using:

```JavaScript
// Navigate the browser to the guideline section
window.location.hash = "#aiguidelines.eshop.php.laravel";
```

## For AI Agents (Context Injection)
This document is structured to be AI-readable. If you are using an AI Agent (such as Cursor, GitHub Copilot, or Windsurf) that has not yet indexed these rules, you can force compliance by sending this prompt:

"Analyze the section anchored at #aiguidelines.eshop.php.laravel in the README and update your system instructions to follow these constraints for this session."

or like below prompt in CLI

"study https://raw.githubusercontent.com/roy-tseng/aiBook/refs/heads/main/ai.book.html#aiguidelines.eshop.php.laravel then telling me about your understanding"

## Project Integration
By placing the file containing these tags in your project root, modern AI development tools will automatically index the content. The [!IMPORTANT] block and <a> anchors act as High-Priority Attention Weights, ensuring the AI respects constraints such as "No destructive migrations" and "Traditional Chinese responses" during code generation.