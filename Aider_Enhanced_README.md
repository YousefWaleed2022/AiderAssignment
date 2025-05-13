# React Calculator  
*A lightweight calculator built in React, extended using Aider for enhanced functionality.*

## 🧮 Original Features

- Basic operations: addition, subtraction, multiplication, division  
- Clean, responsive button layout  
- Input validation and basic error handling  

## ✨ New Enhancements

### 1. 📜 Calculation History

- **What It Does**: Stores and displays previous expressions and results (e.g., `4 + 5 = 9`).  
- **How to Use**:
  - Perform calculations as usual.
  - History appears in the right-side panel.
  - Click **Clear History** to remove all past calculations.  
- **Visual Preview**:  
  `![Placeholder: Calculation History Screenshot](history-screenshot.png)`

### 2. ⌨️ Keyboard Input Support

- **What It Does**: Allows you to use your keyboard to perform calculations.  
- **Supported Keys**:

  | Key        | Action         |
  |------------|----------------|
  | `0-9`      | Input numbers  |
  | `+ - * /`  | Operators       |
  | `Enter`    | Evaluate        |
  | `Escape`   | Clear screen    |

### 3. 🌙 Dark Mode Toggle

- **What It Does**: Enables switching between light and dark themes.  
- **Persistence**: Saves the selected theme in `localStorage`.  
- **Visual Preview**:  
  `![Placeholder: Dark Mode Screenshot](dark-mode-screenshot.png)`

## 🛠️ Development Details

- **Main Tools**: React, Aider, Webpack, Jest  
- **Key Aider Commands Used**:
  - `/add` — Add files into context  
  - `/ask` — Get clarification on codebase logic  
  - `/diff` — Review suggested changes  
  - `/run` — Test changes live  
  - `/refine` — Improve UI/UX incrementally  
  - `/test` — Validate unit tests  
  - `/commit` — Finalize edits  

## 🧱 Installation

Clone the repository:

```bash
git clone https://github.com/zeyadmahfouzz/react-calculator.git
cd react-calculator
```

## ⚙️ Fixing Node.js OpenSSL Error

If you run into OpenSSL issues with Node.js, try setting the following environment variable:

```bash
# Windows
set NODE_OPTIONS=--openssl-legacy-provider

# macOS/Linux
export NODE_OPTIONS=--openssl-legacy-provider
```

## 🚀 Running the App

To launch the calculator locally:

```bash
npm start
```

## 🧪 Running Tests

This project includes tests for:

- Calculation history  
- Theme toggle functionality  

To run all tests:

```bash
npm test
```

## 🙏 Credits

- Original project forked from [andrewagain/calculator](https://github.com/andrewagain/calculator)  
- Enhanced using **Aider** for feature development and code refinement  
