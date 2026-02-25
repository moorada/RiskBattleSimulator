# 🎲 Risk Battle Simulator

A beautiful web application to simulate Risk board game battles with accurate dice mechanics and real-time battle visualization.

**[🎮 Play Live Demo](https://moorada.github.io/RiskBattleSimulator/)**

![Risk Battle Simulator](https://img.shields.io/badge/Risk-Battle%20Simulator-red)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

- **Authentic Risk Rules**: Implements official Risk battle mechanics
  - Attacker rolls up to 3 dice (must leave 1 army behind)
  - Defender rolls up to 2 dice
  - Ties favor the defender
- **Two Battle Modes**:
  - **Single Attack**: Execute one attack at a time for strategic planning
  - **Attack Until Death**: Auto-simulate until conquest or defeat
- **Detailed Battle Log**: See every dice roll and casualty in real-time
- **Beautiful UI**: Modern gradient design with military-themed icons
- **Responsive Design**: Works on desktop and mobile devices
- **No Installation Required**: Pure HTML/CSS/JS - just open and play!
- **Victory Conditions**: 
  - Attacker wins when defender reaches 0 armies
  - Defender wins when attacker can't attack (only 1 army left)

## 🎮 How to Use

1. Set the number of attacking armies (minimum 2)
2. Set the number of defending armies (minimum 1)
3. Choose your strategy:
   - Click **Attack!** for controlled, single attacks
   - Click **Attack Until Death!** to see the final outcome immediately
4. Watch the battle unfold in the battle log
5. Click **Reset** to start a new battle

## 🚀 Getting Started

### Option 1: Online (Recommended)

Simply visit the **[Live Demo](https://moorada.github.io/RiskBattleSimulator/)** and start playing!

### Option 2: Local Installation

1. Download or clone this repository:
```bash
git clone https://github.com/moorada/RiskBattleSimulator.git
```

2. Start a local server (PWA features require `http://`):
```bash
cd RiskBattleSimulator
python3 -m http.server 8080
```

3. Open `http://localhost:8080`

### Option 3: Deploy to GitHub Pages (HTTPS)

This repository includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`.

1. Push `main` to GitHub.
2. In GitHub: `Settings` → `Pages` → under **Build and deployment** set **Source** to `GitHub Actions`.
3. Re-run the latest workflow if needed from `Actions` → `Deploy To GitHub Pages`.
4. Open your deployed URL:
   - `https://<your-username>.github.io/RiskBattleSimulator/`

### Install As App (PWA)

Install from the HTTPS Pages URL:

- **Android (Chrome/Edge)**: menu `⋮` → `Install app`
- **iPhone (Safari)**: `Share` → `Add to Home Screen`

If you only see `Add to Home` in Chrome and it opens with browser bars, remove that shortcut and install from the real **Install app** prompt.

## 🎯 Game Rules

### Dice Mechanics

- **Attacker**: Rolls 1-3 dice (based on army count, must leave 1 army)
- **Defender**: Rolls 1-2 dice (based on army count)
- Dice are sorted in descending order
- Highest dice are compared pairwise
- **Ties favor the defender**

### Example Battle

**Attacker rolls**: 6, 4, 2  
**Defender rolls**: 5, 3

**Comparisons**:
- 6 vs 5 → Defender loses 1 army
- 4 vs 3 → Defender loses 1 army

**Result**: Defender loses 2 armies

## 🛠️ Tech Stack

- **HTML5** - Structure
- **Tailwind CSS** (CDN) - Styling
- **Vanilla JavaScript** - Game logic and interactivity


## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


⭐ **Star this repo if you find it useful!** ⭐

Made with ❤️ for Risk enthusiasts
