# Quizzler

A dynamic, GUI-based trivia application built with Python that quizzes users on various topics using real-time data from an external API.

## 🚀 Features

- **Dynamic Questions:** Fetches trivia questions dynamically from the Open Trivia Database API.  
- **Graphical User Interface:** Built with Tkinter, featuring a clean layout with custom themes and interactive buttons.  
- **Real-time Feedback:** The interface changes color (green for correct, red for incorrect) to provide immediate feedback after each answer.  
- **Score Tracking:** Automatically tracks and displays the user's current score throughout the session.  
- **OOP Architecture:** Developed using Object-Oriented Programming principles to separate data handling, logic, and UI.  

## 📂 File Structure

- **`main.py`**: The entry point of the application that initializes the data, logic, and UI.  
- **`ui.py`**: Manages the Tkinter interface, window layout, and button commands.  
- **`quiz_brain.py`**: Handles the quiz logic, including score tracking, question progression, and answer checking.  
- **`data.py`**: Manages the API request to fetch 10 boolean-type questions.  
- **`question_model.py`**: Defines the `Question` class to structure question objects.  

## 🛠️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Fiteh-21/Quizzler-API-GUI.git
cd Quizzler-API-GUI
```
2. Install dependencies:

This project requires the requests library to handle API calls.
```bash
pip install requests
```
3. Assets:

Ensure you have an images/ folder containing true.png and false.png for the UI buttons.

## 🎮 Usage

1. Run the application through the `main.py` file:

```bash
python main.py
```
2. Read the question displayed on the canvas.  
3. Click the **Check** button for True or the **Cross** button for False.  
4. The UI will flash a color to indicate if you were correct or incorrect before loading the next question.  

## 🧰 Technologies Used

- **Language:** Python 3  
- **Libraries:** Tkinter (GUI), requests (API), html (for unescaping text)  
- **API:** Open Trivia Database  
