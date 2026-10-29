# Scribely models

Speech-recognition models downloaded by the **Scribely: Voice to Text Notes** Android app
(`com.voxelnova.scribely`). Files are in the [`models-v1` release](../../releases/tag/models-v1).

| File | Used for |
|---|---|
| `tiny-*.int8.onnx`, `tiny-tokens.txt` | Fast model: live text while recording |
| `base-*.int8.onnx`, `base-tokens.txt` | Accurate model: re-transcription after recording |
| `silero_vad.onnx` | Splits speech into phrases |

Whisper © OpenAI (MIT), ONNX export by sherpa-onnx (Apache-2.0), Silero VAD © Silero Team (MIT).
Files are redistributed unchanged; checksums are in `SHA256SUMS`.

The release is produced by `.github/workflows/publish.yml` (Actions → Publish models → Run workflow).
