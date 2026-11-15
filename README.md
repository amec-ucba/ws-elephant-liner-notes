# 💻 Assignment Boilerplate

A starting point for assignment and exercise repos. It includes submission instructions, editor and Git configuration,
and a pull request template so every assignment works the same way.

> [!NOTE]
> `.editorconfig`, `.gitattributes`, `.gitignore`, `.noai`, and the `.github` and `.idea`
> folders are setup files that keep assignments consistent. Leave them alone.

## 📋 Assignment Requirements

> [!IMPORTANT]
> **Start here: [read ASSIGNMENT.md →](.github/ASSIGNMENT.md)**

It has the requirements, grading criteria, and due date. Read it before you start, and check it again before you submit.

## ✅ At a Glance

Every assignment follows the same steps. Each guide has screenshots for every step.

| Step | What you do                                                                | Guide                                         |
|------|----------------------------------------------------------------------------|-----------------------------------------------|
| 0    | **First assignment only:** install and set up WebStorm                     | [WebStorm Setup](.github/WEBSTORM_SETUP.md)   |
| 1    | Create your repo from this template, clone it, and make a `develop` branch | [Getting Started](.github/GETTING_STARTED.md) |
| 2    | Build your page in the root folder                                         | [Where Your Files Go](#-where-your-files-go)  |
| 3    | Commit and push often, then turn on GitHub Pages                           | [Publishing](.github/PUBLISHING.md)           |
| 4    | Open a pull request into `main` and submit its URL in Canvas               | [Submitting](.github/SUBMITTING.md)           |

## 📂 Where Your Files Go

Create your files in the **root folder** of this repo — the same folder as this README.
GitHub Pages publishes from the root, so `index.html` has to live there or your site will 404. Group your assets into
subfolders:

<img src=".github/images/webstorm-project-files.png" alt="The WebStorm Project panel showing index.html in the root folder, with css/style.css, images/photo.jpg, and js/script.js in their own subfolders, all highlighted" width="350">

## 🤖 AI Policy

Work on this assignment must be your own. Do not use AI coding assistants — including
GitHub Copilot, Cursor, ChatGPT, Claude, or JetBrains AI Assistant — to generate,
complete, or rewrite your code.

You should be able to explain any line of your submission. You may be asked to do so.

This repo includes a `.noai` file, which disables JetBrains AI Assistant for the project
in IDEs like WebStorm. Leave it in place. It is a reminder of the policy above, not a
substitute for it — following the policy is still your responsibility.

> [!NOTE]
> The `.noai` file does **not** turn off WebStorm's local Full Line code completion. Turn that
> off yourself as part of the [one-time setup](.github/WEBSTORM_SETUP.md) (step 5).

> [!CAUTION]
> Late or missing submissions are graded on what is in the pull request at the deadline, so push your final commits
> before you submit.
