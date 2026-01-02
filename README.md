# 🤖 AI-CV-Chat

> Your CV, but make it talk — **interactive, front-end only, scalable chat widget using free/open LLM APIs (BYOK).**

---

## 🧩 What is AI-CV-Chat?

**AI-CV-Chat** turns your resume or portfolio into a **live chat experience** where an AI persona answers questions **only from the CV facts you define** — in **first person**, with built-in guardrails to avoid hallucination.

This is a **static web widget**.  
You don’t need:

- ❌ Backend servers  
- ❌ Python
- ❌ Databases
- ❌ Paid hosting

Just drop `index.html` into your repo and deploy.

---

## ✨ Core Features

- 💬 ChatGPT-style **familiar chat UI**
- ⌨️ **Press Enter to send messages**
- 🔌 **Bring Your Own API Key (BYOK)**  
  *(You choose your provider + add your API key)*
- 🔁 **Swap providers by changing one line**  
  - Hugging Face Inference
  - TogetherAI
  - Groq
  - OpenRouter, etc.
- 🌍 Deploy anywhere static:
  - GitHub Pages
  - Netlify
  - Vercel
  - Cloudflare Pages
- 🔒 Privacy-friendly → **No personal data is stored**

---

## 🚀 Deploy on GitHub Pages

1. Upload `index.html` to this repo
2. Go to: **Settings → Pages**
3. Select branch: `main`
4. Click **Save**
5. Open your live link and start chatting

---

## ⚙️ Swap API Providers (Example)

Only edit this inside the script:

```js
providerEndpoint = "api-inference.huggingface.co/v1/chat/completions";
