# To-Do App Tutorial

Welcome to the To-Do App tutorial! In this project, you will learn to create a basic web application using HTML, CSS, and JavaScript. This application allows users to add tasks, mark them as complete, and delete them.

## Prerequisites

1. Basic understanding of HTML, CSS, and JavaScript.
2. A code editor (e.g., Visual Studio Code, Atom).
3. A modern web browser (e.g., Chrome, Firefox).

## Learning Objectives

By the end of this tutorial, you should be able to:

1. Create a user interface using HTML and style it with CSS.
2. Understand and implement basic DOM manipulation using JavaScript.
3. Create, read, update, and delete list items on a web page.

## Features

1. **Add Task**: Users should be able to input a task and click an "Add" button (or press Enter) to add the task to the list.
2. **Mark as Complete**: Users should be able to click on a task to mark it as complete. Completed tasks might have a strikethrough, a changed background color, or any other visual indication.
3. **Delete Task**: Next to each task, there should be a "Delete" button to remove the task from the list.

## Instructions

1. **Setup**:

   - Create a new folder for your project.
   - Inside the folder, create three files: `index.html`, `styles.css`, and `script.js`.

2. **HTML Structure**:

   - In `index.html`, set up a basic HTML structure.
   - Add input field for tasks and a button to add them.
   - Create an empty list (`<ul>` or `<ol>`) where the tasks will be displayed.

3. **Styling with CSS**:

   - Open `styles.css`.
   - Add styling to your input field, button, and list. Feel free to get creative with colors, fonts, and other styles!

4. **JavaScript Logic**:

   - In `script.js`, write the logic for adding tasks, marking them as complete, and deleting them.
   - Use event listeners to handle user actions like adding and deleting tasks.

5. **Test**:
   - Open `index.html` in your web browser.
   - Test all the features to ensure they're working as expected.

## Version Control with Git

Using Git is an essential tool for developers. Here's a basic guide to get started with Git for this project.

### Prerequisites

1. [Git](https://git-scm.com/) installed on your computer.
2. A [GitHub](https://github.com/) account (or another Git hosting service, if preferred).

### Basics of Git

1. **Initialization**:

   - Navigate to your project folder in your terminal or command prompt.
   - Run `git init` to initialize a new Git repository.

2. **Staging Changes**:

   - As you make changes to your files, Git tracks them.
   - Use `git status` to see which changes are being tracked.
   - Use `git add .` to stage all changes or `git add <filename>` to stage specific files.

3. **Committing Changes**:

   - After staging, you can commit your changes. This is like saving a version of your code.
   - Run `git commit -m "Your descriptive message here"` to commit your staged changes.

4. **Remote Repositories**:

   - Go to GitHub and create a new repository.
   - To link your local repository to the GitHub repository, run:
     ```
     git remote add origin https://github.com/YourUsername/YourRepositoryName.git
     ```

5. **Pushing Changes**:

   - After committing your changes locally, you can push them to GitHub.
   - Run `git push -u origin master` to push your changes to the master branch of your repository on GitHub.

6. **Pulling Changes**:
   - If you're collaborating with others or made changes on GitHub directly, you'll want to pull those changes to your local machine.
   - Use `git pull origin master` to get the latest version from the master branch.

### Useful Tips

- Commit often with meaningful messages. This makes it easier to track changes and find specific versions later.
- Before starting any new work, it's a good habit to pull the latest changes.
- If you're new to Git, there are many online resources and tutorials to dive deeper and learn more advanced features.

---

With the added knowledge of Git, not only will learners build a To-Do App but also get familiar with version control, a key aspect of software development.
