# 🚨 Scope Creep Detector

> Compare original agreements with new client requests. Detect scope creep automatically. Protect your time and money.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Open Source](https://badgen.net/badge/Open%20Source/Yes/green)](https://github.com/yourusername/scope-creep-detector)
[![Made with](https://badgen.net/badge/Made%20with/Anthropic%20Claude/purple)](https://anthropic.com)

![Preview](https://via.placeholder.com/800x400/0A0A0A/EF4444?text=Scope+Creep+Detector+Preview)

## ✨ Features

- **🔍 Automatic Detection** — AI compares original vs. new requests
- **📊 Creep Score** — 0-100 meter showing severity
- **💰 Cost Calculator** — Auto-estimates additional charges
- **✉️ Copy-Paste Response** — Ready-to-send client messages
- **🎚️ Adjustable Sensitivity** — Strict, Balanced, or Lenient modes
- **🔒 100% Private** — Your data never leaves your browser
- **🎨 Cyberpunk UI** — Dark terminal aesthetic with radar scan effects

## 🚀 Live Demo

**[Try it now →](https://yourusername.github.io/scope-creep-detector)** (GitHub Pages)

Or run locally:

```bash
git clone https://github.com/yourusername/scope-creep-detector.git
cd scope-creep-detector
# Open index.html in your browser
```

## 🔑 Setup

1. **Get your free Anthropic API key** at [console.anthropic.com](https://console.anthropic.com/)
2. **Paste your original agreement** (proposal, contract, or scope)
3. **Paste the new client request** (email, message, or call notes)
4. **Click Analyze** — get a verdict with cost breakdown

## 📄 Output Includes

- ✅ **Verdict Badge** — SAFE / WARNING / CRITICAL
- ✅ **Creep Score** — Visual 0-100 meter
- ✅ **What's New** — Features not in original scope
- ✅ **What Changed** — Modified requirements
- ✅ **What's Safe** — Requests within original scope
- ✅ **Recommended Response** — Copy-paste message for client
- ✅ **Additional Cost** — Hour breakdown with totals

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **Tailwind CSS** — Utility-first styling
- **Vanilla JavaScript** — Zero dependencies
- **Anthropic Claude API** — AI-powered analysis

## 🎨 Customization

### Change default hourly rate
Edit the `value="75"` attribute in the hourly rate input.

### Adjust detection sensitivity
Choose between Strict, Balanced, or Lenient modes.

### Modify the AI personality
Edit the prompt in `detectCreep()` to change the tone.

## 📁 Project Structure

```
scope-creep-detector/
├── index.html      # Main application (single file)
├── README.md       # This file
├── LICENSE         # MIT License
└── .gitignore      # Git ignore rules
```

## 🌐 Deployment

### GitHub Pages (Free)
1. Fork this repo
2. Go to Settings → Pages → Source: Deploy from branch → main
3. Your site is live at `https://yourusername.github.io/scope-creep-detector`

### Netlify (Free)
1. Drag and drop the folder to [Netlify Drop](https://app.netlify.com/drop)
2. Get an instant HTTPS URL

### Vercel (Free)
```bash
npm i -g vercel
vercel --prod
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments

- Powered by [Anthropic Claude](https://anthropic.com)
- UI built with [Tailwind CSS](https://tailwindcss.com)
- Fonts by [Google Fonts](https://fonts.google.com)

---

<p align="center">Built with ❤️ for freelancers who value their time</p>
