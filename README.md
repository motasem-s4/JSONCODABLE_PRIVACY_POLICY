# Json Codable

Json Codable is a lightweight native macOS app that converts JSON into clean, type-safe Swift `Codable` models.

Paste JSON, tweak a few options, and get ready-to-use Swift code that fits right into your iOS/macOS projects.

---

## ✨ Features

- 🚀 **Instant Swift Codable models**
  - Generate `struct` or `final class` models
  - Automatic `CodingKeys` with camelCase property names
- 🧠 **Smart type inference**
  - Infers `Int`, `Double`, `Bool`, nested objects, arrays
  - Handles mixed-type arrays by falling back to `[Any]`
- 🎨 **Syntax highlighting**
  - Xcode-like colors for Swift output (keywords, strings, types, comments)
  - Types after `:` (e.g. `: Codable`, `: Int`) highlighted in a separate color
- 📥 **Import JSON files**
  - Import `.json` (or `.txt`) files via a native macOS open panel
  - Content fills the JSON editor with line numbers
- 📜 **JSON editor with line numbers**
  - Line-numbered gutter (like Xcode)
  - Smart quote replacement so “fancy quotes” don’t break JSON
- 📚 **History & search**
  - Save JSON snippets to history
  - Quickly search and restore old snippets
- 💾 **Export-ready Swift**
  - Copy generated code to the clipboard
  - Export as `.swift` using a native save panel
- 🧭 **Mac-like UI**
  - Split view: JSON input on the left, Swift output on the right
  - Sidebar toggle button (navigator-style) just like Xcode
  - “Generate” blink effect on Swift output border for successful generation

---

## 🖥 Requirements

- macOS Sonoma (or newer)  
- Apple Silicon recommended (works on Intel if you build from source)

---

## 📦 Installation

> 🚧 Distribution is up to you – adjust this section to match how you ship (DMG, notarized zip, etc.).

### Option 1 – Download build

- Download the latest release from the **Releases** page.
- Drag `Json Codable.app` into your `/Applications` folder.
- Open the app (you may need to allow it under **System Settings → Privacy & Security** if not notarized yet).

### Option 2 – Build from source

1. Clone the repo:

   ```bash
   git clone https://github.com/<your-username>/json-codable.git
   cd json-codable
