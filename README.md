<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=AI+Engineer+%7C+Self-hosted+LLMs;RAG+%2B+Knowledge+Graphs;React+Native+%7C+Expo+%7C+TypeScript;Building+AI+for+businesses+most+engineers+never+see)](https://git.io/typing-svg)

</div>

---

## 👋 Who I am

I spent **5 years on the factory floor** — CNC operator, then production process optimizer at a Slovak woodworking company. I automated scheduling, reduced material waste, and rebuilt how the shop floor communicated internally.

That background shapes everything I build. I optimize for workers with dirty hands, bad signal, and zero patience for slow UX.

In parallel I taught myself AI engineering. Today I build **self-hosted, privacy-first AI products** for Slovak SMBs — companies that need GDPR compliance, want data on their own server, and can't rely on cloud APIs going down.

📍 Bratislava, Slovakia · 🕐 UTC+1 · 📩 masasisa91@gmail.com

> *Repos marked `-demo` are public code samples — full products are private (commercial, client data). Each demo contains real extracted code and production screenshots.*

---

## 🧠 What I Build

| | Project | Status | Stack |
|--|---------|--------|-------|
| <img src="https://raw.githubusercontent.com/sebastian414/NUMchat-business-demo/main/docs/screenshots/01-home-voice.png" width="60" /> | **[NUMchat Business](https://github.com/sebastian414/NUMchat-business-demo)** — B2B AI knowledge base. Voice input, offline-first, GDPR. | 🔒 Private beta | Qwen3-30B · MiniRAG · RN |
| <img src="https://raw.githubusercontent.com/sebastian414/alena-demo/main/docs/screenshots/01-home.png" width="60" /> | **[Alena](https://github.com/sebastian414/alena-demo)** — Medication assistant for Slovak elderly (65+), voice-first. | 🔒 UI complete, grant pending | React Native · Expo |
| <img src="https://raw.githubusercontent.com/sebastian414/interaktivnamapa-demo/main/docs/screenshots/01-map-overview.png" width="60" /> | **[interaktivnamapa.sk](https://interaktivnamapa.sk)** — Live map, 289 landmarks, quiz, XP, community feed. | ✅ **Live in production** | Mapbox GL · Supabase · PostGIS |

---

## 🐛 Recent Fixes

**[iOS keyboard overlaps chat input — iPhone 15 Pro](https://github.com/sebastian414/NUMchat-business-demo)**
`KeyboardAvoidingView` height behavior miscalculates safe-area insets on iOS 17+ Dynamic Island. Migrated to `react-native-keyboard-controller` (native frame events, not screen size estimation).

**[PostGIS pins offset ~50m after schema migration](https://github.com/sebastian414/interaktivnamapa-demo)**
Coordinates stored without SRID after Supabase schema rebuild. Fixed via `ST_SetSRID(..., 4326)` in insert trigger + batch correction on all 289 rows.

**[LLM context bleeding across auth sessions](https://github.com/sebastian414/NUMchat-business-demo)**
llama.rn context buffer not cleared on logout. New user inherited previous session's full conversation history. Fixed in `pb.authStore.onChange` handler — privacy issue.

---

## 🔧 Stack

**AI / ML**

![Anthropic](https://img.shields.io/badge/Anthropic_Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper_STT-412991?style=flat-square&logo=openai&logoColor=white)

**Frontend / Mobile**

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Backend / Infra**

![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![PocketBase](https://img.shields.io/badge/PocketBase-B8DBE4?style=flat-square&logo=pocketbase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?style=flat-square&logo=hetzner&logoColor=white)

---

## 🎯 Active Focus

**NUMchat Business** in private beta with Slovak SMBs. One live production app: [interaktivnamapa.sk](https://interaktivnamapa.sk).

---

## 📊 GitHub Stats

<div align="center">
<img height="160" src="https://github-readme-stats.vercel.app/api?username=sebastian414&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sebastian414&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />
</div>

---

## 📫 Contact

[![Email](https://img.shields.io/badge/masasisa91%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:masasisa91@gmail.com)

> **Available for:** AI subcontracting · RAG architecture · React Native · Slovak/Czech NLP
> **Rate:** €45–55/h · EU VAT invoice · UTC+1 · 15h/week
