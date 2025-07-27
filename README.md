# San Laguna RPG - Character Sheet

A beautiful, responsive character sheet for the San Laguna RPG system.

## Features

- ✨ Modern, noir-inspired design
- 📱 Fully responsive (works on mobile and desktop)
- 💾 Auto-save functionality (localStorage)
- 📥 Export/Import character data as JSON
- 🎲 Built-in combat mechanics display
- 🔧 Dynamic HP calculation based on descriptors

## How to Use

1. **Online**: Visit the live version at [https://paulodcsc.github.io/sanlagunasheet/](https://paulodcsc.github.io/sanlagunasheet/)
2. **Local**: Download `sheet.html` and open it in any modern web browser

## Character Creation

1. Enter your character's name
2. Fill in 4-6 descriptors that define your character
3. Add any "tough" descriptors to automatically calculate HP
4. List your equipment and weapons
5. Add background notes and story details

## Game Mechanics

- **Base HP**: 10 + 2 per tough descriptor
- **Tests**: Roll 1d6 (6="Yes, and..." | 5-4="Yes..." | 3-2="Yes, but..." | 1="No, and...")
- **Combat**: 1d6 to hit (4-6 = success, 1-3 = miss)
- **Relevant Descriptor**: Roll 2d6, take higher
- **Problematic Descriptor**: Roll 2d6, take lower

## Technical Details

- Pure HTML/CSS/JavaScript (no dependencies)
- Uses localStorage for auto-save
- Responsive design with CSS Grid
- Custom fonts from Google Fonts

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Feel free to submit issues and enhancement requests!
