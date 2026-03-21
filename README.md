# PVT Chat

**Self-hosted private chat that runs entirely on your own machine — no cloud, no tracking, no third parties.**

PVT Chat is a secure, encrypted messaging app you install and run on your own computer. Your conversations never leave your machine. No subscriptions, no surveillance, no server bills.

---

## Downloads

Go to the [Releases page](https://github.com/sathish17110/pvtchat/releases) and download the installer for your platform:

| Platform | File |
|----------|------|
| 🪟 Windows | `PVTChat-Setup-*.exe` |
| 🍎 macOS | `PVTChat-*.dmg` |
| 🐧 Linux (Fedora/RHEL) | `PVTChat-*.rpm` |
| 🐧 Linux (Ubuntu/Debian) | `PVTChat-*.deb` |
| 🐧 Linux (Portable) | `PVTChat-*.tar.gz` |

---

## Features

- 💬 Group and private messaging
- 🔒 Fully self-hosted — your data stays on your machine
- 👥 Up to 5 users on the free tier
- 🌐 Optional ngrok tunnel for remote access (requires free ngrok account)
- 🛡️ Admin controls and user management
- 🌙 Dark mode

---

## Getting Started

### Windows
1. Download `PVTChat-Setup-*.exe`
2. Run the installer
3. Launch PVT Chat from the Start Menu
4. Create your admin account on first run

### macOS
1. Download `PVTChat-*.dmg`
2. Open the DMG and drag PVT Chat to Applications
3. **Important:** Because PVT Chat is not yet code-signed with an Apple certificate, you need to run this command in Terminal before opening it:
   ```bash
   xattr -cr /Applications/PVTChat.app
   ```
4. Launch PVT Chat from Applications
5. Create your admin account on first run

### Linux
1. Download the `.deb` or `.rpm` package for your distro
2. Install it with your package manager
3. Launch PVT Chat and create your admin account on first run

---

## License Tiers

| Tier | Users | Price |
|------|-------|-------|
| Free | 5 | Free forever |
| Tier 1 | 20 | Coming soon |
| Tier 2 | 50 | Coming soon |
| Tier 3 | 100 | Coming soon |

Paid tiers coming soon. Activate your license in **Admin Settings → 🔑 License**.

---

## Remote Access (Optional)

PVT Chat includes built-in ngrok tunnel support so you can access your chat from anywhere. Enable it in **Admin Settings → 🌐 Tunnel** (requires a free [ngrok](https://ngrok.com) account).

---

## License

Proprietary. See [LICENSE](LICENSE) for details. Free tier is available for personal, non-commercial self-hosted use.

---

## Support

📧 [sathish@orthomail.us](mailto:sathish@orthomail.us)
