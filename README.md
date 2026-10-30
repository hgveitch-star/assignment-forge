# Assignment Forge 🛠️

A custom web-based tool designed to help students manage, forge, and organize their assignments efficiently. It reads your syllabus, remembers every deadline across all your courses, and coaches your thinking — without ever writing a word of your assignment for you.

## 🚀 Live Demo

You can use the tool directly in your browser here:
[https://hgveitch-star.github.io/assignment-forge/](https://hgveitch-star.github.io/assignment-forge/)

## ✨ Features

- **Reads your syllabus and brief so you don't have to retype them.** Upload a PDF or Word file and the tool extracts the course code, task description, word count, due date, rubric, AI-use policy, and the assessment schedule — then shows you a review screen so you can correct anything the AI got wrong. It never guesses. Empty is better than invented.

- **Remembers every deadline in one place.** Assignments, tests, exams, and presentations across all your courses appear in a single chronological view. When more than two assignments fall due in the same seven-day window, and together they ask for more than eight hours of work, the tool flags the cluster in orange. Not to panic you — to help you plant early.

- **Coaches your thinking; never writes your prose.** Every phase has a Socratic thinking partner: guided walkthroughs when you're stuck, seed questions, three layers of feedback (structure, paragraph, sentence), and a translation bridge for multilingual students. The tool refuses, architecturally, to write prose for you. What it will do: insert the correct in-text citation from your approved reading list at your cursor, in the citation style your brief specifies.

## 🚫 What it won't do

- It won't write your assignment for you. That's the point.
- It won't store your work anywhere except your own browser (IndexedDB and localStorage). There is no server, and there is no data collection.
- It won't check for plagiarism or predict your grade.

## ⚠️ What you'll need

- A modern web browser.
- An API key from one of the supported AI providers (DeepSeek, OpenAI, Claude, Gemini, Perplexity, or Groq). The tool runs entirely in your browser and never sends your work anywhere except to the provider you chose. Typical cost: a few US cents per assignment.

## 🛠️ How to Use

No installation required. Just open the live link above or clone this repository and open `index.html` in any web browser.

## 👨‍💻 Author

**Herman Veitch**
- GitHub: [@hgveitch-star](https://github.com/hgveitch-star)
