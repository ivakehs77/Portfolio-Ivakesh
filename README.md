# abishek@portfolio:~$

> An interactive, terminal-based personal portfolio. Built to showcase my projects, experience, and love for building things from scratch. 

**[View the Live Site Here]** 

I wanted to build a highly polished, interactive portfolio without relying on bloated frameworks like React for what is essentially a static site. This entire project runs on vanilla HTML, CSS, and JavaScript, living inside a single file with zero dependencies and no build step.

## 🛠️ Technical Features

* **Zero Dependencies:** No npm, no frameworks, no external CSS libraries. Just the DOM and vanilla JS.
* **Custom Command Engine:** A lightweight parser that handles commands, arguments, and specific error states.
* **Authentic Terminal UX:**
  * `Tab` for command autocomplete.
  * `↑` / `↓` arrows to navigate command history.
  * `Ctrl + L` to clear the screen, `Ctrl + C` to cancel a prompt.
* **Theming System:** Change the UI colors on the fly (try `theme amber` or `theme matrix`). State is preserved in `localStorage`.
* **Deep Linking:** Append `?cmd=<command>` to the URL to automatically execute a command on load (e.g., `?cmd=whoami`).
* **Graceful Degradation:** The Matrix-style canvas background disables automatically on mobile devices to save battery and rendering resources.

## 💻 Available Commands

Once you're in the terminal, type `help` or `help --all` to see the full list of commands. A few to get you started:

* `whoami` — Displays my bio, education, and current focus area.
* `projects` — Lists my core builds (PuriPy, Astralecture, RAG Chatbot).
* `experience` — Shows my work history.
* `skills` — Outputs my technical stack.
* `cat <project>` — Drills down into specific project details and links.
* `theme <name>` — Changes the terminal theme (default, amber, matrix, solar).
* `clear` — Clears the terminal output.

*Hint: There are several hidden easter eggs scattered throughout the system. Try seeing what happens when you attempt to escalate your privileges.*

## 🚀 Local Development

Because there is no build step or package manager, running this locally is as simple as it gets:

1. Clone the repository:
   
```bash
   git clone [https://github.com/ivakehs77/portfolio.git](https://github.com/ivakehs77/portfolio.git)
Open index.html in your browser.

That's it.

📞 Contact & Status
I am currently a CS + Data Analytics student at Texas State University (Class of 2028), actively seeking SWE Internships.

Email: abishekpuri77@gmail.com

GitHub: @ivakehs77

LinkedIn: Abishek Puri

If you're hiring engineers who sweat the details, let's talk.