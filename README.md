<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=AI+Engineer+%7C+Self-hosted+LLMs;RAG+%2B+Knowledge+Graphs;React+Native+%7C+Expo+%7C+TypeScript;Building+AI+for+businesses+most+engineers+never+see)](https://git.io/typing-svg)

</div>

---

## 👋 Who I am

I spent **5 years on the factory floor** — first as a CNC operator running woodworking machines, then as a **production optimizer** automating and restructuring manufacturing workflows at a Slovak carpentry company.

That background changed how I think about software. I don't build demos. I build tools that need to work when a worker is standing at a machine with dirty hands, poor signal, and zero patience for bad UX.

In parallel I taught myself AI engineering. Today I build **self-hosted, privacy-first AI products** for Slovak SMBs — companies that can't afford OpenAI subscriptions, need GDPR compliance, and want everything on their own server.

📍 Bratislava, Slovakia · 🕐 UTC+1 · 📩 masasisa91@gmail.com

---

## 🧠 What I Build

| Project | Description | Stack |
|---------|------------|-------|
| 🤖 **[NUMchat Business](https://github.com/sebastian414/NUMchat-business-demo)** | Self-hosted B2B AI knowledge base. Workers record what's happening by voice — AI classifies, stores, summarizes. All data on company server. | Qwen3-30B · MiniRAG · React Native |
| 📱 **[Alena](https://github.com/sebastian414/alena-demo)** | Voice-first medication assistant for Slovak elderly users (65+). Designed for people who have never used a smartphone app. | React Native · Expo · expo-speech |
| 🗺️ **[interaktivnamapa.sk](https://interaktivnamapa.sk)** | Live interactive map of 289 Slovak heritage sites. Quiz engine, XP gamification, community photo feed, real-time duel mode. | Mapbox GL · Supabase · PostGIS |

---

## 🐛 Recent Fixes Worth Mentioning

Real bugs from my projects — documented as engineering case studies.

**[iOS keyboard overlaps chat input on iPhone 15 Pro](https://github.com/sebastian414/NUMchat-business-demo)**
`KeyboardAvoidingView` with `behavior="height"` miscalculates safe-area insets on iOS 17+ Dynamic Island devices. Migrated to `react-native-keyboard-controller` which reads keyboard frame via native events instead of estimating from screen size.

**[PostGIS landmark pins offset ~50m after schema migration](https://github.com/sebastian414/interaktivnamapa-demo)**
Coordinates were stored without explicit SRID after Supabase schema rebuild. `ST_AsGeoJSON` returned shifted values. Fixed via `ST_SetSRID(..., 4326)` enforcement in insert trigger + batch correction on 289 existing rows.

**[LLM conversation history bleeding across user sessions](https://github.com/sebastian414/NUMchat-business-demo)**
llama.rn context buffer not cleared on PocketBase logout event. New user session inherited previous user's full conversation. Fixed by adding context clear in `pb.authStore.onChange` handler — privacy issue, not just a bug.

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

**NUMchat Business** — private beta, piloting with Slovak SMBs in construction & manufacturing. Applying for SBA Inovuj grant (digital health track) for **Alena**.

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
