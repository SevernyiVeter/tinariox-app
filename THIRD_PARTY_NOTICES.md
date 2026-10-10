# Third-party notices

Tinariox bundles, links against, or downloads the components below.
The application is proprietary freeware — see [LICENSE](LICENSE).
Third-party components remain under their own licenses listed here.

## Linked into the APK

| Component | License |
|-----------|---------|
| sherpa-onnx (speech: STT/TTS runtime) | Apache-2.0 |
| ONNX Runtime | MIT |
| AndroidX, Jetpack Compose, CameraX, Room | Apache-2.0 |
| OkHttp | Apache-2.0 |
| Kotlin stdlib, kotlinx-serialization, kotlinx-coroutines | Apache-2.0 |
| PDFBox-android | Apache-2.0 |
| SQLCipher for Android | BSD-3-Clause |
| all-MiniLM-L6-v2 (embeddings model in APK assets) | Apache-2.0 |

## Downloaded at runtime (not bundled in the APK)

| Component | License | Notes |
|-----------|---------|-------|
| Supertonic 3 TTS weights | **Open RAIL-M** | © Supertone Inc. Use-based restrictions in Attachment A of the license apply. Weights are fetched when you install a voice in the app. |
| Streaming STT model (Russian zipformer) | Apache-2.0 | On-device speech recognition model |

You can review the license texts at the upstream project pages (k2-fsa/sherpa-onnx, Microsoft ONNX Runtime, Google AndroidX, Supertone Supertonic, etc.).
