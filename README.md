# Discord Account Generator GUI (Go + Fyne)

A Discord account generator with a modern graphical user interface built using Go and the [Fyne](https://fyne.io/) GUI toolkit.  
It simulates creating Discord accounts with realistic usernames, emails, passwords, proxies, and manages token states like unlocked, locked, and spammer.

---

## ⚙️ Features

- **Generate Discord accounts** with:
  - Realistic usernames from a curated list + random suffix
  - Randomly generated emails with common domains
  - Secure randomized passwords
  - Random user agents to mimic real browsers
  - Optional proxy support for requests
- **Account status detection:** unlocked, locked, spammer tokens
- **Token unlocking simulation** by mimicking user actions (profile update, presence change, etc.)
- **Profile customization:** set profile picture, banner, apply for Hypesquad (simulated)
- **Account management:** save and load accounts from file
- **Statistics display:** live count of unlocked, locked, and spammer accounts
- **Graphical interface:**
  - Generate single accounts on demand
  - Placeholder UI for batch generation
  - Progress bar and status updates
  - Scrollable account list with status labels
  - Save/Load buttons for account persistence

---

## 🚀 Getting Started

### Prerequisites

- Go 1.18 or newer
- Internet access (to interact with Discord API endpoints)
- Recommended: Configure proxies if you want to route requests

### Installation

```bash
git clone [github.com/pukarplayz/Discord-Token-Generator-2025](https://github.com/pukarplayz/Discord-Token-Generator-2025).git
cd discord-account-generator
go get fyne.io/fyne/v2
go build -o discord-account-generator main.go
