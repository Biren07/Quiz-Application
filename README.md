# Quiz App

This **Quiz App** is built with **Next.js** and **Tailwind CSS**, providing a dynamic and engaging quiz experience. The app features a variety of interactive elements such as real-time scoring, a timer for each question, answer validation, and detailed results upon completion. The user interface is fully responsive and the quiz data is loaded from JSON files.

## Features

### 1. **Subject Selection**
- Choose a subject from the home page.
- Questions are dynamically loaded from JSON files located in the `/public/data` folder for each subject.

### 2. **Timed Quiz**
- Each question has a countdown timer of **10 seconds**.
- If the timer runs out, the question is marked as unattempted.

### 3. **Answer Validation**
- Selected answers turn **green** if correct, **red** if incorrect, and the correct answer is highlighted in green for immediate feedback.

### 4. **Scoring System**
- Earn **4 points** for each correct answer, with the score displayed at the top throughout the quiz.

### 5. **Post-Quiz Results**
- **Detailed Results Page**: After completing the quiz, users receive a comprehensive performance breakdown:
  - Total Points
  - Points Earned
  - Correct Answers
  - Wrong Answers
  - Unattempted Questions
  - Percentage
  - Total Time Spent
  - Average Time Per Question
- The results page features icons and colors for improved readability, along with a celebratory **confetti** effect.

### 6. **Responsive Design**
- Fully responsive, ensuring seamless functionality across all devices, including mobile and desktop.

## Technologies Used

- **Next.js**: For server-side rendering and static site generation.
- **Tailwind CSS**: A utility-first CSS framework for styling.
- **React Icons**: For scalable icons.
- **Confetti**: For celebratory effects on the results page.
- **react-use**: For handling window sizes, particularly for the confetti effect.
- **JavaScript/ES6**: For component building and quiz logic.

## How to Run the Project

### 1. Clone the Repository
```bash
https://github.com/Biren07/Quiz-Application.git
```
### 3. Install Dependencies
```bash
npm install
```

### 4. Run the Development Server
```bash
npm run dev
```

## Future Improvements

- **Backend Integration**: To allow dynamic question loading, user authentication, and real-time leaderboard updates.
- **User Authentication**: Implement login and signup features to track user progress and performance.
- **Difficulty Levels**: Add multiple difficulty levels for each subject to enhance the quiz experience.
- **Question Bank Expansion**: Expand the quiz by adding more subjects and questions.

