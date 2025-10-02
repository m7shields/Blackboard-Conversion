blackboard-conversion-toolkit/ root
# Blackboard Conversion Toolkit

The **Blackboard Conversion Toolkit** helps you extract, convert, and repurpose Blackboard course exports into a portable, searchable, and user-friendly offline course site.  

This tool converts a Blackboard `.zip` export into:  
- 📂 Markdown files (one per Blackboard item)  
- 🖼 Media folder with linked resources (PDF, PPTX, images, video, etc.)  
- 📑 `TOC.md` (Markdown table of contents)  
- 🌐 `index.html` (interactive offline course site)  
- 🔍 `search_index.json` (prebuilt index for fast full-text search)

---

## ✨ Features
- **Blackboard export parser** — preserves course hierarchy from `imsmanifest.xml`  
- **HTML → Markdown** conversion  
- **Relinked media** — all attachments copied to `/media/` and referenced correctly  
- **Interactive viewer** (`index.html`) with:
  - Sidebar navigation  
  - Live filtering of titles  
  - Full-text search across all content (snippets + highlights)  
  - Scroll-to-first-match highlighting  
  - **Download PDF** button for any rendered page  
- **Offline-first** — no server required, just open `index.html`

---

## 📦 Requirements
Python 3.8+  

Install dependencies:
```bash
pip install -r requirements.txt
