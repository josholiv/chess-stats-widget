# Chess.com Stats Widget

A simple widget to display your (or anyone's) Chess.com stats!

![image](https://github.com/user-attachments/assets/1ba3b1a9-01b4-4c0d-8b78-c0ef5c377501)

## Features

- **Live fetch** from the [Chess.com Public API](https://www.chess.com/news/view/published-data-api) 
- Displays **ratings** across multiple time controls (Bullet, Blitz, Rapid, Daily)  
- Includes **Tactics** (AKA Puzzles) rating and **Total games played**  
- Clean card-style layout with color-coded backgrounds  
- 🖼Chess.com-chessboard-inspired **background** using a chessboard SVG  
- Built with [Preact](https://preactjs.com) and functional hooks

## 📦 Installation

```bash
git clone https://github.com/your-username/chess-stats-widget.git
cd chess-stats-widget
npm install
npm run dev
```
## 🔧 Configuration

Edit the following line in ChessStats.tsx to set your Chess.com username:

```
const username = 'MagnusCarlsen'; // change to your own Chess.com username
```
You can also replace the chessboard image by modifying:
```
const chessboard = '/chessboard.svg'; // path to your background SVG
```
## 🛠️ Customization

Each stat card uses the formatCard() helper. You can easily tweak:

    💬 Labels and emojis

    🎨 Background colors

    🔗 External links (e.g., info on game types)

## 📁 File Structure
```
📦 chess-stats-widget
├── public/
│   └── chessboard.svg        # Background image
├── src/
│   └── components/
│       └── ChessStats.tsx    # Main widget code
├── preview.png               # Preview screenshot
└── README.md
```

## 📜 License

MIT License © 2025 Josh Olivier

Pull requests and issues welcome!
Feel free to fork this project and integrate it into your own site or portfolio.

