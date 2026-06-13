# ⚖️ Petty Debate Judge

> *"Justice for arguments that absolutely did not need a judge."*

![petty judge](./assets/petty.png)

An AI-powered courtroom drama app that settles your most ridiculous everyday debates — with full theatrical flair, a live animated judge, a rowdy audience, and scorecards. Built in one day as a Claude Artifact.

🔗 **[Try it live →](https://claude.ai/public/artifacts/d955a40e-2376-4c9f-959a-372c2d699344)**

---

## What it does

You bring the debate. The Honorable Judge delivers the verdict.

- Submit any petty question — *"Is cereal a soup?" "Toilet paper: over or under?"*
- Both sides argue their case
- The AI Judge weighs the evidence, cites absurd legal precedents, and rules
- The gallery erupts with topic-specific heckles
- The Judge slams the gavel: **ORDER IN MY COURT**
- Scorecards for Logic, Pettiness, and Style — because justice demands metrics

Every debate produces a completely unique verdict, audience reaction, and set of judge dialogue — no two cases sound alike.

---

## Features

- 🧑‍⚖️ **Animated SVG judge** — bobs, blinks, furrows his brows while deliberating, slams the gavel, and smirks at the verdict
- 💬 **Live speech bubble** — topic-aware quips that change as you type, rotate during deliberation, go red and shouty when the gallery gets out of hand
- 👥 **Rowdy audience** — 4 AI-generated petty heckles specific to your debate, animated in one by one
- 📊 **Scorecards** — logic, pettiness, and style scores with animated fill bars for each side
- 🎉 **Confetti verdict drop** — because every ruling deserves a moment
- ✨ **Tap-to-fill example topics** — so anyone can play instantly
- 📱 Responsive — works on mobile and desktop

---

## Built with

| Tool | Role |
|---|---|
| [Claude Artifacts](https://claude.ai) | Build & host environment |
| React + Hooks | UI framework |
| Anthropic Claude API (`claude-sonnet-4-6`) | AI judge, verdicts, audience heckles |
| Pure SVG + CSS animations | Animated judge character |
| Tailwind-free custom CSS | All styling in-component |

No build step. No backend. No database. The entire app is a single React component calling Claude's API at runtime.

---

## How it was built

This was built entirely inside **Claude Artifacts** — Anthropic's in-chat app builder — without writing any code manually. The process:

1. Described the idea to Claude in plain English
2. Iterated on the UI through conversation ("make it more modern", "add a petty judge character", "add a rowdy audience")
3. Hit **Publish** to get a shareable link

Total time: ~30 minutes of iterative prompting.

---

## Running it yourself

The live link above requires a free Claude account to use (the app calls Claude's API at runtime).

To run it without a login requirement, you can self-host:

```bash
# 1. Clone this repo
git clone https://github.com/yourusername/petty-debate-judge

# 2. Set up a React + Vite project
npm create vite@latest petty-debate-judge -- --template react
cd petty-debate-judge

# 3. Replace src/App.jsx with the component in /src
# 4. Add your Anthropic API key to .env
VITE_ANTHROPIC_API_KEY=your_key_here

# 5. Run locally
npm install && npm run dev
```

Get an API key at [console.anthropic.com](https://console.anthropic.com) — free tier available.

---

## More projects in this series

| App | Status | Description |
|---|---|---|
| ⚖️ Petty Debate Judge | ✅ Live | AI courtroom drama for silly arguments |
| 🌿 Plant Matchmaker | 🔨 Building | Find your perfect plant like a dating app |
| 🐱 Why Is My Cat Doing That | 🔨 Building | Decode your cat's chaotic behavior |
| 🎸 Ukulele Chord Coach | 🔨 Building | Song-to-chords generator for beginners |

---

## Author

Built by [Nikita Kumari](https://www.linkedin.com/in/nikitakumari22/)

*Verdicts are legally meaningless and emotionally binding.*
