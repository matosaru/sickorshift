# 🎲 Sick or Shift?

**One roll. Two fates. Work or duvet?**

Sick or Shift? is a free, playful browser-based dice game for those “Should I go to work tomorrow?” moments. Roll a die and get one of two outcomes: **go to work** or **call in sick**.

The game is a lighthearted reminder to check in with yourself about rest, health, and work–life balance. It isn't a medical assessment or a substitute for making responsible decisions.

## 🎮 How to play

1. Open the game's website or run `index.html` in your browser.
2. Press **Roll the dice!**
3. See what fate has in store:
   - **Even numbers (2, 4, 6):** 💼 Go to work.
   - **Odd numbers (1, 3, 5):** 🛌 Call in sick.
4. Press **Roll again** if you dare.

Each result has a 50% chance. The dice animation is purely for fun.

## ✨ Features

- 🎲 Animated, random six-sided die
- ⚖️ Two equally likely outcomes
- 📱 Mobile-friendly responsive design
- ⚡ A lightweight static site — no backend, accounts, or build tools
- 🔎 SEO metadata, social sharing tags, and structured data
- 💜 Information about health, rest, and work–life balance
- ❓ FAQs about the game and its purpose

## 🌿 Why work–life balance matters

A healthier routine makes room for recovery, relationships, and activities that recharge you. Although rolling a die won't change your life on its own, it can offer a playful pause to ask useful questions:

- Am I actually feeling well enough to work?
- Am I getting enough rest?
- Do I need better boundaries between work and personal time?
- What realistic step could improve my wellbeing?

**Important:** If you're sick, decide whether to work based on your health, relevant professional advice, and workplace policies — not on a random dice roll. Never use this game as a reason to misrepresent your health.

## 🚀 Run locally

No installation required:

```bash
git clone https://github.com/matosaru/sickorshift.git
cd sickorshift
```

Open `index.html` in any modern browser.

## ☁️ Deploy with Cloudflare Pages

1. In [Cloudflare Dashboard](https://dash.cloudflare.com/), navigate to **Workers & Pages**.
2. Create a **Pages** project and connect the GitHub repository `matosaru/sickorshift`.
3. Select the `main` branch and choose **None** for the framework preset.
4. Set the build command to `exit 0` (or leave it blank if Cloudflare allows) and the output directory to `/`.
5. Deploy. Cloudflare will assign a `*.pages.dev` URL, and future pushes to `main` can trigger automatic redeployments.

The exact URL depends on the available Cloudflare project name. Once you have a production domain, add canonical and Open Graph URL metadata to `index.html` to improve search-engine consistency.

## 🛠️ Built with

- HTML
- CSS
- Vanilla JavaScript

Everything is contained in a single `index.html` file.

## 📈 Search and sharing

The homepage includes a descriptive page title, meta description, Open Graph and X/Twitter sharing metadata, and JSON-LD structured data for a free web application. It also contains explanatory text and FAQs for people searching for a fun work-or-sick-day decision game.

Search visibility is not guaranteed; a real domain, crawlability, and useful original content also matter.

## ⚠️ Disclaimer

**Sick or Shift? is entertainment only.** The results are random and aren't medical, mental-health, employment, or legal advice. Prioritize your health and use your own judgment.

---

Made for anyone who's ever stared at Monday on their calendar and wished for a dice roll. 🎲
