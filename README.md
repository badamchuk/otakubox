# 🌸 OtakuBox

> Anime-themed Telegram bot powered by [Pollinations.ai](https://pollinations.ai) — image generation, custom stickers, illustrated stories, and more.

[![Powered by Pollinations.ai](https://img.shields.io/badge/Powered%20by-Pollinations.ai-ff69b4?style=flat-square)](https://pollinations.ai)
[![Telegram](https://img.shields.io/badge/Telegram-%40otakubox__bot-26A5E4?style=flat-square&logo=telegram)](https://t.me/otakubox_bot)
[![Live Demo](https://img.shields.io/badge/Landing-Live-success?style=flat-square)](https://badamchuk.github.io/otakubox/)
[![Languages](https://img.shields.io/badge/Languages-10-blueviolet?style=flat-square)](#)

🔗 **Landing page**: https://badamchuk.github.io/otakubox/
🤖 **Try it on Telegram**: [@otakubox_bot](https://t.me/otakubox_bot)

---

## ✨ What it does

OtakuBox turns Telegram into a personal anime studio. Every image, sticker,
emoji, and illustrated story is generated on-demand by **Pollinations.ai** —
the bot is a thin orchestration layer that stitches together prompts, themes,
energy quotas, and a 10-language UI on top of Pollinations' open-access
generation API.

### Features

- 🎨 **40+ anime image styles** — Studio Ghibli, shōnen, shōjo, cyberpunk,
  watercolor, manga ink, chibi, mecha, and more (Fast & HQ tiers)
- 🧩 **Custom emoji packs** — generate themed Telegram emoji sets (6/12/20)
- 📦 **Sticker pack creation** — auto-published Telegram sticker packs from a
  single theme prompt
- 📖 **Daily illustrated stories** — multi-panel anime stories with cover art,
  scenes, and narrative text
- 📡 **Channel auto-posts** — Character of the Day, Sticker of the Day,
  Art of the Day, weekly digests (APScheduler)
- 💬 **AI chat with memory** — multi-turn conversations powered by OpenAI
  (GPT-4o-mini) with Gemini fallback
- 🥷 **Secret Shinobi** — anonymous matchmaking chat with content filtering
- 🔮 **Daily horoscope & predictions** — personalised, illustrated
- 🎮 **Mini-games** — Tic-Tac-Toe, Big TTT, Minesweeper, Dots & Boxes,
  Battleship, Snake, 2048, Tanks, Brick Blaster, Shooter (solo + PvP)
- ⚡ **Energy economy** — daily refills, ad rewards, Telegram Stars
  micro-payments, referral bonuses
- 🌍 **10-language UI** — Ukrainian, English, Polish, German, French, Spanish,
  Italian, Japanese, Turkish, Chinese

---

## 🛠 Tech Stack

| Layer | Tools |
|---|---|
| **Image generation** | [Pollinations.ai](https://pollinations.ai) (Flux, Z-Image) |
| **Text / chat** | OpenAI `gpt-4o-mini`, Google Gemini (fallback) |
| **Bot framework** | [aiogram 3.x](https://github.com/aiogram/aiogram) |
| **Web layer** | aiohttp (WebApp servers for in-game UI) |
| **Scheduling** | APScheduler |
| **Storage** | SQLite (WAL mode) via aiosqlite |
| **Runtime** | Python 3.11, Docker, docker-compose |
| **Hosting** | Self-hosted on NVIDIA Jetson (ARM64), Cloudflare Tunnel |

---

## 🌸 Why Pollinations.ai

OtakuBox is built around Pollinations.ai as its **core image generation
engine** — every visual the bot produces (avatars, character cards, stickers,
emoji, story panels, ship art, daily features) comes from Pollinations.

Pollinations' open API and generous quotas make it possible to ship a
free-to-use, multilingual anime bot without locking creative features behind
paywalls.

---

## 📸 Screenshots

> _Screenshots coming soon — see the [live landing page](https://badamchuk.github.io/otakubox/) for a feature showcase._

---

## 🔗 Links

- 🌐 Landing: https://badamchuk.github.io/otakubox/
- 🤖 Bot: https://t.me/otakubox_bot
- 🌸 Pollinations.ai: https://pollinations.ai

---

> _The bot's source code is kept in a private repository. This repository hosts
> the public landing page and project metadata._
