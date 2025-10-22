# 🧠 Muscle Legends Glitch Finder (v6)

A clean, dark-themed web tool that calculates **first glitch levels** in **Muscle Legends** for all rocks and rarities — across any **rebirth range**.  
It automatically detects glitch levels, displays results neatly in an accordion interface, and lets you **export bullet-point TXT reports** with bold rebirth headers.

---


# 🔗 Website
https://jujux1.github.io/Muscle-legend-glitch-calculator/


---

## ✨ Features

- 🔢 **Rebirth Range Scanning**  
  Input any **min and max rebirth**, and it automatically scans each rebirth’s first glitch levels.

- 🪨 **All Rocks Supported**  
  Includes Tiny Rock → Ancient Jungle, each with its unique XP multiplier.

- 🌟 **All Rarities**  
  Supports Basic, Advanced, Rare, Epic, and Unique rarities.

- 📋 **Bullet-Point TXT Export**  
  Exports a perfectly formatted `MuscleLegends_Glitch.txt` file:  
  - UTF-8 encoded (no weird `â€¢` characters)  
  - Uses clean bullet points and section headers like  
    ```
    === REBIRTH 3 ===
      • Frozen Rock (0.375)
        - EPIC: Level 7 (190 hits)
    ```

- 🧩 **Accordion UI**  
  Toggle each rock’s results open or closed for easy reading.

- 💾 **Offline Ready**  
  100% client-side — no servers, no API keys, no dependencies.

---

## 🚀 How to Use

1. **Open `index.html`** in any browser (works on mobile too).  
2. Enter your **Min Rebirth** and **Max Rebirth**.  
3. Click **“Scan Rebirth Range”**.  
4. Expand any rock to view glitch levels per rarity.  
5. Press **“Download TXT”** to save the report.

---

## 🧮 Formula Summary

Each glitch is calculated using:

XP per hit = (rebirth + 20) * rockMultiplier Total XP = cumulative sum of XP table per rarity

A glitch occurs when:

totalXP / xpPerHit ≈ integer

---

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | HTML5, CSS3, Vanilla JS |
| Fonts | Google Fonts (Poppins) |
| Encoding | UTF-8 via TextEncoder |
| Export | Blob + Auto download link |

---

## 📂 File Structure

📁 muscle-legends-glitch-finder/ ├── index.html       # Main app ├── README.md        # This file └── assets/          # (optional: icons, screenshots)

---

## 📸 Example Output

=== REBIRTH 5 === • Tiny Rock (0.025) - BASIC: Level 12 (345 hits) - ADVANCED: Level 10 (280 hits) • Frozen Rock (0.375) - RARE: Level 7 (195 hits)

---

## 🧑‍💻 Author

**Created by:** Dipesh Shrestha  
**Version:** v6  
**License:** MIT (Free to use, modify, and share)

---

## ❤️ Support

If you found this helpful:
- ⭐ Star the repo  
- 🐛 Report issues or suggestions  
- 📥 Share your TXT formats or UI improvements

> Built with passion, by a gamer for gamers 🎮
