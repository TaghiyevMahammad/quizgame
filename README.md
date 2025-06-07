# Quiz Game

This is a simple and interactive quiz game. The user can enter the starting and ending question numbers, as well as the number of questions to be tested, and play the quiz with randomly selected questions from that range.

---

## Features

- User inputs the start and end question numbers.
- Random selection of questions within the chosen range.
- Visual feedback indicating correct or incorrect answers with colors.
- Question status display (e.g., "Question 1 / 10").
- Final score shown at the end.
- Responsive and user-friendly design.

---

## File Structure

/project-root
│
├── index.html # Main HTML and JavaScript file for running the quiz
├── MM.txt # Text file containing the questions and answers


---

## MM.txt File Format

- Questions are numbered.
- Answers start with either "•" (bullet) or "√" (check mark).
- The correct answer is marked with "√".

Example:

What is the capital of the Republic of Azerbaijan?
• Baku
√ Baku
• Ganja
• Sumgait


---

## How to Use

1. Open `index.html` in a modern web browser.
2. Enter the start and end question numbers, and the number of questions for the quiz.
3. Click the **Start Quiz** button.
4. Select answers for each question and click the **Check** button to verify.
5. Click the **Next** button to proceed to the next question.
6. At the end, the total number of correct answers will be displayed.

---

## Technologies

- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API for loading questions

---

## Notes

- The `MM.txt` file should be loaded via a server or local server environment due to browser security restrictions.
- Fetch may not work properly when opening files via `file://` protocol directly.
- It is recommended to use a local server (e.g., VSCode Live Server, Python `http.server`) for testing.

---

## License

This project is open for educational and personal use.
