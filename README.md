<div align="center">
  <img src="https://raw.githubusercontent.com/umuxt/codeMapSpace/main/assets/icon.png" width="120" alt="CodeMap Space Logo" />
  <h1>CodeMap Space</h1>
  <p><strong>Bring your codebase to an interactive visual graph. Understand architecture instantly.</strong></p>
</div>

## 🚀 Downloads (v2.1.0)

- **macOS Apple Silicon (M1/M2/M3):** [Download DMG](https://github.com/umuxt/codeMapSpace/releases/latest/download/CodeMap.Space-2.1.0-arm64.dmg)
- **macOS Intel:** [Download DMG](https://github.com/umuxt/codeMapSpace/releases/latest/download/CodeMap.Space-2.1.0.dmg)
- **Windows:** [Download EXE](https://github.com/umuxt/codeMapSpace/releases/latest/download/CodeMap.Space.Setup.2.1.0.exe)

## What is CodeMap Space?

CodeMap Space is a powerful desktop application that visualizes your codebase, allowing you to explore files, dependencies, and architecture through an interactive node graph.

It also acts as an **MCP (Model Context Protocol)** server provider, allowing AI Assistants (like Claude Desktop or Gemini) to query your code architecture visually and semantically without sending your code to the cloud.

---
*Note: This repository is used for distribution and releases. The source code is maintained privately.*

## 🛠 Troubleshooting

### macOS: "App is damaged and can't be opened"
Because this app is not notarized by an Apple Developer account, macOS might put it in quarantine. To fix this:
1. Move **CodeMap Space.app** to your `Applications` folder.
2. Open **Terminal** and run:
   ```bash
   xattr -cr "/Applications/CodeMap Space.app"
   ```
3. Now you can open the app normally!
