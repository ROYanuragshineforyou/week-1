 This Python code is designed to create a mini multiple-choice quiz. It leverages lists to hold the questions, options, and correct answers. Here's a brief rundown:

Data Setup:
questions: Holds the questions as strings.
options: Contains tuples for each question, with four choices (A, B, C, D) as strings.
answers: Stores the correct answer for each question as a single character string.
guesses: Keeps track of the user's guesses.
score: Tracks the number of correct answers.
question_num: Acts as an index to iterate through the questions, options, and answers.

Quiz Execution:
It iterates through each question in questions.
For each question, it displays the question and its options, then prompts the user to input their choice (A, B, C, or D).
It compares the user's input to the correct answer (answers) and updates the score accordingly.
After all questions are answered, it displays the results, showing the correct answers, user guesses, and the final score as a percentage.

Results Display:
It prints the correct answers and the user's guesses for each question.
Finally, it calculates and displays the user's overall score as a percentage.
