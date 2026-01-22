# Flutter App Showcase

## Overview

This repository serves as a **professional portfolio** demonstrating my proficiency in building robust and feature-rich mobile applications using the Flutter framework. It is a collection of distinct, fully functional projects, including a comprehensive **To-Do List Manager** and a dynamic **News Aggregator**, all developed within a single, well-organized Flutter project structure.

This showcase highlights my skills in:
*   Implementing complex UI/UX designs.
*   Integrating with external APIs.
*   Managing application state effectively.
*   Adhering to clean and modular code architecture.

## Projects Included

| Project Name | Description | Key Features |
| :--- | :--- | :--- |
| **To-Do App** | A task management application designed to help users organize their daily activities. | **CRUD Operations** (Create, Read, Update, Delete), Task categorization (New, Done, Archived), Intuitive UI/UX. |
| **News App** | A mobile client for browsing and reading news articles from a public API. | **API Integration** (using Dio/http ), Dynamic list loading, Article detail view, Search functionality. |
| **Utility Modules** | Smaller, focused applications demonstrating specific Flutter concepts. | **BMI Calculator**, Login/Registration UI, Messenger UI layout, Counter App. |

## Tech Stack

*   **Framework:** Flutter
*   **Language:** Dart
*   **State Management:** (Placeholder: e.g., Provider, Bloc, Riverpod, or Stateful Widgets)
*   **Architecture:** Modular structure for separation of concerns (using `lib/layout`, `lib/modules`, `lib/shared`).
*   **Data Handling:** Local storage (for To-Do) and REST API integration (for News).

## Getting Started

### Prerequisites

*   Flutter SDK installed on your machine.
*   An IDE (VS Code or Android Studio) with the Flutter and Dart plugins.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/saloma03/Flutter-App-Showcase.git
    cd Flutter-App-Showcase
    ```
2.  **Install dependencies:**
    ```bash
    flutter pub get
    ```
3.  **Run the application:**
    ```bash
    flutter run
    ```
    *Note: The main entry point (`lib/main.dart` ) will navigate to a screen that allows selection between the different apps.*

## Project Structure Recommendation

The current structure places the main apps under `lib/layout/news_app` and `lib/layout/todo_app`. While functional, for a professional portfolio, it is highly recommended to separate each main application into its own top-level folder or even its own repository.

**Recommendation:**

1.  **Option 1 (Best for Portfolio):** Create a separate GitHub repository for the **To-Do App** and another for the **News App**. This makes each project look like a standalone, complete application.
2.  **Option 2 (Keep in one repo):** Move the main app folders to the root of `lib/` to make them more prominent:
    *   `lib/todo_app/`
    *   `lib/news_app/`
    *   `lib/shared/` (for common components)

This will make it easier for recruiters to see the distinct projects.

