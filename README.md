# Enhanced League of Legends Chatbot

![LoL](LoL.jpg)

## Overview

The **Enhanced League of Legends Chatbot** is an interactive assistant designed to help players improve their gameplay by providing detailed information about champions, including:

- **Abilities** and combos
- **Recommended item builds**
- **Rune setups**
- **Matchups and counters**
- **Role-specific tips**

With fuzzy matching for champion names and a contextual response system, this chatbot ensures a smooth user experience.

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
   git clone https://github.com/yourusername/lol-chatbot.git
   cd lol-chatbot
   ```
2. Install dependencies (if required):
   ```bash
   pip install -r requirements.txt
   ```
   *(No additional dependencies needed for the base code as it uses Python's standard library.)*

3. Run the chatbot:
   ```bash
   python chatbot.py
   ```

---

## Usage

1. Start the chatbot:
   ```bash
   python chatbot.py
   ```

2. Use these commands for specific information:
   - **Abilities**: `What are Ahri's abilities?`
   - **Items**: `Recommended items for Ahri`
   - **Runes**: `What runes should I take on Ahri?`
   - **Matchups**: `Who is Ahri strong against?`
   - **Tips**: `Tips for Ahri`

3. Exit the chatbot anytime by typing:
   ```text
   exit
   ```

---

## Example Interaction

```plaintext
╔══════════════════════════════════════════════╗
║       Enhanced LoL Expert Bot v2.0           ║
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

## Customization

### Adding New Champions
To add a new champion, update the `CHAMPION_DATA` dictionary in `chatbot.py` with the following structure:

```python
"champion_name": {
    "role": "Champion's primary role",
    "matchups": {
        "strong_against": ["List", "of", "champions"],
        "weak_against": ["List", "of", "champions"]
    },
    "recommended_items": ["List of recommended items"],
    "recommended_runes": ["List of recommended runes"],
    "tips": "Champion-specific tips",
    "abilities": {
        "passive": "Passive description",
        "Q": "Q ability description",
        "W": "W ability description",
        "E": "E ability description",
        "R": "Ultimate description"
    }
}
```

---

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add feature"`
4. Push to the branch: `git push origin feature-name`
5. Open a Pull Request

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- Riot Games for creating **League of Legends**
- The Python community for making development accessible and powerful
