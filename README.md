# Markdown to Google Docs Converter

This repository provides a **Google Colab Notebook** that converts Markdown meeting notes into a well-formatted **Google Doc** using the **Google Docs API**.

## Features
- Parses headings (`#`, `##`, `###`) and applies **Heading 1**, **Heading 2**, **Heading 3** styles in Google Docs.
- Converts Markdown bullet points and **nested bullet points** into properly indented bullet lists.
- Converts `- [ ]` items into **checklist** bullets in Google Docs.
- Highlights `@mentions` by making them **bold** and assigning a **red** color.
- Preserves footer content (“Meeting recorded by,” “Duration,” etc.) with a separate style (optional).
- Skips lines containing only `---` or `--` (treated as horizontal rules).

---

