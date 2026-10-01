# BeamDrop P2P - Direct P2P File and Folder Transfer (Lightweight Edition)

BeamDrop P2P is a modern desktop application that enables direct, encrypted, and high-speed device-to-device (Peer-to-Peer) file transfer without relying on any cloud service.

Powered by the native Windows Microsoft Edge WebView2 runtime and a Python backend, it comes in at just **14.3 MB**.

---

## Key Features

- **Ultra-Lightweight Footprint (14.3 MB):** Unlike the previous Electron version (~110 MB), all redundant libraries have been stripped out, reducing the size by 8x.
- **Custom Destination Folder:** Incoming files are written directly to the user-selected directory.
- **Both Internet (WebRTC NAT Punch) & LAN (Wi-Fi):** Transfer across different networks using a single room code or locally over the same Wi-Fi.
- **Large File & Folder Support (Zero-RAM Streaming):** Files are streamed directly to disk rather than buffered in RAM.
- **3 Selectable Enterprise Themes:** Midnight Obsidian (Dark), Nordic Slate (Navy), and Pure Light.
- **Bilingual Interface:** Built-in Turkish and English language support.
- **Zero Emojis & Crisp Vector SVGs:** Clean, enterprise-ready UI icons throughout.
- **Integrity Verification (SHA-256):** Checksum validation to ensure transferred files remain uncorrupted.