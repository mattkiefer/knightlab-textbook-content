# Introduction to Data

This repository contains the content for the Knight Lab Introduction to Data textbook. The shared VS Code extension and Dev Container setup are maintained separately in the Knight Lab Textbook Framework repository.

## Structure

- Each immediate subfolder of `chapters/` is one chapter.
- Put the lesson page in `lesson.html`.
- An optional `.py`, `.R`, or `.js` file is opened as the chapter's starter code.
- Number prefixes are optional. Decimal prefixes such as `1.2-data` are supported and only affect ordering; they are omitted from the displayed chapter title.
- `datasets/` and the dependency manifests at the repository root are available to the reusable framework when it builds the course environment.

The framework currently discovers this book from a hard-coded catalog entry. It fetches updates from this repository's `main` branch.
