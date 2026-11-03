# Kupass

> *"Syntax is just a tool. The idea is the real power."*

**Kupass** (Aku - User - Pass) is a simple, offline-first credential generator. It runs entirely in your browser with no server, no tracking, and no external dependencies. 

Just open `index.html` and start generating.

## ✨ Features

- **Username Generator:** Create usernames with custom lengths, character pools, and unique character rules.
- **Password Generator:** Generate secure passwords with configurable complexity and character exclusions.
- **Pairs Generator:** Combine usernames and passwords into a single credential pair along with platform details (Name, Email, Phone).
- **Custom Username Option:** Already have an account? You can input a manual username or choose to exclude usernames entirely (e.g., for platforms that only use email).
- **Export & Print:** Copy results to clipboard, export as CSV/TXT, or print directly to PDF.

## 🔒 Privacy & Security

- **100% Offline:** All generation happens locally using `window.crypto.getRandomValues` (CSPRNG). No data is ever sent over the network.
- **No Credential Storage:** Generated usernames, passwords, and pairs live only in memory. **They vanish the moment you close the tab** — they are never saved to disk.
- **Safe by Design:** Inputs are sanitized, and exported CSV files are protected against spreadsheet formula injection.

## 💡 Using a Shared or Public Computer?

By default, Kupass saves your form inputs (platform names, emails, phone numbers) in your browser's local storage so you don't have to retype them next time. 

If you are using a public PC (like a library or internet cafe), **simply click the Power icon in the top right corner before closing the tab.** This instantly wipes all saved settings and form data from the device. Alternatively, you can use Incognito/Private Browsing mode.

On your personal phone or PC, you don't need to worry about this.

## 🛠️ Usage

Since Kupass is a single-file application, you can:
1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Or, host it directly via GitHub Pages.

---

## Why I Built This (Behind the Scenes)

*"I'm not a traditional programmer. I'm a visualizer. I believe that a strong idea and a clear vision shouldn't be silenced by a lack of coding syntax. Kupass started as a thought: 'Why are credential generators so clunky, full of ads, and require sending data to a server?'*

*I visualized a tool that was clean, offline-first, and straight to the point. I used modern tools to bring that vision to life into this single HTML file. This project is proof that if you can visualize it clearly, you can build it."*
