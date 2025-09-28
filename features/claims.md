# 🏠 Claims & Land Protection

On **Gr1zzlyMC**, we use a **Simple Claim System** to let you claim land, protect your builds, and manage who can access your territory.  
This system makes it easy to keep your area safe, share it with friends, and customize how others interact with it.

---

## 🛡️ What Is a Claim?

A **claim** is a protected piece of land (usually a chunk) where only you — and the players you trust — can build, break, interact with blocks, or use containers.  
Claims prevent griefing and ensure your builds remain safe.

- ✅ Claim land to protect it  
- 🤝 Add or remove trusted members  
- 🔨 Manage permissions and settings via GUIs  
- 📜 Sell, transfer, or merge claims  
- ✨ View borders and maps of claimed chunks

---

## 📌 Quick Reference

| Action | Command |
|--------|--------|
| Claim land | `/claim` |
| Unclaim land | `/unclaim` |
| Add friend | `/claim add <player>` |
| Remove friend | `/claim remove <player>` |
| Teleport to claim | `/claim tp <claim-name>` |
| See chunk borders | `/claim see` |
| View claim map | `/claim map` |
| Rename claim | `/claim setname <old> <new>` |
| Sell claim | `/claim sell <claim> <price>` |

---

## 🧭 How to Create a Claim

1. Stand where you want to claim.  
2. Use the command below to claim the chunk you’re currently standing in:

/claim


- You can also add a **radius** to claim multiple chunks at once:

/claim <radius>


Example: `/claim 2` will claim a 5×5 area around you.

---

## ⚙️ Useful Commands

Here’s a complete list of the most useful player commands you can use to manage your claims.

---

### 🪧 Claim Management

| Command | Description |
|--------|-------------|
| `/claim [<radius>]` | Claim a chunk (or multiple chunks if radius is set). |
| `/unclaim [<claim-name|*>]` | Delete a claim. Use `*` to unclaim all. |
| `/claim main <claim-name>` | Open the main GUI for a claim. |
| `/claim settings [<claim-name>]` | Open the settings GUI. |
| `/claim chunks [<claim-name>]` | Open the chunks GUI. |
| `/claim setspawn` | Set the spawn point of your claim. |
| `/claim setname <old-name> <new-name>` | Rename a claim. |
| `/claim setdesc <claim-name> <description>` | Set a claim description. |
| `/claim merge <claim1> <claim2>` | Merge two claims into one. |
| `/claim addchunk <claim-name>` | Add your current chunk to a claim. |
| `/claim delchunk <claim-name> <world;x;z>` | Remove a chunk from a claim. |

---

### 👥 Members & Access

| Command | Description |
|--------|-------------|
| `/claim add [<*|claim-name>] <player>` | Add a player to your claim. Use `*` for all claims. |
| `/claim remove [<*|claim-name>] <player>` | Remove a player from your claim. |
| `/claim ban [<*|claim-name>] <player>` | Ban a player from your claim. |
| `/claim unban [<*|claim-name>] <player>` | Unban a player from your claim. |
| `/claim bans [<claim-name>]` | Open the bans GUI. |
| `/claim kick [<*|claim-name>] <player>` | Kick a player from your claim. |
| `/claim owner [<*|claim-name>] <player>` | Transfer ownership of a claim. |
| `/claim accept <player>` | Accept a claim invitation. |
| `/claim deny <player>` | Deny a claim invitation. |
| `/claim cancelinv <player>` | Cancel a sent invitation. |

---

### 🗺️ Navigation & Visualization

| Command | Description |
|--------|-------------|
| `/claim tp <claim-name>` | Teleport to one of your claims. |
| `/claim see [<player>]` | Show claim borders with particles. White = free, red = claimed, green = yours, purple = another player’s claims. |
| `/claim map` | View nearby claims in a chat-based map. |
| `/claim list` | View all your claims in a GUI. |
| `/claims` | Open the GUI with all claims on the server. |

---

### 💬 Chat & Communication

| Command | Description |
|--------|-------------|
| `/claim chat` | Toggle between public chat and claim-only chat. |

---

### 🏷️ Buying & Selling Claims

| Command | Description |
|--------|-------------|
| `/claim sell <claim-name> <price>` | Put one of your claims up for sale. |
| `/claim cancel <claim-name>` | Cancel a sale. |
| `/claim buy` | Buy the claim you’re currently standing in (if it’s for sale). |

---

## 💡 Tips for Players

- Use `/claim see` to quickly check if land is free or already claimed.  
- Use `/claim add` to share your land with friends and build together.  
- Always double-check claim names and ownership before merging or transferring.  
- You can use GUIs (`/claim main`, `/claim settings`, etc.) if you prefer menus over commands.

---


Protect your land, build without worry, and control who can enter your territory — all with the **SimpleClaimSystem**.
