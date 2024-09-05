<h1>
  <span class="headline">Python Fundamentals Review Lab</span>
  <span class="subhead">Exercise</span>
</h1>

In this lab, you will use the fundamental Python skills we've learned to create a simple, interactive terminal application. You can choose to work on the lab individually or with your classmates, but each person must turn in their own work.

## Application Options

Choose one of the following for your lab:

| Application                                | Problem Statement                                                                                                                                                                                                                                                                                                                                                          |
| ------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Option No. 1: Personal Library Manager** | Create a simple personal library management application in the terminal that allows users to catalog their books and write brief reviews. Data can be stored either in a .csv file for easy retrieval and organization or in a local object/dictionary for in-memory management.                                                                                           |
| **Option No. 2: Study Guide App**          | Create a terminal-based application that allows users to generate and manage a set of review questions. This tool will help users efficiently prepare for exams or study sessions by providing a structured way to review material. Data can be stored either in a .csv file for easy retrieval and organization or in a local object/dictionary for in-memory management. |

## Deliverables

No matter what project you choose, you will submit a Jupyter Notebook containing:

- A Python application that accepts user input to interact with users in the terminal.

## Specific Requirements for Each Application:

### Personal Library Manager Lab

**Objective**:

Develop a straightforward personal library management application that operates entirely within the terminal. This application will enable users to catalog their books and write brief reviews directly from the command line. Data can be managed using a `.csv` file for persistent storage or a local object/dictionary for in-memory management. Through this project, you'll practice using Python, handling user input, and managing data.

**Requirements**:

Your personal library manager should allow users to:

1. **Main Menu**:

   - When the application starts, display a menu with the following options:

     - **Add a New Book**: Users can add a new book to their library.

     - **View All Books**: Display a list of all books in the library.

     - **Write a Review**: Add a review for a specific book.

2. **Add a New Book**:

   - Collect the following information from the user:

     - **Title**: The title of the book.

     - **Author**: The author of the book.

     - Example:

       ```plaintext
       Title: The Alchemist
       Author: Paulo Coelho
       ```

3. **View All Books**:

   - Print a list of all books in the library, including the title and author.

   - Example:

     ```plaintext
     1. The Alchemist by Paulo Coelho
     2. The Little Prince by Antoine de Saint-Exupéry
     ```

4. **Write a Review**:

   - Users can write a short review for a book in their library.

   - Display the review alongside the book details when viewing all books.

   - Example:

     ```plaintext
     Title: The Alchemist
     Review: "A magical story about following your dreams."
     ```

**Technical Requirements**:

- Store all book details in a `.csv` file.

- Store all reviews in a separate `.csv` file.

- Load existing data from the `.csv` files when the application starts.

**Stretch Goals**:

- **Basic Search**: Allow users to search for books by title or author.

### Study Guide App Lab

**Objective**:

Develop a straightforward study review application that runs in the terminal, allowing users to create and manage a set of review questions to aid in exam preparation. Users will have the option to store data in a `.csv` file for persistent storage or in a local object/dictionary for in-memory use. This lab will enhance your Python skills and introduce you to handling files and user input through a command-line interface.

**Requirements**:

Your study review app should allow users to:

1. **Main Menu**:

   - When the application starts, display a menu with the following options:

     - **Start a Review Session**: Begin a quiz-like session where users answer questions.

     - **Add a New Question**: Allow users to create and add a new review question to the question list.

2. **Add a New Question**:

   - Collect the following information from the user:

     - **Question Text**: The text of the question (ex. "What is the capital of France?").

     - **Response Options**: A list of possible answers, separated by commas (ex. "Paris, London, Berlin").

     - **Correct Response**: The correct answer from the list (ex. "Paris").

   - Example:

     ```plaintext
     Question: What is the capital of France?
     Responses: Paris, London, Berlin
     Correct Response: Paris
     ```

3. **Start a Review Session**:

   - The program should:

     - Present a random question from the list.

     - Display the question text and all response options with labels (A, B, C).

     - Prompt the user to select their answer using the labels.

     - Inform the user if their answer was correct or incorrect.

   - Example:

     ```plaintext
     Question: What is the capital of France?
     A) Paris
     B) London
     C) Berlin
     Your answer: A
     Correct! The capital of France is Paris.
     ```

**Technical Requirements**:

- Store all questions in a `.csv` file.

- Load existing questions from the `.csv` file when the application starts.

**Stretch Goals**:

- Limit the review session to questions from a specific topic or category.
