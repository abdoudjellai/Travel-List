# Travel List

A simple and intuitive React application for managing your packing checklist before traveling.

## Features

- ✅ Add items to your packing list
- 📝 Edit or delete items from your list
- ✔️ Mark items as packed/unpacked
- 📊 View packing statistics (percentage packed)
- 🗑️ Clear entire packing list
- 💾 Clean and responsive UI

## Project Structure

```
src/
├── components/
│   ├── App.js           # Main application component
│   ├── Form.js          # Form to add new items
│   ├── Item.js          # Individual packing item component
│   ├── Logo.js          # Logo component
│   ├── PackingList.js   # List of packing items
│   └── Stats.js         # Statistics display
├── index.js             # Entry point
└── index.css            # Global styles
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository

```bash
git clone <repository-url>
cd travel-list
```

2. Install dependencies

```bash
npm install
```

3. Start the development server

```bash
npm start
```

The app will open at `http://localhost:3000` in your browser.

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Runs the test suite
- `npm eject` - Ejects from Create React App (irreversible)

## Usage

1. **Add Items**: Enter an item name and quantity in the form and click "Add"
2. **Mark as Packed**: Click the checkbox next to an item to mark it as packed
3. **Delete Items**: Click the delete button (❌) to remove an item
4. **View Statistics**: See the total number of items and percentage packed at the bottom
5. **Clear List**: Use the "Clear" button to remove all items at once

## Technologies Used

- **React** 18.2.0
- **React DOM** 18.2.0
- **React Scripts** 5.0.1
- **Testing Library** for component testing

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is part of the Ultimate React Course.

## Author

Created as part of the Ultimate React Course learning exercises.
