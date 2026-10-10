# Third-party notices

Tinariox (ранее LocalLLM Chat) bundles, links against, or downloads the components below.
The application is proprietary freeware — see `LICENSE` (Tinariox Proprietary License).
Third-party components remain under their own licenses listed below.

## Linked into the APK

| Component | License | Notes |
|-----------|---------|-------|
| sherpa-onnx (incl. `sherpa-onnx-static-link-onnxruntime-1.13.5-no-espeak.aar`) | Apache-2.0 | k2-fsa/sherpa-onnx v1.13.5, rebuilt locally **without espeak-ng** (`SHERPA_ONNX_WITH_ESPEAK=OFF`, clean-room stub); see `third_party/sherpa-onnx-no-espeak/` and `dev/build-sherpa-no-espeak.ps1` |
| ONNX Runtime | MIT | Microsoft |
| AndroidX, Jetpack Compose, CameraX, Room | Apache-2.0 | Google |
| OkHttp | Apache-2.0 | Square |
| Kotlin stdlib, kotlinx-serialization, kotlinx-coroutines | Apache-2.0 | JetBrains |
| PDFBox-android | Apache-2.0 | |
| SQLCipher for Android | BSD-3-Clause | |
| all-MiniLM-L6-v2 (`assets/minilm-l6-v2.onnx`) | Apache-2.0 | sentence-transformers |

## Downloaded at runtime (not bundled yet)

| Component | License | Notes |
|-----------|---------|-------|
| Supertonic 3 TTS weights (`sherpa-onnx-supertonic-3-tts-int8-*.tar.bz2`) | **Open RAIL-M** | © Supertone Inc. Source code of Supertonic examples: MIT. License text: https://huggingface.co/supertone-oss-archive/supertonic-3/blob/main/LICENSE — use-based restrictions (Attachment A) apply to all users of the model. Repo is archived (Sep 2026); weights mirrored by k2-fsa/sherpa-onnx releases. |
| Streaming STT model (`sherpa-onnx-streaming-zipformer-small-ru-vosk-int8`) | Apache-2.0 | alphacep/vosk-model-small-streaming-ru (icefall-trained) |

## Present in the repository history only (not in the APK)

| Component | License | Notes |
|-----------|---------|-------|
| YOLOv8 weights (`yolov8*.onnx/.pt`) | AGPL-3.0 | Ultralytics. Unused since the demo cut; removed from git index. |
