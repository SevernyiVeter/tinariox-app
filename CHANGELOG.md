# Tinariox changelog

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
