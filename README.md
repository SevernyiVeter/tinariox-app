# Tinariox

**Local-first AI companion for Android.** Talks with voice, remembers you, helps with tasks — powered by your own LLM server. No cloud account; cloud providers optional.

> **Early beta.** Expect bugs. Several experimental modules are still in development and are not in this build (computer vision, smart home, multi-agent, ComfyUI, code execution, games, and other prototypes). The list of what works today is below.

[Русская версия](README.ru.md)

<p align="center">
  <img src="docs/screenshots/main-chat.jpg" width="220" alt="Main chat">
  <img src="docs/screenshots/companion-setup.jpg" width="220" alt="Companion setup">
  <img src="docs/screenshots/chat-actions.jpg" width="220" alt="Chat actions">
</p>

## What works in this beta

| Area | What you get |
|------|----------------|
| **Chat** | Streaming chat with LM Studio, Ollama, KoboldCpp, text-generation-webui, or any OpenAI-compatible server (Wi-Fi / LAN or cloud URL) |
| **Voice** | On-device speech input and spoken replies (STT/TTS) |
| **Companion** | Personalities, mood, first-meeting onboarding — not a faceless bot |
| **Memory** | Facts about you, conversation history, knowledge graph |
| **Tasks** | Reminders and tasks in plain language, with calendar-style views |
| **Documents** | Load PDFs and ask questions about your own files |
| **Private by default** | Chat and memory stay on your device; the model runs on your machine or endpoint you choose |

More screens: [navigation](docs/screenshots/navigation.jpg), [tasks](docs/screenshots/tasks.jpg), [settings](docs/screenshots/settings.jpg).

## Install

1. Download the latest APK from [Releases](../../releases).
2. On your phone, allow installation from this source when Android asks.
3. Open the app and connect your LLM server (see below).

**Requirements:** Android 8.0+ (API 26), **arm64**.

**APK:** `app-release.apk` (~198 MB — includes bundled on-device speech models).

**SHA-256 (v20.0-demo):**

```
A485AAF32520F3598972D60A7870026DC212C6D63FB9D42CCFC4B42614D4363B
```

Verify after download (example):

```powershell
Get-FileHash .\app-release.apk -Algorithm SHA256
```

## Connect your LLM server

| Method | How |
|--------|-----|
| **Wi-Fi / LAN** | Run LM Studio or Ollama on your computer in the same network. In Tinariox settings enter the computer’s IP (e.g. `192.168.1.10`). LAN auto-discovery is supported. |
| **Cloud** | Server type `OpenAI-compatible` + your provider URL. |

Firewall tips: allow the app’s port on your PC (LM Studio often `1234`, Ollama `11434`).

## Feedback

Found a bug or have an idea? Open an [issue](../../issues) — device model, Android version, and your LLM server help a lot.

## Support the project

Tinariox is free. If it is useful, you can support further development — new voices, stability, and the modules still in progress:

- **Boosty:** [boosty.to/severnyiveter/donate](https://boosty.to/severnyiveter/donate)
- **USDT (Solana):** `AexDs2eE1HBPLoBM3HGMkkfdSNjZQuVn8F72rTYtSGLv`

Donations are optional and do not unlock paid features — everything in the app stays free.

## License

Tinariox is free proprietary software; source code is closed. See [LICENSE](LICENSE).

Third-party components and their licenses: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

---

<sub>Tinariox — local AI companion. Your data stays with you.</sub>
