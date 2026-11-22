# OpenCV

<img width="1973" height="1162" alt="ArgusChain_Dashboard" src="https://github.com/user-attachments/assets/d75fb283-073e-4361-a608-2f6582eb66ad" />

# ArgusChain

**ArgusChain** is a desktop AI chat and computer vision analysis application written in pure Rust (`eframe`/`egui`, version 0.5.0). It runs as a single `ArgusChain.exe` binary without a WebView or separate runtime.

- **AI Chat**: Connects to OpenAI-compatible endpoints, DeepSeek, Anthropic, Google Gemini, and local models (Ollama, LM Studio, llama.cpp), with streaming responses.
- **Vision (OpenC)**: Implements the `cv2` API in pure Rust without linking OpenCV. includes QR, Data Matrix, and 1D barcode reading, video analysis, live monitoring, and Inspection Station (part inspection recipes).
