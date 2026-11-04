# Tenzies

A polished React implementation of the Tenzies dice game. Roll the dice, hold matching values, and try to get all ten dice on the same number.

## Features

- Roll ten dice at a time
- Hold and release individual dice between rolls
- Win detection when all dice are held and match
- Confetti celebration and accessible win announcement
- Responsive layout for desktop and mobile screens
- Keyboard-friendly focus states

## Tech stack

- React
- Vite
- JavaScript
- CSS
- `react-confetti`
- `nanoid`

## Getting started

### Prerequisites

- Node.js 18 or later
- npm

### Installation

```bash
npm install
```

### Run locally

```bash
npm run dev
```

Open the local URL shown by Vite in your browser.

### Create a production build

```bash
npm run build
```

### Preview the production build

```bash
npm run preview
```

## How to play

1. Select dice to hold them.
2. Roll the remaining dice.
3. Keep holding matching dice until all ten show the same value.
4. Select **New Game** to start over after winning.

## Project structure

```text
tenzies/
├── components/
│   └── Die.jsx
├── App.jsx
├── index.css
├── index.html
├── index.jsx
├── LICENSE
├── package.json
└── README.md
```

## License

This project is licensed under the [MIT License](./LICENSE).
