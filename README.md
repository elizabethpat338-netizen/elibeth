elibeth/
├── public/
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── GameBoard.jsx       (Multiplayer game logic)
│   │   ├── MainMenu.jsx        (Player setup)
│   │   ├── QuestionCard.jsx    (Q&A with timer)
│   │   ├── PlayerStats.jsx     (Player display)
│   │   └── Leaderboard.jsx     (Firebase leaderboard)
│   ├── data/
│   │   ├── questions.js        (27 trigonometry questions)
│   │   └── board.js            (10-tile board config)
│   ├── utils/
│   │   ├── soundManager.js     (Sound effects)
│   │   └── timerUtils.js       (Question timers)
│   ├── App.jsx
│   ├── store.js                (Zustand state)
│   ├── firebase.js             (Firebase config)
│   ├── index.js
│   └── index.css               (Tailwind + animations)
├── .github/workflows/
│   └── deploy.yml              (Auto-deploy to GitHub Pages)
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── .env.example
├── .gitignore
└── README.md                   (Comprehensive documentation)
