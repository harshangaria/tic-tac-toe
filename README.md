# 🎮 React Tic‑Tac‑Toe

A two-player Tic‑Tac‑Toe game built with **React** and deployed via **Netlify**.

## 🚀 Live Demo

Play the game live at: [https://ticctacc-toee.netlify.app/](https://ticctacc-toee.netlify.app/)

## 🧩 Features

- Choose custom **player names** (symbols **X** & **O**), editable inline  
- **Alternating turns** with active player highlighting  
- **Win or draw detection**, displayed at game end  
- **Reset (Rematch)** button to start over  
- **Move log** panel to track actions  
- Stateless UI components and centralized state logic in `App`

## 🏗️ Project Structure

```text
src/
  ├── components/
  │   ├── Player.jsx
  │   ├── GameBoard.jsx
  │   ├── Log.jsx
  │   └── GameOver.jsx
  ├── winning-combinations.js
  └── App.jsx
public/
  index.html
package.json
README.md
