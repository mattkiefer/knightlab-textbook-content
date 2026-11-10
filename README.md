# Introduction to Data

This repository contains the content and shared Dev Container configuration for the Knight Lab Introduction to Data textbook. The VS Code extension and container template are maintained in the Knight Lab Textbook Framework repository.

## Structure

- Each immediate subfolder of `chapters/` is one chapter.
- Put the lesson page in `lesson.html`.
- An optional `.py`, `.R`, or `.js` file is opened as the chapter's starter code.
- Number prefixes are optional. Decimal prefixes such as `1.2-data` are supported and only affect ordering; they are omitted from the displayed chapter title.
- `datasets/` and the dependency manifests at the repository root are available to the reusable framework when it builds the course environment.
- `.devcontainer/` contains the standard Dev Container configuration used by both desktop VS Code and GitHub Codespaces.

Open this repository in desktop VS Code and choose **Dev Containers: Reopen in Container**, or create a Codespace from the repository. Both use the same Linux environment. Codespaces does not support mounting folders from the student's computer; use the Codespaces Explorer to upload files into the workspace. The framework's custom Textbooks sidebar is a separate extension and is not automatically installed in Codespaces.

The framework currently discovers this book from a hard-coded catalog entry. It fetches updates from this repository's `main` branch.
