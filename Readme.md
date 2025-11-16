
```markdown
# AI Study Planner 🚀

[![GitHub stars](https://img.shields.io/github/stars/subiksha0515/AI-study-planner?style=social)](https://github.com/subiksha0515/AI-study-planner)
[![GitHub forks](https://img.shields.io/github/forks/subiksha0515/AI-study-planner?style=social)](https://github.com/subiksha0515/AI-study-planner)
[![GitHub issues](https://img.shields.io/github/issues/subiksha0515/AI-study-planner)](https://github.com/subiksha0515/AI-study-planner/issues)
[![License](https://img.shields.io/github/license/subiksha0515/AI-study-planner)](LICENSE)

## Introduction 💡

AI Study Planner is a web application designed to help students organize their study sessions effectively. Leveraging the power of AI, it generates personalized study plans, breaks down tasks, provides a weekly schedule overview, integrates calming music, and includes a Pomodoro-style study timer.  This project aims to be a comprehensive study companion, boosting productivity and reducing stress.

## Features ✨

*   **AI-Powered Study Plan Generation:**  Input your subject and learning goals, and the AI will create a tailored study plan. 🧠
*   **Task Breakdown:**  Large topics are automatically broken down into smaller, manageable tasks. 📝
*   **Weekly Schedule:**  Visualize your study plan with a clear weekly schedule. 🗓️
*   **Calming Music Integration:**  Enhance focus with integrated ambient and study music. 🎶
*   **Study Timer (Pomodoro Technique):**  Utilize a customizable Pomodoro timer to optimize study intervals and breaks. ⏱️
*   **User-Friendly Interface:** Simple and intuitive design for a seamless user experience. 💻
*   **Cross-Platform Compatibility:** Accessible through any modern web browser.🌐

## Installation ⚙️

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/subiksha0515/AI-study-planner.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd AI-study-planner
    ```

3.  **Backend Setup:**
    *   Create a `.env` file in the `backend` directory.
    *   Add your OpenRouter API key to the `.env` file:

        ```
        OPENROUTER_API_KEY=YOUR_OPENROUTER_API_KEY
        OPENROUTER_MODEL=YOUR_OPENROUTER_MODEL #Optional, defaults to a reasonable value
        ```
    *   Install the required Python packages:

        ```bash
        pip install -r backend/requirements.txt
        ```

4.  **Frontend Setup:**
    *   No specific setup is required for the frontend. It's a static HTML/JS application.

## Usage 🚀

1.  **Start the Backend:**

    ```bash
    python backend/app.py
    ```

    This will start the Flask server, typically on `http://127.0.0.1:5000`.

2.  **Open the Frontend:**

    Open the `frontend/index.html` file in your web browser.  Alternatively, if the Flask server is running, you can access the frontend through the server's route (configured in `app.py`).

3.  **Interact with the Application:**

    *   Enter your subject and learning goals in the designated fields.
    *   Click "Generate Study Plan" to receive your personalized plan.
    *   Use the weekly schedule to track your progress.
    *   Start the study timer to implement the Pomodoro technique.
    *   Enjoy the calming music while you study!

## Contributing & Contributers🤝

Contributor - [selvaganesh19](https://github.com/selvaganesh19)

We welcome contributions to the AI Study Planner project!  Here's how you can get involved:

1.  **Fork the repository.**
2.  **Create a new branch** for your feature or bug fix:

    ```bash
    git checkout -b feature/your-feature-name
    ```

3.  **Make your changes** and commit them with descriptive messages:

    ```bash
    git commit -m "Add your commit message here"
    ```

4.  **Push your branch** to your forked repository:

    ```bash
    git push origin feature/your-feature-name
    ```

5.  **Create a pull request** to the main repository.

Please ensure your code adheres to the following guidelines:

*   **Code Style:**  Maintain consistent code style (e.g., PEP 8 for Python).
*   **Testing:**  Include unit tests for any new functionality.
*   **Documentation:**  Update the documentation to reflect your changes.

## License 📜

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

## Project Files 📂

*   `README.md`:  This file, providing project information and instructions.
*   `backend/app.py`:  The main Flask application file, handling API requests and AI integration.
*   `backend/requirements.txt`: Lists the Python packages required to run the backend.
*   `frontend/index.html`: The main HTML file for the user interface.
*   `frontend/manifest.json`:  Web app manifest for PWA functionality.

## Star this project! ⭐

If you find this project helpful, please give it a star on GitHub!  Stars help us increase the visibility of the project and encourage further development.  Thank you! 🙏
```

**Important:**

*   **Replace `YOUR_USERNAME`** with your actual GitHub username.
*   **Replace `YOUR_OPENROUTER_API_KEY`** with your actual OpenRouter API key.
*   **Replace `YOUR_OPENROUTER_MODEL`** with your desired OpenRouter model (optional).
*   Make sure you have a `LICENSE` file in your repository (e.g., MIT License).  You can create one using online generators.
*   Consider adding more detailed documentation and examples as the project evolves.
*   This README assumes a basic understanding of Git, Python, and Flask.  You may want to add more detailed instructions for beginners.
*   The badges at the top are links to your project's statistics on GitHub.  They will automatically update.
*   I've added a section listing the project files for clarity.
*   I've included a call to action to star the project.
*   I've used relevant emojis to make the README more visually appealing.
*   I've used markdown formatting for headings, lists, code blocks, and links.
*   I've added a section on contributing to encourage community involvement.
*   I've added a scope to the manifest.json to make it a PWA.


## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/subiksha0515/AI-study-planner 