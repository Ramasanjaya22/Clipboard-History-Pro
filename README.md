# 📋 Clipboard History Pro

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Chrome Web Store](https://img.shields.io/chrome-web-store/v/{{your-extension-id}})

A Chrome extension for managing clipboard history with search and snippet template features.

🌐 **Demo**: [Live Demo] 
📦 **Chrome Web Store**: [Coming Soon]

## 🚀 Features
- 24-hour clipboard history
- Real-time text search
- 3 free snippet templates
- Format cleaning (remove text styling)
- Basic data export (JSON)

## 🛠️ Installation
1. Clone repo:

```bash
git clone https://github.com/Ramasanjaya22/clipboard-history-pro.git
```

2. In Chrome:
   - Navigate to `chrome://extensions/`
   - Enable "Developer mode"
   - Click "Load unpacked"
   - Select the `dist/` folder

## 🧑💻 Development Setup
**Prerequisites**:
- Node.js 18+
- Latest Chrome browser
- Git

**Setup**:
```bash
# 1. Clone repository
git clone https://github.com/Ramasanjaya22/clipboard-history-pro.git
cd clipboard-history-pro

# 2. Install dependencies
npm install

# 3. Build development version
npm run dev

# 4. Load into Chrome
# - Go to chrome://extensions/
# - Click "Load unpacked"
# - Select 'dist' folder
```

## 🧩 Tech Stack
![Tech Stack](https://skillicons.dev/icons?i=react,typescript,postgresql,firebase,git)

**Frontend**:
- React 18 + TypeScript
- Dexie.js (IndexedDB wrapper)
- Material UI

**Backend** (Optional for MVP):
- PostgreSQL (Sync)
- Firebase Authentication

## 📂 Repository Structure
```bash
📦clipboard-history-pro
├── 📂public
├── 📂src
│   ├── 📂components   # React components
│   ├── 📂db           # IndexedDB setup
│   ├── 📂types        # TypeScript types
│   └── background.ts  # Service worker
├── manifest.json
└── package.json
```

## 🛣️ Roadmap
**Phase 1 - MVP (2 Weeks)**
- [ ] Basic clipboard history
- [ ] Text search functionality
- [ ] Snippet templates
- [ ] Basic settings page

**Phase 2 - Pro Features (1 Week)**
- [ ] Paywall integration
- [ ] Advanced search filters
- [ ] Auto-format cleaning

**Phase 3 - Cloud Sync (1 Week)**
- [ ] PostgreSQL integration
- [ ] Conflict resolution
- [ ] Multi-device sync

## 🤝 Contributing
1. Fork the project
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

**Guidelines**:
- Use TypeScript for all new code
- Follow [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- Test on minimum 2 latest Chrome versions

## 📄 License
MIT © 2025 [Ramasanjaya]. See [LICENSE](LICENSE) for details.

---

To start contributing:
1. Open an [issue](https://github.com/Ramasanjaya22/clipboard-history-pro/issues)
2. Check [project board](https://github.com/Ramasanjaya22/clipboard-history-pro/projects/1) for progress
3. Explore [good first issues](https://github.com/Ramasanjaya22/clipboard-history-pro/contribute)

---

Need technical documentation for a specific feature? Want to see implementation examples? Let me know! 😊
