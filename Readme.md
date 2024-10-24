# TAKE_AWAY_CHATGPT_REACT

### 🔗 Table of Contents

- [📍 Overview](about:blank#-overview)
- [👾 Features](about:blank#-features)
- [📂 Repository Structure](about:blank#-repository-structure)
- [🚀 Getting Started](about:blank#-getting-started)
    - [📦 Installation](about:blank#-installation)
    - [🤖 Usage](about:blank#-usage)
    - [🧪 Tests](about:blank#-tests)
- [🤝 Contributing](about:blank#-contributing)

---

## 📍 Overview

This Chrome extension enhances the messaging experience on LinkedIn by introducing AI-powered responses directly within the message input field. When users focus on the message box, an AI icon appears, allowing them to interact with a simple AI modal that helps generate canned responses. The extension is designed for ease of use, with intuitive interactions and a clean UI that aligns with LinkedIn’s messaging interface.

### Demo

[https://drive.google.com/file/d/1bZKhSWLZXzS4XVlBobdQEbXGaIezHa0t/view?usp=sharing](https://drive.google.com/file/d/1bZKhSWLZXzS4XVlBobdQEbXGaIezHa0t/view?usp=sharing)

---

## 👾 Features

1. **AI Icon Display**:
    - The AI icon appears when the user focuses on the LinkedIn message input field, offering quick access to the AI modal.
    - The icon disappears automatically when the input field loses focus, ensuring minimal distraction.
2. **AI Modal**:
    - On clicking the AI icon, a modal appears in the center of the screen, giving users a focused space to interact with the AI.
    - Clicking outside the modal closes it, maintaining a clean and unobtrusive experience.
3. **Command Input**:
    - Users can type any command into the modal’s input field, allowing flexibility for future integrations with real AI functionality.
4. **Dummy Response**:
    - Clicking the "Generate" button triggers a predefined static response:
        
        ```rust
        Thank you for the opportunity! If you have any more questions or if there's anything else I can help you with, feel free to ask.
        ```
        
    - The "Regenerate" button is currently non-functional.
5. **Message Insertion**:
    - Once the response is generated, users can insert the static response directly into LinkedIn’s message input field by clicking the "Insert" button.

---

## 📂 Repository Structure

```bash
└── Take_Away_ChatGPT_React/
    ├── assets
    │   ├── Vec.png
    │   ├── icon.png
    │   ├── inpt.png
    │   ├── main.css
    │   ├── mes_ic.png
    │   ├── rea.svg
    │   └── rel.png
    ├── entrypoints
    │   ├── background.ts
    │   ├── content
    │   └── types.ts
    ├── lib
    │   └── utils.ts
    ├── package-lock.json
    ├── package.json
    ├── postcss.config.js
    ├── public
    │   ├── icon
    │   └── wxt.svg
    ├── tailwind.config.js
    ├── tsconfig.json
    ├── wxt.config.ts
    └── yarn.lock
```

---

## 🚀 Getting Started

### 📦 Installation

Build the project from source:

1. Clone the Take_Away_ChatGPT_React repository:

```bash
❯ git clone https://github.com/JayDubey19/Take_Away_ChatGPT_React
```

1. Navigate to the project directory:

```bash
❯ cd Take_Away_ChatGPT_React
```

1. Install the required dependencies:

```bash
❯ npm install
```

### 🤖 Usage

To run the project, execute the following command:

```bash
❯ npm run build && node dist/main.js
```

### 🧪 Tests

Execute the test suite using the following command:

```bash
❯ npm test
```

---

## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- [**Report Issues**](https://github.com/JayDubey19/Take_Away_ChatGPT_React/issues): Submit bugs found or log feature requests for the `Take_Away_ChatGPT_React` project.
- [**Submit Pull Requests**](https://github.com/JayDubey19/Take_Away_ChatGPT_React/blob/main/CONTRIBUTING.md): Review open PRs, and submit your own PRs.
- [**Join the Discussions**](https://github.com/JayDubey19/Take_Away_ChatGPT_React/discussions): Share your insights, provide feedback, or ask questions.
- Contributing Guidelines
    1. **Fork the Repository**: Start by forking the project repository to your github account.
    2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
        
        ```bash
        git clone https://github.com/JayDubey19/Take_Away_ChatGPT_React
        ```
        
    3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
        
        ```bash
        git checkout -b new-feature-x
        ```
        
    4. **Make Your Changes**: Develop and test your changes locally.
    5. **Commit Your Changes**: Commit with a clear message describing your updates.
        
        ```bash
        git commit -m 'Implemented new feature x.'
        ```
        
    6. **Push to github**: Push the changes to your forked repository.
        
        ```bash
        git push origin new-feature-x
        ```
        
    7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
    8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
- Contributor Graph
    
    [https://contrib.rocks/image?repo=JayDubey19/Take_Away_ChatGPT_React](https://contrib.rocks/image?repo=JayDubey19/Take_Away_ChatGPT_React)
