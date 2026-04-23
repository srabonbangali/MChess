# ♟ MChess — Play Chess on Telegram

**MChess** is a multiplayer chess bot for Telegram that lets you challenge anyone instantly — no app downloads, no account registration, no setup required.

---

## 🚀 How It Works

1. **Open the bot** — Start a chat with [@mchessbot](https://t.me/mchessbot) on Telegram or add it to any group.
2. **Create a game** — Type `/create` and the bot generates a unique game link.
3. **Share the link** — Send it to your opponent.
   - The first person to open the link plays as **White**.
   - The second person plays as **Black**.
4. **Play** — Make moves in any browser. The board updates live for both players.

---

## 🤖 Bot Commands

| Command | Description |
| :--- | :--- |
| `/start` | Welcome message. Introduces the bot and explains how to create a game. |
| `/create` | Generates a new unique game link. Share it with your opponent to begin playing. |
| `/help` | Shows the full command list and a quick guide on how MChessBot works. |
| **🔄 New Game** (inline button) | Tap it on any game message to instantly generate a fresh game without typing. |

---

## ✨ Features

- **Unique Game IDs** — Every game gets a cryptographically random 32-character ID. No two games are ever the same.
- **Instant Generation** — Game links are created in milliseconds. No waiting, no loading.
- **Works Anywhere** — The game link opens in any browser. No app needed for players or spectators.
- **Group Friendly** — Add MChessBot to any Telegram group. Anyone can challenge anyone with `/create`.
- **10-Minute Clock** — Each player starts with 10 minutes. The active timer glows to show whose turn it is.
- **Rematch in One Tap** — The "🔄 New Game" button creates a fresh match without leaving the Telegram chat.
- **Spectator Mode** — Any number of spectators can watch live. Great for group commentary and learning.
- **Full Chess Rules** — Castling, en passant, promotion, check and checkmate — all standard rules enforced.

---

## 👥 Roles & How They Are Assigned

Roles are auto-assigned by the order players open the link:

| Order | Role | Description |
| :--- | :--- | :--- |
| **1st** | ⚪ **White** | Makes the first move. |
| **2nd** | ⚫ **Black** | Responds to White's opening. |
| **3rd+** | 👁 **Spectator** | Watches the game live as it unfolds. |

---

## ❓ Frequently Asked Questions (FAQ)

**Do I need an account to play?**
> No. Just open the game link in any browser and you're in. The bot assigns your role automatically.

**Can I use this in a Telegram group?**
> Yes. Add @mchessbot to any group and anyone can type `/create` to start a game. The link is shared right in the group for others to join.

**What happens if a third person opens the link?**
> The first two people become the players (White and Black). Anyone after that automatically joins as a spectator and watches live.

**Is there a time limit per game?**
> Yes. Each player starts with 10 minutes. The clock only counts down on your turn. If time runs out, you lose on time.

**Can I play on mobile?**
> Absolutely. The chess board is fully responsive and works on any smartphone browser — no installation needed.

**What if my opponent doesn't open the link?**
> The game stays in a "waiting" state until a second player joins. You can always tap "🔄 New Game" to generate a fresh link and try again.

**Can I play against an AI?**
> Not yet — MChessBot is currently two-player only. AI opponent support is planned for a future update.

**Are games saved?**
> Active and completed games are stored in the database. PGN export and game history are planned for a future release.

---

## 🔗 Links

- **Telegram Bot:** [@mchessbot](https://t.me/mchessbot)
- **Website:** [srabon.net](https://srabon.net/mchess)

---

## 📄 License

© 2025 srabon.net — Built with ♟ & ☕
