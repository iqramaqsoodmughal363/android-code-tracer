# 💻 Code Tracer

<p align="center">
  <b>Learn, Code, and Visualize Data Structures on the go.</b>
</p>

<p align="center">
  <em>"An interactive Android application built in Java featuring a custom code editor, universal interpreter, syntax validator, and real-time visualizers for Arrays, Stacks, and Queues."</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red" alt="Made with Love">
  <img src="https://img.shields.io/badge/Platform-Android-green" alt="Platform">
  <img src="https://img.shields.io/badge/Language-Java-orange" alt="Language">
  <img src="https://img.shields.io/badge/Feature-Code%20Interpreter-blueviolet" alt="Feature">
  <img src="https://img.shields.io/badge/Status-Complete-success" alt="Status">
</p>

---

## 📋 Overview

**Code Tracer** is a powerful, educational Android application designed to help students and developers practice coding and understand data structures visually. Built entirely in **Java**, the app includes a custom code editor, a universal interpreter to execute basic logic, and interactive visualizers for common data structures. 

Whether you are learning a new language or trying to understand how a Stack works, Code Tracer provides a hands-on environment to experiment with code directly on your phone.

---

## ✨ Key Features

* **📝 Custom Code Editor (`EditorActivity.java`):** A built-in text editor to write and run code snippets.
* **🌍 Universal Interpreter (`UniversalInterpreter.java`):** A custom engine that parses and executes basic programming logic.
* **✅ Syntax Validator (`SyntaxValidator.java`):** Real-time syntax checking to help you catch errors before running your code.
* **📊 Data Structure Visualizers:**
  * **Array Visualizer (`ArrayVisualizer.java`):** See arrays in action.
  * **Stack Visualizer (`StackVisualizer.java`):** Understand LIFO (Last-In-First-Out) principles visually.
  * **Queue Visualizer (`QueueVisualizer.java`):** Understand FIFO (First-In-First-Out) principles visually.
* **📚 Examples & Tutorials:** Pre-built examples (`ExamplesActivity.java`) and step-by-step tutorials (`TutorialActivity.java`) to get started quickly.
* **🎨 Beautiful UI:** Features a custom splash screen (`SplashActivity.java`) and dedicated layouts for different programming concepts.

---

## 🛠️ Tech Stack

| Category | Tools / Technologies |
|---|---|
| **Language** | Java |
| **IDE** | Android Studio |
| **UI Components** | XML Layouts, Custom Views, Animations |
| **Core Logic** | Custom Interpreter & Syntax Parser |
| **Data Structures** | Array, Stack, Queue (Visualized via Java) |

---

## 📂 Project Structure

```text
android-code-tracer/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── kotlin+java/com/codetracer/app/
│   │   │   │   ├── ArrayVisualizer.java          # Array logic & visualization
│   │   │   │   ├── EditorActivity.java           # Code Editor UI
│   │   │   │   ├── ExamplesActivity.java         # Pre-loaded code examples
│   │   │   │   ├── LanguageSelectActivity.java   # Choose programming language
│   │   │   │   ├── MainActivity.java             # Main Dashboard
│   │   │   │   ├── QueueVisualizer.java          # Queue logic & visualization
│   │   │   │   ├── SplashActivity.java           # App Startup Screen
│   │   │   │   ├── StackVisualizer.java          # Stack logic & visualization
│   │   │   │   ├── SyntaxValidator.java          # Custom syntax checker
│   │   │   │   ├── TopicSelectActivity.java      # Choose a topic
│   │   │   │   ├── TutorialActivity.java         # Educational tutorials
│   │   │   │   └── UniversalInterpreter.java     # The code execution engine
│   │   │   ├── res/
│   │   │   │   ├── drawable/                     # Icons and custom shapes
│   │   │   │   ├── layout/                       # UI Layouts
│   │   │   │   │   ├── activity_editor.xml
│   │   │   │   │   ├── activity_examples.xml
│   │   │   │   │   ├── activity_language_select.xml
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   │   ├── activity_splash.xml
│   │   │   │   │   ├── activity_topic_select.xml
│   │   │   │   │   └── activity_tutorial.xml
│   │   │   │   ├── mipmap/                       # App icons (WebP format)
│   │   │   │   └── values/                       # Colors, Strings, Themes
│   │   │   └── AndroidManifest.xml
│   │   └── build.gradle.kts
│   ├── proguard-rules.pro
│   └── gradle/
├── build.gradle.kts
├── libs.versions.toml
├── settings.gradle.kts
└── README.md
```

---

## 🚀 How to Build and Run

### Prerequisites
* **Android Studio** (Latest Version)
* **JDK 17** or higher (Since Kotlin DSL is used)
* **Android SDK** (API 24+)

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/iqramaaqsoodmughal363/android-code-tracer.git
   ```
2. **Open in Android Studio**
   Open Android Studio → **File** → **Open** → Select the `android-code-tracer` folder.
3. **Sync Gradle**
   Wait for Gradle to sync. Click **"Sync Now"** if prompted.
4. **Build and Run**
   Connect your Android device or start an emulator, then click the **Run** button (green play icon).

---

## ⚙️ How It Works (Behind the Scenes)

### 1. The Core Engine (`UniversalInterpreter.java`)
This is the heart of the app. It takes the raw string input from the `EditorActivity`, parses it, and executes the logic. This is a custom-built mini-compiler/interpreter that translates user code into actionable results.

### 2. Syntax Checking (`SyntaxValidator.java`)
Before the code is passed to the interpreter, the `SyntaxValidator` runs a series of checks to ensure the code follows the basic rules (e.g., matching brackets, correct keywords), providing a smooth user experience by catching errors early.

### 3. Visualizing Data Structures
The `StackVisualizer`, `QueueVisualizer`, and `ArrayVisualizer` use custom Android Views and Animations to dynamically draw the data structures on the screen. When a user pushes to a stack or enqueues a queue, the UI updates in real-time.

---

## 🎯 Key Takeaways

* **Educational Tech:** A perfect blend of education and technology.
* **Custom Compiler:** Demonstrates advanced string parsing and execution logic in Java.
* **UI/UX:** Shows how to build custom interactive visualizers in Android.
* **Clean Architecture:** Well-organized packages for Activities, Logic, and Utilities.

---

## 👩‍💻 Author

**Iqra Maqsood Mughal**

*Software Engineer · Full-Stack Developer · Code Craftsman · Android App Developer · Problem Solver 🚀*

```javascript
const codeIsLife = "Code is life";
while (true) { 
    learn(); 
    build(); 
    innovate(); 
}
```

---

## 📅 Date

October 18, 2026

---

## 📄 License

This project is intended for educational and personal use purposes.
