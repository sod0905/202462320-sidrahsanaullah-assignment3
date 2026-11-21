# Personal Portfolio - Sidrah Sanaullah

This is my personal portfolio website for Assignment 3, which is an extension of the work that I have done in Assignment 1 & 2. I made it using HTML, CSS, and JavaScript, and this has slightly more advanced functionality than before, with a live GitHub API section.

## Project Description

The website is a simple portfolio where I introduce myself, show some of the projects I have worked on, list my skills, and include a contact form.

This is the third version of my portfolio.

## Sections

### About Me

A short introduction about me and my interests.

### Projects

This section shows three projects I have worked on:

- Clinic Management System - Java
- Fitness Management System - Python
- Pentomino Game - JavaFX

### Skills

A list of programming languages and technologies that I have used.

### Contact

A form where visitors can enter their name, email, and message.

## JavaScript Features

The website uses JavaScript for a few interactive features:

1. A greeting that changes depending on the time of day.
2. A dark and light mode button.
3. A menu button for smaller screens.
4. Contact form validation.
5. Smooth scrolling between sections.

## New Javascript Features (for assignment 2)
1. Search projects by title, description or tags.
2. Switch between light and dark mode. The selected theme is saved.
3. Use the contact form, which checks the fields and shows a confirmation.
4. See animations when scrolling and hovering over project cards and buttons.
5. View a result count or a message when no projects match the search.

## New JavaScript Features (Assignment 3)
1. GitHub API: the "My GitHub Repositories" section loads my repositories from the GitHub API. It shows a loading message, an error message if the request fails, and a message if there are no repositories.
2. Project filter: projects can be filtered by language (All, Java, Python) and this works together with the search box.
3. Timer: the footer shows how long a visitor has been on the page, and a thank-you message appears after one minute.
4. Visitor name: visitors can enter their name, which is saved in the browser. A "Not you?" button clears it.
5. Saved theme: the light/dark mode choice is remembered between visits.

## How to Run

There is nothing that needs to be installed to run the website.

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in a browser.

You can also use VS Code with the Live Server extension if you have it installed.
The GitHub section requires an internet connection.

## AI Use Summary
I changed the theme from blue to burgundy, and asked it to generate orange colored images which would make it fit the burgundy theme. The code of assignment1 was sent to Claude along with assignment 2's rubric and I asked for an explanation on how to begin the project, along with generating basic ideas for how to do each part of the project. I used chatgpt for more clarification and asked how to step by step do each part of the code and asked for verifications on my code and whether what i did was correct. There are more details in the AI-Usage-Report. 

## Folder Structure

```text
202462320-sidrahsanaullah-assignment3/
│
├── README.md
├── index.html
├── .gitignore
│
├── css/
│   └── styles.css
│
├── js/
│   └── script.js
│
├── assets/
│   └── images/
│
└── docs/
    ├── ai-usage-report.md
    └── technical-documentation.md