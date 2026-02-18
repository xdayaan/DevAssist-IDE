# DevAssist-IDE — JavaFX Intelligent Code Editor

DevAssist-IDE is a modern desktop code editor built with JavaFX, designed to provide a lightweight IDE-like experience with intelligent assistance powered by the Gemini API. This project demonstrates desktop UI engineering, file handling, syntax highlighting, and AI integration for developer productivity.

---

## Features

### Core Editor
- Multi-file editing support
- Open / Save / Save As functionality
- Keyboard shortcuts for productivity
- Status bar with cursor tracking
- Dark / Light theme toggle

### Developer Experience
- Line numbers
- Syntax highlighting (Java / JavaScript)
- Find & Replace functionality
- Auto-indentation

### AI Integration (Gemini API)
- Code explanation
- Bug detection suggestions
- Code improvement hints
- Natural language → code generation *(planned)*

---

## Tech Stack

| Component      | Technology             |
|----------------|------------------------|
| Language       | Java                   |
| UI Framework   | JavaFX                 |
| Highlighting   | RichTextFX             |
| AI Integration | Gemini API             |
| Build Tool     | Maven / Gradle         |

---

## Project Structure

```
src/
├── controller/
├── service/
├── model/
├── ui/
└── resources/
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/codepilot-ai.git
cd codepilot-ai
```

### 2. Add Your Gemini API Key

Create a `.env` file or set an environment variable:

```
GEMINI_API_KEY=your_key_here
```

### 3. Run the Application

Using Maven:

```bash
mvn javafx:run
```

Or run the main class directly from your IDE.

---

## Roadmap

- [ ] Integrated terminal panel
- [ ] Java compiler support
- [ ] Plugin system
- [ ] Git integration
- [ ] AI auto-complete suggestions

---

## Purpose

This project was built to demonstrate:

- Java desktop application engineering
- JavaFX UI architecture
- File system handling in Java
- AI-assisted development tooling
- Real-world software design practices

---

## License

This project is open source. See [LICENSE](LICENSE) for details.
