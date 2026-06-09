# ElevenLabs Demo Website Template

This repository provides a reusable template for creating demo websites with an embedded ElevenLabs Conversational AI agent.

The goal is to quickly spin up a branded demo (web + voice/chatbot) in just a few minutes.

---

# What this template includes

- Pre-configured HTML demo page
- ElevenLabs widget integration
- Reusable layout (hero section + styling)
- Placeholder elements for quick customization
- GitHub Pages ready

---

# How to create a new demo (Step-by-step)

## 1. Create a new repo from this template

- Click **"Use this template"**
- Name your new repo (e.g. `bina-istra-demo`)

---

## 2. Update the agent ID & Image

Open `index.html` and update this line:

```html
<elevenlabs-convai
  agent-id="REPLACE_AGENT_ID"
