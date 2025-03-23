# DuoAlly AI LoL Chatbot

## Overview

The **DuoAlly AI Chatbot** is an interactive rule-based chatbot assistant designed to help players in league of legends improve their gameplay by providing detailed information about champions, including:

- **Abilities**
- **Recommended item builds**
- **Rune setups**
- **Matchups and counters**
- **Role-specific tips**

With fuzzy matching for champion names and a contextual response system, this chatbot ensures a smooth user experience.
---

## Demo
Note: This demo includes many of the LoL chatbot version 1.0's limitations. For version 2.0, please go to https://github.com/DuoAlly/LoL-Chatbot-v2.

https://github.com/user-attachments/assets/d230bb15-1b0b-4f77-a1a7-2584de77a1db

---

## Features

- **Contextual Understanding**: Remembers the last mentioned champion for fluid conversations.
- **Detailed Champion Insights**: Provides specific advice for items, runes, abilities, and more.
- **Interactive User Experience**: Simulates a "typing effect" for responses, making it feel more engaging.
- **Fuzzy Name Matching**: Recognizes champion names even with slight typos.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/DuoAlly/LoL-Chatbot.git
   cd LoL-Chatbot
   ```
2. Run the chatbot:
   ```bash
   python chatbot.py
   ```

---

## Usage

1. Use these commands for specific information:
   - **Abilities**: `What are Ahri's abilities?`
   - **Items**: `Recommended items for Ahri`
   - **Runes**: `What runes should I take on Ahri?`
   - **Matchups**: `Who is Ahri strong against?`
   - **Tips**: `Tips for Ahri`

2. Exit the chatbot anytime by typing:
   ```text
   exit
   ```

---

## Example Interaction

```plaintext
╔══════════════════════════════════════════════╗
║           LoL Expert Bot v1.0                ║
╚══════════════════════════════════════════════╝

Ask me about any champion's:
• Abilities and combos
• Item builds
• Rune setups
• Matchups and counters
• Role-specific tips

Type 'help' for commands or 'exit' to quit.

[12:30:45] You: Tell me about Ahri
[12:30:45] Bot: 
Champion Overview - Ahri:
Role: Mid-lane Mage/Assassin
Tips: Ahri excels at poking and kiting. Use your Orb of Deception to poke, and Charm to catch enemies off-guard.

You can ask about Ahri's abilities, items, runes, or matchups!

[12:31:15] You: What are her abilities?
[12:31:15] Bot: 
Abilities for Ahri:
Passive: Essence Theft - Gains stacks of Essence Theft when hitting enemy champions with abilities
Q: Orb of Deception - Sends out and pulls back an orb, dealing magic damage
W: Fox-Fire - Releases fox-fires that target nearby enemies
E: Charm - Blows a kiss that damages and charms an enemy
R: Spirit Rush - Dashes and fires essence bolts at nearby enemies
```

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- Riot Games for creating **League of Legends**
