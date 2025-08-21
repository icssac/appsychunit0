# Psychology Unit 0 Review Hub

An interactive flashcard study app designed for psychology students to master Unit 0 terminology and concepts.

## Features

- **Flashcards**: Traditional flip-card study mode with shuffle and reset options
- **Matching Game**: Timed memory game to match terms with definitions
- **Multiple Choice Quiz**: Test knowledge with randomized quizzes
- **Study List**: Comprehensive view of all terms and definitions
- **CSV Import/Export**: Load custom term sets and export progress
- **Secure Login**: Protected access with authentication

## Login Credentials

- **Username**: `APPSYCH2025`
- **Password**: `IVANPAVLOV`

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/psychology-flashcard-app.git
cd psychology-flashcard-app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Usage

### Study Modes

1. **Flashcards**: Click cards to flip between terms and definitions
2. **Matching Game**: Match 8 pairs of terms and definitions as quickly as possible
3. **Quiz Mode**: Answer 10 multiple choice questions with instant feedback
4. **Study List**: Review all terms in a scrollable list format

### Data Management

- Upload CSV files with terms in column A and definitions in column B
- Export your current term set as a CSV file
- Data is automatically saved to local storage

## File Structure

```
psychology-flashcard-app/
├── public/
│   ├── index.html
│   └── Psych TA quizlets - Sheet1.csv
├── src/
│   ├── App.js
│   ├── index.js
│   └── index.css
├── package.json
└── README.md
```

## Technologies Used

- **React 18**: Frontend framework
- **Tailwind CSS**: Styling and responsive design
- **Lucide React**: Icon components
- **Papa Parse**: CSV file parsing
- **Local Storage**: Data persistence

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Built for psychology education
- Inspired by effective spaced repetition learning techniques
- Named after Ivan Pavlov, the famous psychologist