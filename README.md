# teneo-models

Immutable, SHA-256-pinned on-device model artifacts for [Teneo](https://github.com/theCodeD3vil/teneo).

Teneo downloads these files only when a user explicitly opts into Local AI in Settings, verifies exact byte length and SHA-256 digest locally, and runs inference inside an App-Sandboxed XPC service with zero network entitlements.

## Releases

- **`q12-v1`** — MiniLMv2 lookup-quantized Q12 credential classifier (`teneo-minilm-q12.onnx` + `teneo-minilm-q12.spm`).
