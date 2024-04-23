# Quiz Application

## Output

[Click here to view the Quiz Application](https://codingbysahil.github.io/SMITFirstHackathon/) <!-- Replace # with your actual output link -->

## Objective

The primary objective of this project is to develop a small quiz application using HTML, CSS, and JavaScript. This application allows students to:

- Input their personal details
- Create a quiz on a chosen topic
- Answer multiple-choice questions
- Receive marks based on correct answers

The total time allocated for the development of this application is 3 hours.

## Features

### 1. Student Details Form

- An HTML form to collect the following details:
  - Roll Number
  - Name
  - Batch
  - Section
- CSS styling for the form

### 2. Data Storage

- Upon submitting the student details form, the data is stored in Session Storage using JavaScript.

### 3. Quiz Page

- An HTML form with fields to input:
  - Heading for Quiz Application
  - Topic for the Quiz
  - Five multiple-choice questions
  - Each question has four radio button options, including one correct answer and three wrong answers
- CSS styling for the form

### 4. Quiz Evaluation

- Upon submitting the multiple-choice questions form, the selected answers are compared with predefined correct answers using JavaScript.
- Marks are awarded for correct answers, and the total marks are displayed.
- Marks are stored in Session Storage for display on the results page.

### 5. Results Page

- An HTML page to display:
  - Student's details
  - Quiz topic
  - Selected answers
  - Correct answers
  - Total marks
- CSS styling for the results page

## Execution

1. Open `index.html` in a web browser to input student details.
2. After entering the details, click on the submit button.
3. You will be redirected to the `quiz.html` page to answer the questions.
4. After answering all questions, click on the submit button.
5. You will be redirected to the `result.html` page to view the score and details.
