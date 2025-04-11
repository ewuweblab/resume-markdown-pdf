# Resume in Markdown to PDF

> This resume was generated using HTML, CSS, and JS.

# Why?
* **Simplicity & Focus** - Create clean, professional documents using plain text syntax without fighting complex formatting tools.
* **Version Control & Portability** - Track changes with Git and easily convert to multiple formats (PDF, HTML, DOCX) from a single source file.
* **Maintenance & Consistency** - Make updates quickly without formatting issues and maintain a uniform style throughout your document.
* **Tech-Forward Approach** - Demonstrate technical proficiency, particularly valuable for roles in development, documentation, or content.


# How to Use?
* `*Use this tempate*` button to create a new repository with the same directory structure and files
* Install dependencies with `npm install`
* Dependencies:
    - [Markdown to PDF](https://www.npmjs.com/package/md-to-pdf)
* Edit the `resume.md` file to add your own information
* Run the command `npx md-to-pdf resume.md` to generate a PDF file from the markdown file
* Edit the `style.css` file to customize the look and feel of your resume
* Open the generated PDF file in your browser or PDF viewer

# What is frontmatter?
`resume.md` file includes *frontmatter* metadata aka "extra settings" which are used apply custom stylesheet and change default media type from `screen` to `print`.

```
---
stylesheet: style.css
page_media_type: print
---
```

# Citations
* npm Module: [Markdown to PDF](https://www.npmjs.com/package/md-to-pdf)
* Fonts: [Font](#)
* CodePen: [CodePen Pen](#)
