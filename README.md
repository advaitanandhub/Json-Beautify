# 🧹 JSON Beautifier

A fast, lightweight, browser-based JSON formatter. No server. No tracking. Your data never leaves your device.

> Paste your raw JSON, get clean and readable output instantly — all inside your browser, with zero data sent anywhere.

---

## 🚀 Features

- **Beautify** — Format raw JSON with proper indentation
- **Minify** — Strip whitespace for compact output
- **Copy Output** — One-click copy to clipboard
- **Download** — Save output as a `.json` file
- **Auto-format** — Instantly formats as you type
- **Dark / Light Mode** — Persistent theme toggle
- **Error Feedback** — Clear messages for invalid JSON

---

## ⚠️ Why Not Use a Public Website?

Many developers paste JSON into public online tools without thinking twice. This is a serious security risk.

**What you could be exposing:**
- 🔑 API keys and secret tokens
- 🗄️ Database credentials and connection strings
- 👤 Personally Identifiable Information (PII)
- 💳 Payment data and financial records
- 🔐 Auth tokens, JWTs, session data
- 🏗️ Internal service URLs and infrastructure details

**Public tools can:**
- Log every JSON payload you submit
- Store it in server-side databases
- Expose it via search engine indexing
- Share it with third-party analytics services
- Be vulnerable to data breaches

> 💡 A single accidental paste of a production config or JWT has caused real-world data breaches and credential leaks.

**This tool is different** — everything runs in your browser via plain JavaScript. Nothing is ever transmitted, logged, or stored anywhere outside your own device.

---

## 🛠️ Usage

1. Open `index.html` in any modern browser
2. Paste your JSON into the **left panel**
3. The output appears instantly in the **right panel**
4. Use the buttons to **Beautify**, **Minify**, **Copy**, or **Download**

No install. No dependencies. No internet connection required after loading.

---

## 📁 Project Structure

```
json-beautifier/
└── index.html    # Everything in one self-contained file
```

---

## 🌐 Browser Support

Works in all modern browsers — Chrome, Firefox, Safari, and Edge.

---

## 📄 License

MIT — free to use, modify, and distribute.
