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

2. Open `index.html` in your web browser

That's it! No build process, no dependencies to install.

## 🌐 Deploy to GitHub Pages

1. Create a new repository on GitHub called `risk-battle-simulator`
2. Push your code:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/moorada/RiskBattleSimulator.git
git push -u origin main
```

3. Enable GitHub Pages:
   - Go to repository **Settings** → **Pages**
   - Under **Source**, select **main** branch
   - Click **Save**
   - Your site will be live at `https://moorada.github.io/RiskBattleSimulator/`

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