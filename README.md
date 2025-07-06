# SOCHI Newsletters Archive

This repository contains all SOCHI newsletter issues and a structured JSON archive used to dynamically display newsletters on the SOCHI website.

---

## 🗂 Folder Structure

Each newsletter is stored in its own folder:

newsletter-01/
└── index.html
└── images/
newsletter-02/
└── index.html
└── images/
...
newsletters.json


- `index.html` should contain the full rendered HTML of the newsletter.
- Images must be stored locally (e.g., in an `images/` folder) and referenced using **relative paths** like `images/banner.png`.

---

## 📄 newsletters.json

This file holds metadata for each issue so that the SOCHI website can automatically display an up-to-date archive.

Each entry follows this format:

```json
{
  "title": "Issue 01: Kickoff + UX Spotlight",
  "date": "2025-07-01",
  "url": "https://sochinewsletters.github.io/sochi-newsletters/newsletter-01/"
}
