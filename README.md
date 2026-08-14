# 📝 JavaScript Console To-Do Application

A lightweight, prompt-driven task management application built with vanilla JavaScript and HTML5. This project demonstrates core JavaScript fundamentals including array manipulation, control flow structures, dynamic user input handling, and browser console output.

---

## 🌟 Overview

The **JavaScript Console To-Do Application** provides an interactive command-line style interface directly within the web browser. Users interact through browser `prompt()` dialogs, executing essential CRUD (Create, Read, Delete) operations while viewing real-time state changes inside the browser's developer console.

---

## 🚀 Key Features

* **List Tasks (`list`):** Iterates through active tasks and displays each item alongside its zero-based index in the browser console.
* **Add Tasks (`add`):** Prompts for task descriptions and dynamically appends them to the task list using array methods.
* **Delete Tasks (`delete`):** Allows removal of specific items by their array index via JavaScript's `splice()` method.
* **Graceful Exit (`quit`):** Safely breaks out of the continuous execution loop and terminates the session.
* **Command Validation:** Handles unrecognized input gracefully with informative console feedback.

---

## 🛠️ Built With

* **HTML5:** Minimal markup structure providing user guidance.
* **JavaScript (ES6):** Core application logic, array manipulations, and execution loops.

---

## 📁 Repository Structure

* `README.md` — Project documentation.
* `app.js` — Core JavaScript logic and interactive loop.
* `index.html` — Application entry point and on-screen instructions.


---

## 💻 How to Run

1. Download or open the project files on your computer.
2. Double-click **`index.html`** to launch it in any web browser (Chrome, Edge, Firefox, Safari).
3. Open the **Browser Developer Tools / Console**:
   * **Windows/Linux:** Press `F12` or `Ctrl + Shift + I` and switch to the **Console** tab.
   * **macOS:** Press `Cmd + Option + I` and switch to the **Console** tab.
4. Interact with the browser prompts to manage your tasks.

---

## 📖 Usage & Commands

| Command | Action | Description |
| :--- | :--- | :--- |
| `list` | **View All** | Prints all active tasks with indices to the console. |
| `add` | **Create** | Prompts for a task description and appends it to the list. |
| `delete` | **Remove** | Prompts for a specific index and removes that task. |
| `quit` | **Exit** | Breaks the execution loop and closes the session. |

---

## 🧠 Concepts Demonstrated

* **Loops & Control Flow:** `while (true)` loop with conditional branching (`if / else if / else`) and loop termination (`break`).
* **Array Methods:** Dynamic array operations using `push()` and `splice()`.
* **User Input & DOM Dialogs:** Handling synchronous user inputs using `prompt()` and displaying formatted logs via `console.log()`.

---

## 🔮 Roadmap / Future Improvements

- [ ] Transition from prompt dialogs to an interactive DOM-based UI with forms and buttons.
- [ ] Implement `localStorage` to persist tasks across browser reloads.
- [ ] Add status toggles (`completed` / `pending`) and priority tags.
- [ ] Add comprehensive input validation and edge-case sanitization.

---

