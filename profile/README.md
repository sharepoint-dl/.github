# 📦 Public Folder ZIP Downloader

**Turn any public OneDrive or SharePoint folder into a single, easy-to-download ZIP file.**

[![Website](https://img.shields.io/badge/Website-Live-blue)](https://sharepoint-dl.github.io)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## 🚀 What does it do?

Ever tried to download a shared folder from OneDrive or SharePoint, only to find that you can't download the whole thing as a ZIP unless you have an account?

**This tool fixes that.**

Just paste a public shared folder link, and the tool will:

1. **Scrape** the public folder's contents.
2. **Fetch** all files in the background.
3. **Package** them into one `sharepoint-download.zip`.
4. **Serve** it directly to your browser.

## ✨ Key Features

- ⚡ **No Account Required**: Works for any link shared as "Anyone with the link can view."
- 📦 **Automatic Packaging**: No more clicking "Download" on 50 individual files.
- 🔒 **Privacy First**: Files are processed transiently and deleted immediately after the ZIP is created.
- 🛠️ **CLI Support**: For power users, a Python-based CLI tool is available for mirroring folders to local disk.

## 🛠️ Tech Stack

- **Frontend**: Vanilla JS, CSS (Glassmorphism Design).
- **Backend**: Python (Dependency-free for maximum portability).
- **Hosting**: GitHub Pages & Render.

---

_Created for the community to make public data access easier._
