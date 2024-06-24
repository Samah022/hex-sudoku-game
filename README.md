# Puzzle Application 🧩

## Summary

This project is a graphical user interface (GUI) application developed in Java using Swing. The application allows users to fetch, solve, and verify Sudoku and HexSudoku puzzles. It was developed as part of a software construction course to demonstrate various software engineering concepts and techniques such as GUI design, network communication, file handling, and user input validation.

## Features

- **Puzzle Fetching**: Fetch Sudoku and HexSudoku puzzles from a server.
- **Interactive GUI**: Provide an intuitive interface for users to solve puzzles.
- **Input Validation**: Ensure user inputs are valid for the type of puzzle.
- **Solution Verification**: Compare user solutions with correct solutions stored in files.
- **Solution Display**: Show the correct solution upon request.

## Components

- **Main Frame**: The primary window of the application containing buttons to fetch puzzles and submit solutions.
- **Puzzle Panel**: A dynamically generated grid for displaying and interacting with puzzles.
- **Solution Frame**: A separate window to display the correct solution of the puzzle.

## How It Works

1. **Fetch Puzzle**: Upon clicking the "Sudoku" or "HexSudoku" button, the application sends a GET request to the server to fetch a new puzzle.
2. **Display Puzzle**: The fetched puzzle is displayed on a grid where users can fill in their solutions.
3. **Submit Solution**: Users can submit their solutions, which are then saved to a file.
4. **Verify Solution**: The application compares the user's solution file with the correct solution file and provides feedback.
5. **Show Solution**: Users can request to view the correct solution, which is displayed in a new window.

## How to Run

1. **Clone the Repository**: 
    ```sh
    git clone https://github.com/yourusername/puzzle-client.git
    ```
2. **Open the Project** in your preferred Java IDE.
3. **Run the Application**:
   a. Run server
     1. navigate to the directory where your .java file is located using the cd command.
     ```sh
      cd Specification&Design&Implementation
      ```
     2. compile the PuzzleServer.java file, use the javac command
     ```sh
      javac PuzzleServer.java
      ```
     3. Run the server
      ```sh
      java PuzzleServer
      ```
    b. Run Client
    1. compile the PuzzleClient.java file, use the javac command
       ```sh
        javac PuzzleClient.java
        ```
   3. Run the client
        ```sh
        java PuzzleClient
        ```

## Screenshots
![Screenshot 2024-06-24 223206](https://github.com/Samah022/hex-sudoku-game/assets/97039075/ef76e379-14c2-4588-8890-759bfe67db41)
![Screenshot 2024-06-24 223220](https://github.com/Samah022/hex-sudoku-game/assets/97039075/e2f0131b-7299-434f-9132-dc1ec10c3bfb)
![Screenshot 2024-06-24 223244](https://github.com/Samah022/hex-sudoku-game/assets/97039075/aad75cf8-c6de-44b4-a4bb-87a5b3ca106a)
![Screenshot 2024-06-24 223154](https://github.com/Samah022/hex-sudoku-game/assets/97039075/79e1a986-e08f-4461-9daa-d454f90abbc2)


Developed with ❤️ for the Software Construction Course. Enjoy solving puzzles! 🧩✨
