# Tinariox

**Local-first AI companion for Android.** Talks with voice, remembers you, helps with tasks — powered by your own LLM server. No cloud required; cloud providers optional.

Early beta: expect bugs, some features are still in development.

## Features

- **Chat** — connects to LM Studio, Ollama, KoboldCpp, text-generation-webui, or any OpenAI-compatible server
- **Voice** — speech input and spoken replies built in
- **Companion** — has a personality, mood and greetings; not a faceless chatbot
- **Memory** — remembers facts and past conversations, searches your documents (PDF and more)
- **Tasks & reminders** — ask in plain language
- **Private by default** — conversations and memory stay on your device; the model runs on your own machine

## Install

1. Download the latest APK from [Releases](../../releases).
2. On your phone, allow installation from this source when Android asks.
3. Open the app and set the address of your LLM server.

Requires Android 8.0+ (API 26), arm64.

## Connect your LLM server

| Method | How |
|--------|-----|
| **Wi-Fi** | Run LM Studio or Ollama on your computer in the same network. In Tinariox settings enter the computer's IP (e.g. `192.168.1.10`). Server auto-discovery is supported. |
| **Cloud** | Server type `OpenAI-compatible` + your provider URL. |

## Feedback

Found a bug or have an idea? Open an [issue](../../issues).

## License

Tinariox is free proprietary software; source code is closed. See [LICENSE](LICENSE).

Third-party components and their licenses: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
