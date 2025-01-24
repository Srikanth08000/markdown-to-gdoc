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

## Setup Instructions

1. **Enable the Google Docs API**  
   - Go to [Google Cloud Console](https://console.cloud.google.com/).
   - Create (or select) a Google Cloud project.
   - Enable the **Google Docs API** (and optionally the **Google Drive API** if needed).

2. **Clone or Download This Repository**  
   - Clone via `git clone https://github.com/Srikanth08000/markdown-to-gdoc.git`, or
   - Download the ZIP and extract it locally.

3. **Open `main.ipynb` in Google Colab**  
   - Either upload `main.ipynb` to Colab, or
   - Go to [Google Colab](https://colab.research.google.com/), choose **GitHub**, and paste your repo’s URL.

---

## Required Dependencies

Within the Colab environment, you’ll need:
- **Python 3.7+** (comes preinstalled on Colab)
- **google-api-python-client**
- **google-auth-oauthlib**
- **google-auth-httplib2**

You can install them in the Colab notebook with:
```bash
!pip install --quiet google-api-python-client google-auth-httplib2 google-auth-oauthlib

```bash
!pip install --quiet google-api-python-client google-auth-httplib2 google-auth-oauthlib
