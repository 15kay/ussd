# RSOS USSD Demo 📱

A browser-based USSD simulator for the **Rural Skills & Opportunities System (RSOS)**, built with pure HTML, CSS and JavaScript. No frameworks, no dependencies.

🔗 **Live Demo:** [https://15kay.github.io/ussd/index.html](https://15kay.github.io/ussd/index.html)

---

## What It Does

Simulates a USSD session (`*120#`) that connects job seekers and SMMEs to:

- **Graduate Portal** — Find jobs, explore career paths, enrol in training
- **SMME Portal** — Access funding, training programs, and find workers

---

## Features

- 📱 **Two display modes** — toggle between a clean modern UI and a retro Nokia frame
- ⌨️ **On-screen keypad** — click keys or type directly and press Enter
- 🔄 **Full session flow** — navigates menus, goes back, ends session
- 🕐 **Live clock** — real-time status bar clock
- 🖥️ **No frame mode** — bare UI perfect for embedding in a browser extension

---

## How To Use

1. Open the app in your browser
2. Type `*120#` in the input field and press **SEND** or **Enter**
3. Navigate menus by typing the option number (e.g. `1`, `2`, `0`)
4. Press `0` at any menu to go back
5. Use the **red ✕ button** to end the session
6. Toggle **Nokia Frame** in the top-right to switch UI modes

---

## Project Structure

```
ussd/
└── index.html      # Single-file app — all HTML, CSS and JS
```

---

## Run Locally

No build tools needed. Just open the file:

```bash
git clone https://github.com/15kay/ussd.git
cd ussd
# open index.html in your browser
```

Or with XAMPP:
```
Place in: c:\xampp\htdocs\USSD\phone\
Visit:    http://localhost/USSD/phone/index.html
```

---

## USSD Menu Tree

```
*120#
├── 1. Graduate Portal
│   ├── 1. Find Jobs        → Job matches + qualification check
│   ├── 2. Career Path      → Career path recommendations
│   ├── 3. Training         → Available training programs
│   └── 0. Back
├── 2. SMME Portal
│   ├── 1. Funding          → Grants and youth funds
│   ├── 2. Training         → Business skills training
│   ├── 3. Find Workers     → Browse available workers
│   └── 0. Back
└── 0. Exit
```

---

## Tech Stack

| Layer | Tech |
|-------|------|
| Markup | HTML5 |
| Styling | CSS3 (variables, grid, flexbox, animations) |
| Logic | Vanilla JavaScript |
| Fonts | Google Fonts — Inter, Share Tech Mono |
| Hosting | GitHub Pages |

---

## Contributing

Pull requests are welcome. For major changes, open an issue first.

---

## License

MIT © [15kay](https://github.com/15kay)
