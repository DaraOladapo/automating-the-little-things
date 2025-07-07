# ⚙️ Automating the Little Things

> *Small tasks, big gains—one automation at a time.*

This is a growing collection of practical, real-world automations designed to eliminate friction from your day-to-day. Whether you're a developer, educator, or creator, this repo helps you reclaim time by offloading the repetitive stuff.

Built with tools like **n8n**, **Synology NAS**, and a range of **LLMs including Azure OpenAI**, it's ideal for those exploring the power of self-hosted workflows and intelligent systems.

---

## 🚀 What You'll Find

- 🧩 **Ready-to-use workflows** (n8n, Logic Apps, etc.)  
- 🤖 **LLM-powered demos** (Azure OpenAI, self-hosted models & more)  
- 🔧 **Use-case driven setups**: Think email triage, content automation, and beyond  
- 🏗️ **Deploy-anywhere configurations** for home labs or the cloud

---

## 💡 Featured: Inbox Zero Workflow  
A smart, auto-classifying inbox assistant powered by:
- `n8n` for orchestrating the flow  
- `LLMs` for natural language understanding (classification, summarization)  
- `IMAP/SMTP` for universal email provider support  
- `Synology NAS` + `Cloudflare Tunnel` for self-hosted flexibility

📂 Get started → [`./workflows/inbox-zero.json`](./workflows/inbox-zero.json)  
📺 Walkthrough Video → [Watch on YouTube](#)

---

## 🛠 Tool Stack

| Tool                     | Purpose                                  |
|--------------------------|------------------------------------------|
| `n8n`                    | Automation engine (no-code/low-code)     |
| `LLMs (Azure OpenAI, etc.)` | Text classification, summarization       |
| `Synology NAS`           | Self-hosted workflow runner              |
| `Cloudflare Tunnel`      | External webhook exposure                |
| `Docker & YAML`          | Containerized deployment configs         |

---

## 🎯 Why This Repo Exists

Because the little things matter.  
**Automate what drains your time—focus on what fuels your creativity.**

---

<details>
  <summary>💬 Frequently Asked Questions</summary>

  ### 📌 What kind of automations are in this repo?
  Mostly task-level workflows—things like email classification, AI-assisted drafting, file sorting, social media triggers, etc. These are meant to be modular and adaptable for different setups.

  ### 🤖 Which LLMs are supported?
  The current demos use Azure OpenAI, but the workflows are adaptable to **any LLM with an API**, including local models hosted via Ollama, LM Studio, or OpenRouter-compatible backends.

  ### 🏠 Can I run this on a home server?
  Absolutely. Many of these were built on a **Synology NAS** using Docker Compose, but you can run them on any local machine, cloud VPS, or even a Raspberry Pi—just tweak the configs accordingly.

  ### 📧 Will the email workflows work with Gmail/Outlook?
  Yes! As long as your provider supports **IMAP and SMTP**, you're good to go. Auth setup may differ depending on 2FA and app passwords.

  ### 🙋 Can I contribute?
  Yes please. Open a PR, raise an issue, or just share ideas—I'd love to collaborate and grow this toolkit with the community.

</details>

---

More automations in the pipeline.  
Pull requests, issues, and ideas are welcome!

**License:** MIT  
**Author:** [Dara Oladapo](https://github.com/DaraOladapo)
