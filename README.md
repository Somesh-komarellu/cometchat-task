# CometChat Internship Task - UI Kit Integration

This repository contains the implementation of the **CometChat UI Kit for React**, created as part of the internship evaluation task. The project demonstrates the successful integration of the CometChat Widget, including authentication, real-time messaging, and UI customization.

**Note:** This codebase is uploaded "as-is" from the UI Kit Builder to demonstrate the default behavior, including the linting warnings and deprecated dependencies documented in the accompanying Usability Report PDF.

## 🚀 Project Overview

* **Platform:** React (Web)
* **Tool:** CometChat UI Kit Builder
* **Features Implemented:**
    * User Authentication (Login)
    * 1-on-1 & Group Messaging
    * Voice & Video Calling
    * Rich Media Support
    * Custom Theme (Dark Mode)

---

## 📸 Screenshots

### 1. Application Login
*The entry point showing the sample user login interface.*
![Login Screen](./Screenshot%202025-12-03%20130910.png)

### 2. UI Kit Configuration (Builder)
*The configuration process in the CometChat Dashboard where I customized the layout and theme.*
![UI Kit Builder](./Screenshot%202025-12-03%20125114.png)

### 3. Chat Interface (Dark Mode)
*The fully functional chat interface running on `localhost:3000`.*
![Chat Interface](./Screenshot%202025-12-03%20131222.png)

### 4. UI Interaction & Testing
*Testing specific UI elements, such as the delete functionality and hover states (documented in the friction report).*
![UI Interaction](./Screenshot%202025-12-03%20131900.png)

---

## 🛠️ Installation & Setup

To run this project locally:

1.  **Clone the repository:**
    ```bash
    git clone [YOUR_GITHUB_REPO_LINK_HERE]
    ```

2.  **Install Dependencies:**
    ```bash
    npm install
    ```
    *(Note: You may see deprecation warnings during install, as noted in the technical review).*

3.  **Run the Application:**
    ```bash
    npm start
    ```
    Runs the app in the development mode.\
    Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

---

## 📝 Technical Review & Findings

A detailed PDF report has been submitted alongside this repository. Key findings included in this implementation:

* **Dependency Status:** The generated `package.json` relies on several deprecated Babel plugins.
* **Code Quality:** The default output contains ESLint warnings regarding loose equality checks (`==`) and unused variables.
* **UI Observations:** Feedback on the visual hierarchy and hovering states in the UI Kit Builder.
