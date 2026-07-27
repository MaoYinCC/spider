# Spider Solitaire: Same-Suit Edition (摆别扭)

An elegant, minimalist, and responsive browser-based Spider Solitaire game featuring pure Web Audio API-synthesized physical card sound effects and a sleek macOS-inspired frosted glass aesthetic.

---

## 🌟 Features / 核心特性

- **Pure Card Sound Effects / 纯正纸牌音效**: Built-in procedural Web Audio API sound engine that generates realistic card friction, snaps, table-slap thuds, and multi-card sliding collection sounds without external audio files.
- **Mac-Inspired Aesthetics / 苹果极简美学**: Frosted glass (`backdrop-filter`) panels, rich green felt poker table gradients, and smooth card hovering/selection feedback.
- **Bilingual Rule Modal / 双语游戏说明**: Clean, modal popup detailing rules and tips in both Chinese and English.
- **Responsive Layout / 自适应网格**: Seamless column and card scaling tailored for modern desktop and laptop browsers.

---

## 🎮 Game Rules & Instructions / 游戏规则与说明

"Spider Solitaire" (known here as **"Same-Suit Spider"** or **摆别扭**) is a classic puzzle game that tests both strategy and patience. Master these core rules to get started easily:

「摆别扭」（Spider Solitaire 的变体/单人纸牌游戏）是一款考验策略与耐心的经典益智游戏。即使是第一次接触，只要掌握以下核心规则，就能轻松上手：

### 1. Game Objective / 游戏目标
* **English:** Arrange and clear a shuffled deck of 52 cards into sequential order by suit from A to K (A, 2, 3...J, Q, K), and finally collect and eliminate them all from the table. Clear all cards from the table to win.
* **中文：** 将一副打乱的扑克牌（52张）全部按同花色从 A 到 K（A、2、3...J、Q、K）的顺序顺连整理，并最终从桌面全部回收消除。当桌面所有牌都被收完时，即告通关胜利。

### 2. Layout / 牌面布局
* **English:** 
  * **Play Area:** At the start, cards are dealt into 7 vertical columns. The bottom card of each column is face-up; covered cards above are face-down and temporarily unplayable.
  * **Suits & Colors:** Uses all 4 suits (Spades ♠, Clubs ♣, Hearts ♥, Diamonds ♦). Hearts and Diamonds are red, while Spades and Clubs are black, marked with high-contrast large fonts.
* **中文：**
  * **游戏区域：** 开局时，牌会被分发到 7 个纵向列中。每一列底部的牌是明牌（正面朝上），上方压着的牌是暗牌（背面朝上）。
  * **颜色与花色：** 游戏使用全部四种花色（黑桃 ♠、梅花 ♣、红桃 ♥、方片 ♦），红与黑分明，并有高对比度的大字标示。

### 3. Core Mechanics & Movement Rules / 核心操作与移动规则
* **English:**
  * **Single Card Move:** A face-up card can be moved onto a card of the same suit that is 1 rank higher (e.g., placing Heart 8 onto Heart 9).
  * **Sequential Group Move:** Properly sequenced same-suit card groups within a column can be selected and dragged together.
  * **Empty Column Strategy:** Only a King (K) or a sequence starting with K can fill an empty column.
  * **Revealing Hidden Cards:** When the bottom face-up card of a column is moved away, any hidden card above it automatically flips face-up.
* **中文：**
  * **单张移动：** 点数小 1 且同花色的明牌，可移动到大 1 的同花色牌下方（例如：红桃 8 可叠放在红桃 9 下方）。
  * **多张连牌移动：** 同列中已排好序的同花色连牌组可整体拖动。
  * **利用空列（国王入驻）：** 空列仅允许 K（国王）或以 K 开头的合法连牌组入驻。
  * **翻开暗牌：** 明牌移走后，其上方的暗牌会自动翻开。

### 4. Auto-Collection / 自动回收机制
* **English:** When a complete sequence from A to K of the same suit forms at the bottom of a column, the system automatically collects and clears it, flipping any hidden cards above it.
* **中文：** 当某列底部凑齐从 A 到 K（同花色）的完整序列时，系统自动回收并消除，同时自动翻开上方暗牌。

### 5. Beginner Tips / 新手入门建议
* **English:**
  * **Prioritize Hidden Cards:** Focus on moving face-up cards to reveal and flip hidden ones.
  * **Stick to Same-Suit Builds:** Keeping same-suit cards together maintains group movability.
  * **Guard Empty Columns:** Empty columns are precious for maneuvering; don't waste them on small cards—save them for Kings!
* **中文：**
  * **优先翻开暗牌：** 尽量通过移动明牌去解锁并翻开被压住的暗牌。
  * **善用同花色接龙：** 尽量把相同花色的牌往一起靠，避免交错导致无法整体移动。
  * **谨慎使用空列：** 空列非常珍贵，切勿轻易用小牌填满，留给 K（国王）更有战略空间。

---

## 🚀 Quick Start / 快速开始

1. Clone or download this repository.
2. Open `index.html` directly in any modern web browser (Chrome, Safari, Edge, Firefox).
3. Click **"游戏说明"** (Rules) to read details, or click **"音效: 开"** (Sound: ON) to toggle the procedural card audio.

---

## 📄 License / 许可证

This project is open-source and available under the [MIT License](LICENSE).
