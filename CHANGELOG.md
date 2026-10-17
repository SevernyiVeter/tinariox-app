# Tinariox changelog

## v20.0.6 (beta) — 2026-10-17

Download: [release v20.0.6](../releases/tag/v20.0.6)

### Highlights

- **Theme Studio** — custom three-color palette, accent picker, fonts, chat layout, wallpapers, named presets with JSON export/import
- **Russian voice** — Supertonic pronunciation frontend (dictionary stress + neural accentor), number/date/unit expansion, TTS Lab
- **Web & tools** - `web_search` back as a first-class tool, broader RU/EN triggers, per-tool toggles, system-prompt guide for local models
- **In-app updates** — daily GitHub release check, notification, in-app download + system install
- **Security hardening** — internal tokens stored encrypted, safer local-server traffic, stronger PIN hashing, integrity checks for the voice model and updates
- versionCode 26

SHA-256: `1FDB906AA3fdc463C021897E79AF2D50F016D4852DC981C24791A3C51932431E`


## v20.0.5-demo (beta) — 2026-10-13

Download: [release v20.0.5](../../releases/tag/v20.0.5)

### Highlights

- **Memory Garden** — new “Memory” menu section: full list of remembered facts (search, categories, inline edit, “Forget”), dialogue fragments, knowledge-graph portal, and “Erase all” with confirmation
- **RAG improvements** — document chunks actually injected into the answer context; new `query_documents` tool; better MiniLM embeddings (mean-pooling, bundled models) — more accurate document search, especially for Russian; web search no longer substitutes a random PDF on weak matches
- **Chat fixes** — no more stalled empty replies after tool calls; honest “nothing found” messages for documents; one automatic retry on transient HTTP 5xx
- **Diagnostics** — app logs mirrored to logcat in release builds (adb-friendly)
- versionCode 25

SHA-256: `C60419E959D0BDC7F2C692424FF2223133568F4424248A2190036EA28BE7C585`

## v20.0.2-demo (beta) — 2026-10-11

- Settings → Advanced: toggle “Hide chat from screenshots” (FLAG_SECURE), default ON
- versionCode 22

SHA-256: `7469B70236E99DEBFFED4FF255CB354FE23FF7784ABCF8093555F51C52023BA5`

## v20.0.1-demo (beta) — 2026-10-11

Bugfix release.

- FLAG_SECURE: chat hidden from screenshots and Recents preview
- PIN lockout counters persist across process death
- Release builds no longer fall back to the debug signing key
- versionCode 21

SHA-256: `A867EAAD8624D44E1F30747A9D3F43DDD975ACF8F0828BCEA2BA089A35E798A7`

## v20.0-demo (beta) — 2026-10-10

First public beta of the Tinariox Android app (APK-only distribution).

### Included

- Chat with local / OpenAI-compatible LLM servers (streaming)
- On-device voice input and speech output
- Companion onboarding and personalities
- Memory, facts, knowledge graph
- Tasks and reminders
- Document Q&A (PDF)
- LAN server discovery

### Not in this build

Some experimental features remain under development and are **not included** in the public beta. This release focuses on a stable core: chat, voice, companion, memory, tasks, documents.

### Files

- `app-release.apk` — ~198 MB, arm64, Android 8.0+
- SHA-256: `A485AAF32520F3598972D60A7870026DC212C6D63FB9D42CCFC4B42614D4363B`
