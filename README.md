# Magic Match - Memory Game

A fun and interactive memory card matching game built with React and Vite. Test your memory skills by matching pairs of magical items including helmets, potions, rings, scrolls, shields, and swords!

## 🎮 Game Features

- **Classic Memory Game**: Flip cards to find matching pairs
- **Magical Theme**: Fantasy-themed cards with RPG items
- **Turn Counter**: Track your performance with turn count
- **Responsive Design**: Play on desktop or mobile devices
- **Smooth Animations**: Enjoy fluid card flip animations
- **New Game Button**: Start fresh anytime

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/memory-game.git
   cd memory-game
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## 🎯 How to Play

1. Click on any card to flip it and reveal the magical item
2. Click on a second card to try to find its match
3. If the cards match, they stay flipped and are removed from play
4. If they don't match, both cards flip back after a short delay
5. Continue until all pairs are matched
6. Try to complete the game in as few turns as possible!

## 📁 Project Structure

```
memory-game/
├── public/
│   ├── img/
│   │   ├── cover.png          # Card back design
│   │   ├── helmet-1.png       # Game cards
│   │   ├── potion-1.png
│   │   ├── ring-1.png
│   │   ├── scroll-1.png
│   │   ├── shield-1.png
│   │   └── sword-1.png
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── SingleCard.jsx     # Individual card component
│   │   └── SingleCard.css     # Card styling
│   ├── App.jsx                # Main game logic
│   ├── App.css                # Main app styling
│   ├── main.jsx               # App entry point
│   └── index.css              # Global styles
├── package.json
└── vite.config.js
```

## 🛠️ Technologies Used

- **React 18** - UI library for building the game interface
- **Vite** - Fast build tool and development server
- **CSS3** - Styling with modern CSS features
- **ESLint** - Code linting for consistent code quality

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🎨 Customization

### Adding New Cards

1. Add new card images to `public/img/`
2. Update the `cardImages` array in `src/App.jsx`:
   ```javascript
   const cardImages = [
     // ... existing cards
     { src: "/img/your-new-card.png", matched: false },
   ];
   ```

### Styling Changes

- Modify `src/App.css` for main layout
- Update `src/components/SingleCard.css` for card appearance
- Adjust `src/index.css` for global styles

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built with React and Vite
- Card images designed for fantasy/RPG theme
- Inspired by classic memory matching games

---

**Enjoy the game! 🧙‍♂️✨**
