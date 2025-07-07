# 📥 Inbox Zero – Email Automation Workflow

> *Classify. Summarize. Declutter. Automatically.*

This folder contains a streamlined **n8n** workflow designed to automate your email system using **LLMs** like Azure OpenAI or local models (Ollama, OpenRouter, etc.). From classification to smart summaries and reply generation, this setup moves you closer to Inbox Zero—on autopilot.

---

## 🗂️ File Included

| File           | Purpose                         |
|----------------|---------------------------------|
| `workflow.json`| The full n8n automation workflow|

---

## 🚀 How to Use

1. Open your **n8n** instance (cloud or self-hosted).
2. Import `workflow.json` using the ➕ Import button in the editor.
3. Configure the following:
   - ✉️ IMAP/SMTP credentials for your email provider
   - 🤖 API credentials for your chosen LLM (Azure OpenAI, etc.)
4. Review classification categories & prompts.
5. Set a trigger (e.g. every 15 minutes or on webhook).
6. Test, tune, and enjoy your clean inbox!

---

<details>
  <summary>💡 Pro Tips</summary>

  - Store sensitive credentials in **n8n’s Credentials Manager**.
  - Customize prompt language to match your tone of voice.
  - Add logic to forward, archive, or log important summaries to Notion, Obsidian, or Slack.
  - Extend with daily digest summaries or notification bots.

</details>

---

## 📺 Walkthrough Video

🎥 [Inbox Zero: How I Automated My Email](https://youtu.be/aeauRwQoeoY)  
[![Watch on YouTube](https://img.youtube.com/vi/aeauRwQoeoY/hqdefault.jpg)](https://youtu.be/aeauRwQoeoY)

---

## 🙌 Contribute

This workflow is part of the [`automating-the-little-things`](https://github.com/DaraOladapo/automating-the-little-things) project.  
PRs and variations (e.g. with Gmail Threads API or Notion archiving) are very welcome.

---

**License:** MIT  
**Author:** [Dara Oladapo](https://github.com/DaraOladapo)
