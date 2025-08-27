# LifeTracker – A Personal Growth Dashboard

A single-page application (SPA) built with pure HTML, CSS, and Vanilla JavaScript. It serves as a personal dashboard for tracking habits, goals, and daily reflections.

## Features

*   **Habit Tracker:** Add, track, and check off daily or weekly habits.
*   **Goal Manager:** Create and manage long-term goals with a progress tracker.
*   **Daily Reflections:** A mini-journal for daily thoughts and notes.
*   **Visual Dashboard:** Charts visualizing habit completion rates and goal progress.
*   **Data Persistence:** All data is saved locally in the browser using `localStorage`.
*   **Inspirational Quotes:** Fetches and displays a new motivational quote daily.

## Tech Stack

*   HTML5
*   CSS3 (Grid & Flexbox for layout)
*   Vanilla JavaScript (ES6+)
*   Chart.js (for data visualization)
*   [Quotable API](https://api.quotable.io/) (for inspirational quotes)

## Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd lifetracker
    ```

2.  **Open the project:**
    Simply open the `index.html` file in your web browser. No build process is required!

    *Alternatively, for a better development experience, use a live server extension in your code editor (like VS Code's "Live Server") to avoid browser caching issues.*

## Usage

1.  **Adding a Habit/Goal:** Use the forms in each section to add a new item.
2.  **Tracking Progress:** Click on habits to mark them as complete for the day. Update goal progress as you make steps forward.
3.  **Writing Reflections:** Type your thoughts and click 'Save' to store them for the day.
4.  **Viewing Data:** Your statistics are automatically visualized in the dashboard section. All data is saved automatically.

## Project Structure

The code is organized into modules for maintainability: