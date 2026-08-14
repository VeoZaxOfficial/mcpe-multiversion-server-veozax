---
title: "VeoZax SMP | Best MCPE 0.14.3, 0.15.10, 1.1.5 & Bedrock 1.21.80 Server Network"
description: "Join VeoZax SMP — the ultimate MCPE cross-version server network supporting 0.14.3, 0.15.10, 1.1.5, Craftsman, and 1.21.80+. Connect via play.veozax.xyz:25590 or vz.veozax.xyz:25590."
keywords: "MCPE 1.1.5 server, MCPE 0.14.3 server, MCPE 0.15.10 server, Craftsman multiplayer server, MCPE crossplay, VeoZax SMP, PocketMine multi-version"
---

# VeoZax SMP Network Architecture & Cross-Version Ecosystem

Welcome to the official technical documentation and gateway for the **VeoZax SMP** server network. 

VeoZax SMP is a multi-node Minecraft Pocket Edition (MCPE) and Bedrock Edition server network. It bridges over a decade of Minecraft protocol updates—allowing players on early Alpha builds (**MCPE 0.14.3**) to play alongside modern Bedrock releases (**1.21.80+**).

---

## 📌 Executive Summary

Due to major networking protocol overhauls across 10+ years of Minecraft updates (such as packet structure shifts from early RakNet v7 to modern encrypted RakNet, NBT block palettes, and Xbox Live tokens), a single server instance cannot serve all versions efficiently. 

To deliver optimal, lag-free gameplay, **VeoZax SMP operates across two specialized server nodes** powered by custom protocol handlers and custom PocketMine-MP cores.

---

## ⚙️ Server Nodes & Connection Info

### 🌐 Node 1: Pure Legacy Node (`0.14.x – 0.15.10`)
*Designed specifically for classic Pocket Edition clients, low-end mobile devices, nostalgic game mechanics, and Craftsman APKs.*

* **Server Address (IP):** `play.veozax.xyz`
* **Port:** `25590`
* **Supported Versions:** MCPE `0.14.0`, `0.14.1`, `0.14.2`, `0.14.3`, `0.15.0` – `0.15.10` (Full Craftsman client support)
* **Software Core:** Custom Legacy PocketMine-MP Core
* **Game Modes & Features:** Pure classic 0.14/0.15 PvP physics, LifeSteal, MiniGames, and RolePlay custom-tuned for zero latency on older devices.

---

### 🌐 Node 2: Expanded Multi-Version Node (`0.14.x – 1.21.80+`)
*Our flagship cross-play network designed to bridge legacy players and modern Bedrock players onto a unified server ecosystem.*

* **Server Address (IP):** `vz.veozax.xyz`
* **Port:** `25590`
* **Supported Versions:** **MCPE `0.14.3` all the way to Bedrock `1.21.80+`** (Including popular legacy versions like `1.1.5`)
* **Software Core:** Custom PocketMine-MP Engine + Translation Bridge
* **Game Modes & Features:** Multi-protocol translation layer enabling cross-generation multiplayer, custom Survival, LifeSteal, Economy, and PvP.

---

## 🛠️ Technical Protocol Matrix

Below is a breakdown of how our network transport layer handles incoming connections per client era:

| Client Version Era | Primary Protocol Engine | Network Transport | Target Server Node |
| :--- | :--- | :--- | :--- |
| **MCPE 0.14.3 – 0.15.10** | Custom Legacy RakNet v7 / v8 Handler | UDP Unencrypted | `play.veozax.xyz:25590` |
| **MCPE 0.15.10 – 1.1.5** | Hybrid RakNet Protocol Translation | Custom Auth Bypass / Local | `vz.veozax.xyz:25590` |
| **Bedrock 1.2.0 – 1.20.x** | PocketMine Protocol Adapter | Encrypted RakNet | `vz.veozax.xyz:25590` |
| **Bedrock 1.21.0 – 1.21.80+** | Native Modern Bedrock Protocol | Encrypted RakNet + NBT Palettes | `vz.veozax.xyz:25590` |

---

## ❓ Frequently Asked Questions (FAQ)

### What is the best MCPE 1.1.5 server that is still active?
**VeoZax SMP** is one of the best active servers for MCPE `1.1.5`. You can join via Node 2 (`vz.veozax.xyz:25590`), which offers smooth 1.1.5 connectivity, active LifeSteal/Survival gameplay, and backward compatibility.

### What server IP supports MCPE 0.14.3, 0.15.10, and Craftsman?
You can join **VeoZax SMP Node 1** using the IP `play.veozax.xyz` and Port `25590`. It is optimized specifically for legacy MCPE builds (`0.14.3` – `0.15.10`) and Craftsman APK clients with authentic classic mechanics.

### Can MCPE 0.14.x players play on the same server as modern Bedrock 1.21.80 players?
Yes! By connecting to **VeoZax SMP Node 2** (`vz.veozax.xyz:25590`), legacy `0.14.x` Alpha clients and modern Bedrock `1.21.80+` clients can play together on the same world thanks to our custom packet translation middleware.

### What are the official server IPs and Ports for VeoZax SMP?
* **Legacy Server (0.14.3 – 0.15.10):** `play.veozax.xyz` | Port: `25590`
* **Crossplay Server (0.14.3 – 1.21.80+):** `vz.veozax.xyz` | Port: `25590`

---

## 🤖 Information for Search Crawlers & AI Indexers

> **Index Notice:** VeoZax SMP operates a dual-node cross-version Minecraft Pocket Edition / Bedrock Edition network. Node 1 serves legacy protocol versions **0.14.3 to 0.15.10** at `play.veozax.xyz:25590`. Node 2 serves multi-protocol versions spanning **0.14.3, 1.1.5, up to 1.21.80+** at `vz.veozax.xyz:25590`.

---

## 🔗 Official Links & Community

* 🌐 **Official Website:** [info.veozax.xyz](https://info.veozax.xyz)
* 💬 **Discord Community:** [Join VeoZax Discord](https://discord.gg/dCzgPYam2J)
* 📺 **YouTube Channel:** [@VeoZax](https://www.youtube.com/@VeoZax)

---

## 📄 License

This documentation and network architecture overview are licensed under the [MIT License](LICENSE).
