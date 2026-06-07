# 🐍 Daily Python Quiz

Master Python one question at a time with this interactive daily quiz application!

## ✨ Features

- 📊 **25+ Python Questions** - Data types, OOP, functions, decorators, and more
- 🔥 **Streak Tracking** - Build your learning streak day by day
- 📈 **Progress Tracking** - Monitor your accuracy and total scores
- 💾 **LocalStorage** - All data saved locally in your browser
- 🎨 **Beautiful UI** - Dark theme with Python colors (Blue & Yellow)
- 📱 **Fully Responsive** - Works on desktop, tablet, and mobile
- ⚡ **Zero Dependencies** - Pure HTML, CSS, and JavaScript
- 🚀 **Offline Ready** - Works completely offline

## 🎯 Topics Covered

- Data Types (Lists, Tuples, Dictionaries, Sets)
- String Operations
- Operators & Operators
- Object-Oriented Programming (OOP)
- Functions & Lambda
- Decorators
- Generators & Yield
- List/Dictionary Comprehensions
- Built-in Functions
- Advanced Concepts & GIL

## 🚀 How to Use

1. Download the `index.html` file
2. Open in any modern web browser
3. Take the daily quiz
4. Your progress is saved automatically in LocalStorage
5. Come back tomorrow for new questions!

## 💾 Features

### Daily Quiz System
- One quiz per day (resets at midnight)
- 10 random questions selected daily from a pool of 25+
- Difficulty levels: Beginner, Intermediate, Advanced

### Progress Tracking
- **Current Streak**: Track consecutive days of quizzes
- **Total Score**: Cumulative points across all quizzes
- **Accuracy %**: Your overall performance percentage
- **Quiz History**: Last 20 completed quizzes with dates

### User Experience
- ⏱️ Timer for each question
- 📖 Detailed explanations after answers
- 🎨 Color-coded difficulty badges
- 🔄 Skip question option
- 💡 Visual feedback (green for correct, red for incorrect)

## 📋 Question Difficulty

- **Beginner**: Basic syntax, data types, built-in functions
- **Intermediate**: OOP concepts, list comprehensions, common libraries
- **Advanced**: Decorators, generators, GIL, memory management

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS variables for theming)
- Vanilla JavaScript (no dependencies)
- Browser LocalStorage API

## 📦 LocalStorage Data Structure

```javascript
{
  streak: number,
  totalScore: number,
  quizzesTaken: number,
  totalCorrect: number,
  totalAnswered: number,
  completedDates: array,
  history: array,
  lastCompletedDate: string
}
```

## 🎮 How Questions Work

- Questions are seeded by date, so all users get the same questions on the same day
- 10 questions are selected from a pool of 25+ Python questions
- Each question includes an explanation to help you learn
- Your answers are evaluated immediately with visual feedback

## 📊 Statistics Tracked

1. **Streak** - Consecutive days of quiz completion (resets if missed a day)
2. **Total Score** - Sum of all correct answers across all quizzes
3. **Accuracy** - Percentage of questions answered correctly
4. **Quizzes Taken** - Total number of quizzes completed
5. **Complete History** - Last 20 quizzes with dates and scores

## 🔧 Customization

You can easily customize:
- Colors (modify CSS variables in `:root`)
- Number of questions per quiz (change `totalQuestions`)
- Add/remove questions (edit `pythonQuestions` array)
- Question pool size

## 🌐 Browser Compatibility

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Opera ✅
- Mobile browsers ✅

## 💡 Tips

- Use **not in Private/Incognito mode** for LocalStorage to work
- Bookmark the page for quick access
- Share with friends - each browser has separate stats
- Clear history anytime using the "Clear History" button

## 📈 Future Enhancements

- [ ] Cloud sync for progress across devices
- [ ] Leaderboard system
- [ ] Community challenges
- [ ] More Python topics
- [ ] Dark/Light theme toggle
- [ ] Export progress as PDF

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Found a bug or have suggestions?
- Open an issue
- Submit a pull request
- Share your ideas!

## 👨‍💻 Author

Created with ❤️ by [Your Name]

## ⭐ If you found this helpful, please give it a star!

---

**Happy Learning! Master Python one day at a time! 🐍**
