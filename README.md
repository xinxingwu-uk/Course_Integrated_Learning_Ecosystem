# Course-Integrated Learning Ecosystem

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**A tablet-inspired, course-integrated environment for learning introductory programming through structured, hands-on activities.**

This repository shares instructional materials and a web-based learning interface developed for **COS 107: Problem Solving, Logic & Design** at **Kentucky State University** (Fall 2026). The current implementation uses Python to introduce computational thinking, problem solving, program design, and practical computing skills. It brings course navigation, learning resources, guided practice, and independent lab activities together in one place.

## Project Overview

The Course-Integrated Learning Ecosystem is designed to make introductory programming more accessible and engaging by connecting foundational concepts with small, practical tasks. Its main design elements include:

- **An integrated course hub:** A tablet-inspired homepage provides access to the course syllabus, introduction, and weekly learning activities.
- **Progressive learning:** Sixteen labs move from basic Python statements to data handling, visualization, object-oriented programming, databases, and a game-related final activity.
- **Guided and independent practice:** Labs 1–15 pair introductory explanations and in-class coding with independent programming tasks, summaries, and a Google Colab–Gradio workflow.
- **Practice with real tools:** Students can write Python in Thonny, experiment in Google Colab, and build simple web interfaces with Gradio.
- **Reusable instructional materials:** HTML-based lessons can be reviewed, adapted, and used as a starting point for similar courses.

## Explore the Course

- **[Open the course homepage](COS107_Paper/Homepage/index.html)** — tablet-inspired course dashboard
- **[Read the course syllabus](COS107_Paper/COS107.html)** — course goals, learning outcomes, policies, and schedule
- **[View the course introduction](COS107_Paper/Intro/Introduction.html)** — orientation and learning roadmap

> **Note:** Links to Canvas assignments, quizzes, and other university systems may require Kentucky State University access. The public HTML lessons can be viewed separately.

## Learning Path: 16 Labs

| Lab | Topic and hands-on focus |
| --- | --- |
| [01](./Lab1/lab1.html) | Hello Python — print statements, comments, and strings |
| [02](./Lab2/lab2.html) | Input and variables — interactive profile |
| [03](COS107_Paper/Lab3/lab3.html) | Numbers and calculations — tip calculator |
| [04](COS107_Paper/Lab4/lab4.html) | Decision structures — grade advisor |
| [05](COS107_Paper/Lab5/lab5.html) | Loops — repetition and running totals |
| [06](COS107_Paper/Lab6/lab6.html) | Functions — organizing and reusing code |
| [07](COS107_Paper/Lab7/lab7.html) | Modules and random numbers — mini games |
| [08](COS107_Paper/Lab8/lab8.html) | Strings — text analysis and validation |
| [09](COS107_Paper/Lab9/lab9.html) | Lists — storing and processing values |
| [10](COS107_Paper/Lab10/lab10.html) | Dictionaries and sets — lookups and unique values |
| [11](COS107_Paper/Lab11/lab11.html) | Files and exceptions — saving data safely |
| [12](COS107_Paper/Lab12/lab12.html) | CSV data — reading and summarizing tables |
| [13](COS107_Paper/Lab13/lab13.html) | Data visualization — plotting with Matplotlib |
| [14](COS107_Paper/Lab14/lab14.html) | Object-oriented programming — classes and objects |
| [15](COS107_Paper/Lab15/lab15.html) | SQLite capstone — a small database application |
| [16](COS107_Paper/Lab16/lab16.html) | Flappy Bird — game programming example / final project activity |

## Getting Started

### View the learning materials

1. Clone or download this repository:

   ```bash
   git clone https://github.com/xinxingwu-uk/Course_Integrated_Learning_Ecosystem.git
   ```

2. Open **`COS107_Paper/Homepage/index.html`** in a modern web browser.
3. Select the course introduction or a weekly lab from the homepage. You can also open any lab's HTML file directly.

The course interface is built primarily with **HTML, CSS, and JavaScript**, including [Reveal.js](https://revealjs.com/) for presentation-style lessons. No Python installation is required just to read the HTML materials. Some linked resources and features require an internet connection.

### Practice the Python examples

- Use [Thonny](https://thonny.org/) or another Python environment for introductory exercises.
- Use [Google Colab](https://colab.research.google.com/) for notebook-based practice.
- For lessons that use [Gradio](https://www.gradio.app/), install it in your Python environment or a Colab cell:

  ```python
  !pip install gradio
  ```

- Some later examples require additional libraries such as **Matplotlib** or **Pygame**. The game activity may also require separate image/audio assets to execute; the provided HTML is instructional material, not a standalone packaged game.

## Repository Structure

```text
├── Course_Integrated_Learning_Ecosystem/
│   ├── COS107.html              # Course syllabus
│   ├── Homepage/
│   │   └── index.html           # Tablet-inspired course hub
│   ├── Intro/
│   │   └── Introduction.html    # Course orientation
│   ├── Lab1/ ... Lab16/         # Weekly HTML labs and supporting files
│   ├── css/                     # Shared styles
│   └── js/                      # Shared scripts
├── README.md
└── LICENSE                     # MIT License
```

Each lab directory includes presentation assets and supporting files. Directory structure may change as additional courses or materials are added.

## Teaching and Research Use

These materials may be useful to instructors designing introductory programming courses and to researchers studying course-integrated, practice-oriented learning environments. The sequence emphasizes **concept introduction → guided coding → independent practice → application**, with opportunities for students to extend console programs into simple web interfaces.

The repository presents instructional artifacts and design ideas; it does not, by itself, establish evidence of learning effectiveness.


## License and Attribution

The original project materials are released under the **[MIT License](LICENSE)**. Copyright © 2026 Xinxing Wu.

The repository also contains third-party software and visual assets, including Reveal.js and icon/media resources. Those components remain subject to their **respective licenses and attribution requirements**; the project's MIT License does not replace those third-party terms. Please review applicable notices before redistributing or adapting third-party assets.

If you use or adapt these educational materials, attribution to the project and author is appreciated.
