# GitHub Profile README

<!-- SÚBOR: seastian414/sebastian414/README.md -->

---

```markdown
<div align="center">

<!-- Typing SVG header - mení sa každých pár sekúnd -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=AI+Engineer+%7C+Self-hosted+LLMs;RAG+%2B+Knowledge+Graphs;React+Native+%7C+Expo;Building+AI+for+Slovak+SMBs)](https://git.io/typing-svg)

**Slovak AI engineer building privacy-first, self-hosted AI products.**  
5 years CNC operator → production optimizer → full-stack AI builder.  
I build AI for the businesses most engineers never see.

[![Location](https://img.shields.io/badge/📍-Žilina%2C+Slovakia-0d1117?style=flat-square)](https://github.com/YOUR_USERNAME)
[![Timezone](https://img.shields.io/badge/🕐-UTC%2B1_(EU)-0d1117?style=flat-square)](https://github.com/YOUR_USERNAME)
[![Availability](https://img.shields.io/badge/💼-Available_15h%2Fwk-238636?style=flat-square)](mailto:YOUR_EMAIL)
[![Invoice](https://img.shields.io/badge/💶-EU_VAT_invoice-0d1117?style=flat-square)](mailto:YOUR_EMAIL)

</div>

---

## 🧠 What I Build

| Project | Description | Stack |
|---------|------------|-------|
| 🧠 **[FirmaMozog](https://github.com/YOUR_USERNAME/FirmaMozog)** | Self-hosted B2B AI knowledge base for SMBs. GDPR-compliant, no data leaves your server. | Qwen3-30B · MiniRAG · KG |
| 📱 **[Alena](https://github.com/YOUR_USERNAME/Alena)** | Voice-first medication assistant for Slovak elderly users (65+). | React Native · Expo · TTS |
| 🤖 **[NUMchat](https://github.com/YOUR_USERNAME/NUMchat)** | Privacy-first Slovak AI assistant running fully on-device. | EuroLLM-9B · llama.rn |
| 🗺️ **[interaktivnamapa.sk](https://interaktivnamapa.sk)** | Production map of 289 Slovak heritage sites. | PostGIS · Supabase · React |

---

## 🔧 Stack

**AI / ML**  
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-8B5CF6?style=flat-square&logo=meta&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper_STT-412991?style=flat-square&logo=openai&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Frontend / Mobile**  
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

**Backend / Infra**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PocketBase](https://img.shields.io/badge/PocketBase-B8DBE4?style=flat-square&logo=pocketbase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?style=flat-square&logo=hetzner&logoColor=white)

---

## 🐛 Recent Fixes Worth Mentioning

> Real bugs from my projects — documented as engineering case studies.

- **[iOS keyboard overlap in RN chat](https://github.com/YOUR_USERNAME/FirmaMozog/issues/1)** — `KeyboardAvoidingView` height miscalc on iPhone 15 Pro (Dynamic Island + iOS 17+). Migrated to `react-native-keyboard-controller` with native frame events.
- **[PostGIS landmark coordinate drift](https://github.com/YOUR_USERNAME/interaktivnamapa-sk/issues/1)** — wrong SRID caused ~50m pin offset after Supabase schema migration. Fixed via explicit `ST_SetSRID` enforcement in insert triggers.
- **[EuroLLM context bleed on logout](https://github.com/YOUR_USERNAME/NUMchat/issues/1)** — conversation history persisting across PocketBase auth sessions. Fixed by clearing context buffer on `onAuthStateChange` event.

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />

</div>

---

## 📫 Contact

[![Email](https://img.shields.io/badge/Email-YOUR_EMAIL-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-YOUR_LINKEDIN-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)

> Available for: **AI subcontracting · RAG architecture · Slovak/Czech NLP · React Native**  
> Rate: **€45–55/h** · EU VAT invoice · UTC+1
```

---
---
---

# REPO README ŠABLÓNY
# (skopíruj do každého repozitára)

---

## 🧠 FirmaMozog — README.md

```markdown
# FirmaMozog — Self-hosted AI Knowledge Base

> "Firemný mozog" — AI which knows everything your company knows.  
> All data stays on your server. Zero OpenAI. GDPR compliant.

![Demo](docs/demo.gif) <!-- pridaj neskôr -->

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Stack](https://img.shields.io/badge/LLM-Qwen3--30B-blue)](https://huggingface.co/Qwen)
[![RAG](https://img.shields.io/badge/RAG-MiniRAG-purple)](https://github.com/gusye1234/mini_rag)
[![Mobile](https://img.shields.io/badge/Mobile-React_Native-61DAFB)](https://reactnative.dev)

## What it does

FirmaMozog lets employees ask questions about internal company knowledge in plain Slovak.
Upload contracts, manuals, invoices, emails — the AI answers with citations, never fabricates.

**Key principles:**
- 🔒 Self-hosted — your data never leaves your server
- 📎 Citations only — every answer references its source document
- 📱 Mobile-first — React Native app, works offline
- 🇸🇰 Slovak-first — optimized for Slovak SMBs

## Architecture

```
Mobile App (RN/Expo)
    ↓
PocketBase API (auth + sync)
    ↓
Qwen3-30B-A3B (main LLM, Scaleway GPU)
    ↓
MiniRAG + pgvector (knowledge graph + semantic search)
    ↓
Company documents (PDF, DOCX, emails)
```

## Stack

- **LLM:** Qwen3-30B-A3B (MoE, 30B params / 3B active)
- **Router:** Qwen3-0.6B (fast intent classification)
- **Vision:** Qwen2.5-VL-7B (photo/invoice OCR)
- **STT:** Whisper (voice input)
- **RAG:** MiniRAG + knowledge graph
- **Mobile:** React Native + Expo
- **Backend:** PocketBase + PostgreSQL/pgvector
- **Infra:** Scaleway GPU → Hetzner dedicated

## Status

🚧 Private beta — piloting with 1-3 Slovak SMBs.  
Contact: [YOUR_EMAIL] for pilot access.
```

---

## 📱 Alena — README.md

```markdown
# Alena — Voice-First Medication Assistant

> Built for Slovak seniors (65+) who forget their medication.  
> Voice-first. No complex UI. Works offline.

[![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-black)](https://expo.dev)
[![Framework](https://img.shields.io/badge/Framework-React_Native_%2B_Expo-61DAFB)](https://expo.dev)
[![Language](https://img.shields.io/badge/Language-Slovak-blue)](https://sk.wikipedia.org/wiki/Slovenčina)
[![Status](https://img.shields.io/badge/Status-UI_Complete-green)](https://github.com/YOUR_USERNAME/Alena)

## What it does

Alena reminds Slovak seniors to take their medication — via voice, not
text. Designed for users who have never used a smartphone app before.

**8 screens, complete UI:**
1. Welcome / onboarding
2. Medication list
3. Add medication (voice or manual)
4. Daily schedule
5. Reminder notification
6. Confirmation screen ("Vzal som si")
7. History / log
8. Settings (family contact, language)

## Design principles

- **Voice-first:** every action can be completed by speaking
- **Large targets:** 56px+ tap areas, high contrast
- **Slovak only:** no English fallback, proper Slovak grammar
- **Offline-capable:** no internet required for reminders

## Stack

- React Native + Expo
- expo-speech (TTS) + expo-av (audio)
- expo-notifications (scheduled reminders)
- AsyncStorage (local data, no backend)

## Screenshots

<!-- Add after: npx shots --device iPhone15Pro -->

## Status

UI complete. Backend integration in progress.  
Applying for SBA Inovuj grant (digital health category).

## Contact

Pilot interest or grant partnership: [YOUR_EMAIL]
```

---

## 🤖 NUMchat — README.md

```markdown
# NUMchat — Privacy-First Slovak AI Assistant

> Slovak AI that runs entirely on your phone. No server. No data sent anywhere.  
> Powered by EuroLLM-9B via llama.rn.

[![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-black)](https://expo.dev)
[![Model](https://img.shields.io/badge/Model-Qwen3--1.7B_Q4__K__M-orange)](https://huggingface.co/Qwen)
[![Runtime](https://img.shields.io/badge/Runtime-llama.rn-red)](https://github.com/mybigday/llama.rn)
[![Privacy](https://img.shields.io/badge/Privacy-100%25_On--device-green)](https://github.com/YOUR_USERNAME/NUMchat)

## What it does

NUMchat is a Slovak AI assistant that runs the full LLM on your device.
Nothing leaves your phone. No API calls. No telemetry.

## On-device model

| Model | Size | Speed (iPhone 13) | Slovak quality |
|-------|------|-------------------|----------------|
| Qwen3-1.7B Q4_K_M | ~1.1 GB | ~18 tok/s | ✅ Good (119 lang) |

Model fits within App Store 2GB download limit.

## Stack

- React Native + Expo
- llama.rn (C++ llama.cpp bindings for iOS/Android)
- EAS Build (required for native modules)
- PocketBase (optional sync, off by default)

## Build

```bash
# Requires EAS Build (no Expo Go support for llama.rn)
eas build --platform ios --profile preview
```

## Privacy

- Model runs 100% on-device via llama.cpp
- No network requests during inference
- No analytics, no telemetry
- Optional: PocketBase sync can be enabled but is off by default
```

---

## 🐛 Bug Fix Issues — copy-paste do GitHub Issues

### Issue #1 — FirmaMozog

**Title:** `fix: iOS keyboard overlaps chat input on iPhone 15 Pro`

**Body:**
```
## Bug

When keyboard opens in the chat screen, the text input field is hidden
behind it on notched iPhones running iOS 17+.

Affects: iPhone 15 Pro, 15 Pro Max, 14 Pro (Dynamic Island models)
iOS: 17.0+
Not affected: Simulator (keyboard behavior differs)

## Root cause

`KeyboardAvoidingView` with `behavior="height"` doesn't correctly
account for safe-area insets on newer devices. The Dynamic Island
changes the safe area top inset and this throws off height calculations.

## Fix

Migrated to `react-native-keyboard-controller` which reads the keyboard
frame via native event listener instead of estimating height from screen
size. Added `bottomOffset={20}` to ensure the input stays above the
keyboard.

## Code

**Before:**
```jsx
<KeyboardAvoidingView behavior="height" style={{flex: 1}}>
  <ChatMessages />
  <ChatInput />
</KeyboardAvoidingView>
```

**After:**
```jsx
import { KeyboardAwareScrollView } from 'react-native-keyboard-controller';

<KeyboardAwareScrollView bottomOffset={20}>
  <ChatMessages />
  <ChatInput />
</KeyboardAwareScrollView>
```

## Labels
`bug` `ios` `react-native` `keyboard`
```

---

### Issue #2 — interaktivnamapa-sk

**Title:** `fix: PostGIS landmark pins offset by ~50m after schema migration`

**Body:**
```
## Bug

After Supabase schema migration, all landmark pins appear ~50 meters
off from their real position on the map.

Affects: all 289 landmarks
Browser: all

## Root cause

The insert function was storing coordinates without explicit SRID.
When the schema was recreated, PostGIS defaulted to SRID 4326 but
the stored data had no SRID tag — causing `ST_AsGeoJSON` to return
coordinates in a shifted reference frame.

## Fix

Added explicit `ST_SetSRID(..., 4326)` in the insert trigger.
Ran batch correction via `BEGIN; UPDATE landmarks SET geom =
ST_SetSRID(geom, 4326); COMMIT;`

## Labels
`bug` `postgis` `supabase` `database`
```

---

### Issue #3 — NUMchat

**Title:** `fix: conversation history bleeds across user sessions on logout`

**Body:**
```
## Bug

After logout + login as different user, the previous user's conversation
history is still visible in chat. Context from previous session persists.

## Root cause

The LLM context buffer (llama.rn session) is held in memory and not
cleared on PocketBase `onAuthStateChange` logout event. The new user
session starts with the old context still loaded.

## Fix

Added context clear in auth state listener:

```typescript
pb.authStore.onChange((token, model) => {
  if (!token) {
    // User logged out — clear LLM context
    llamaContext?.stopCompletion();
    setMessages([]);
    setLlamaContext(null);
  }
});
```

## Labels
`bug` `auth` `llama.rn` `privacy`
```

---

## ✅ GIT COMMIT pre každý fix

### FirmaMozog keyboard fix:
```bash
git add .
git commit -m "fix: resolve keyboard overlap on notched iPhones

KeyboardAvoidingView height behavior doesn't account for safe-area
insets correctly on iOS 17+ devices with Dynamic Island.

Migrated to react-native-keyboard-controller which uses native
keyboard frame events instead of estimating height from screen size.
Added bottomOffset={20} for consistent spacing above keyboard.

Closes #1"
git push
```

### PostGIS coordinate fix:
```bash
git commit -m "fix: enforce SRID 4326 on landmark geometry inserts

Coordinates were stored without explicit SRID after schema migration,
causing ~50m drift in pin positions due to reference frame ambiguity.

Added ST_SetSRID(geom, 4326) in insert trigger and ran batch
correction on existing 289 rows.

Closes #1"
```

### NUMchat session fix:
```bash
git commit -m "fix: clear LLM context on PocketBase auth logout

Conversation history from previous user session persisted in memory
because llama.rn context was not cleared on logout event.

Added context cleanup in pb.authStore.onChange handler.
Privacy issue: different users could see previous session messages.

Closes #1"
```

---

## 📸 Alena Screenshots — postup

### 1. Spusti Expo Go / simulator
```bash
cd alena
npx expo start
# Otvor v iOS Simulator (iPhone 15 Pro)
```

### 2. Screenshoty zo simulatora
- Cmd+S v Xcode simulatore → uloží PNG
- Alebo: Device → Screenshot v menu

### 3. iPhone mockup zadarmo
Choď na **shots.so** (zadarmo):
1. Upload screenshot PNG
2. Vyber iPhone 15 Pro frame
3. Nastav background (tmavý odporúčam)
4. Export PNG

### 4. GIF demo (voliteľné, veľmi efektívne)
```bash
# Na Mac:
brew install ffmpeg
# Nahraj screen recording → konvertuj:
ffmpeg -i recording.mov -vf "fps=10,scale=390:-1" -loop 0 demo.gif
```

### 5. Pridaj do README
```markdown
<div align="center">
  <img src="docs/screenshots/home.png" width="200" />
  <img src="docs/screenshots/medication.png" width="200" />
  <img src="docs/screenshots/reminder.png" width="200" />
</div>
```

---

## 🔗 Užitočné linky

- **github-readme-stats:** `https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=github_dark`
- **Typing SVG:** `https://readme-typing-svg.demolab.com` 
- **Shields.io badges:** `https://shields.io`
- **shots.so** — iPhone mockups zadarmo
- **Profile README generator:** `https://gprm.itsvg.in`
