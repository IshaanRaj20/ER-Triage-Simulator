# 🏥 ER Triage Simulator

An interactive, educational healthcare simulation that demonstrates how emergency room professionals sort symptoms by urgency using triage principles.

## 🚀 Overview

**ER Triage Simulator** is a web application designed to demonstrate how medical professionals evaluate symptoms, identify potential warning signs, and organize patients according to urgency.

Users can describe a fictional or general symptom scenario, answer follow-up questions, and receive an educational triage assessment with an explanation of the warning signs identified.

The application combines built-in JavaScript rules with an optional Claude AI integration to simulate a conversational triage experience.

## ✨ Features

- **Interactive Symptom Chat** – Describe symptoms and interact with a simulated triage assistant.
- **AI Integration** – Optional Claude API integration for more contextual conversations.
- **Offline Simulation** – Built-in JavaScript rules allow the application to function without an API key.
- **Color-Coded Triage System** – Three educational urgency categories:
  - 🔴 RED – Emergency warning signs.
  - 🟡 YELLOW – Prompt medical attention.
  - 🟢 GREEN – General educational information.
- **Follow-Up Questions** – The assistant can ask up to two clarifying questions.
- **Triage Results Dashboard** – Displays identified warning signs, explanations, and possible professional evaluations.
- **Example Scenarios** – Explore predefined fictional medical situations.
- **Session History** – Keep track of completed simulations during the current session.
- **Responsive Design** – Works across desktop, tablet, and mobile devices.
- **Modern UI** – Clean healthcare-inspired interface with interactive elements and animations.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling and responsive design |
| JavaScript | Interactive functionality and simulation logic |
| Claude API | Optional conversational AI integration |
| Local Storage | Stores the optional API key in the browser |

## 📂 Project Structure

```text
ER_Triage_Simulator/
│
├── index.html       # Main application
├── favicon.ico      # Application favicon
└── README.md        # Project documentation
```

The application is built as a single HTML file containing its HTML, CSS, and JavaScript.

## ⚙️ Getting Started

### 1. Download the Project

Download or clone the project files to your computer.

### 2. Open the Application

Locate `index.html` and open it in your preferred web browser.

No package installation or build process is required for offline mode.

### 3. Explore the Simulator

- Enter a fictional symptom scenario.
- Answer the assistant's follow-up questions.
- Review the educational triage results.
- Try the predefined example scenarios.

## 🤖 Optional Claude AI Integration

The application supports an optional Claude API connection.

To configure it:

1. Open the ER Triage Simulator.
2. Select **AI Settings**.
3. Enter your Anthropic API key.
4. Save the key.

Without an API key, the application automatically uses its built-in JavaScript simulation rules.

**Security note:** The current implementation stores the API key in browser Local Storage and sends requests directly from the browser. This is not suitable for protecting a private production API key. A secure backend should handle API requests before using this feature in a publicly deployed application. Never enter personal medical information into this demonstration.

## 🧠 How the Simulation Works

The application uses two possible processing modes:

**1. Offline Rules Mode**

A built-in JavaScript engine checks symptom descriptions against predefined warning-sign patterns and asks relevant follow-up questions.

**2. Live AI Mode**

When configured, the application sends the conversation to Claude, which generates contextual responses and educational triage explanations.

Both modes use predefined safety rules to prioritize recognized emergency warning signs.

## 🎯 Project Goals

- Demonstrate the fundamentals of emergency room triage.
- Explore how AI can support conversational interfaces.
- Understand how symptom-related information can be organized.
- Practice building interactive applications using vanilla JavaScript.
- Explore the intersection of healthcare and artificial intelligence.

## ⚠️ Medical Disclaimer

ER Triage Simulator is an educational software project, not a medical diagnostic tool.

It cannot diagnose medical conditions, determine whether someone is safe, or replace professional medical judgment.

Its color-coded categories are simplified educational demonstrations, not real clinical triage classifications.

If someone may be experiencing a medical emergency, contact 911 in the United States or the appropriate local emergency service immediately.

## 👨‍💻 Developer

**Created by Ishaan Raj**

An educational software project exploring artificial intelligence, healthcare technology, and interactive web development.

---

*Built with curiosity, creativity, and code.*