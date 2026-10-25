Day 2: HTML Foundations — Personal Introduction
<img width="773" height="639" alt="image" src="https://github.com/user-attachments/assets/12acfb26-1111-444d-81f1-923214569670" />
This example is a small personal introduction page that can grow into a resume-style page. Open index.html in a browser and read the source alongside the page.

Learning goals
By the end of this practice, you should be able to:

Explain the purpose of <!doctype html>, <html>, <head>, <title>, and <body>.
Use headings, paragraphs, line breaks, and emphasis to structure text.
Group related content in div elements and identify groups with id and class.
Recognize semantic containers such as header, main, section, and footer.
Inspect and fix a simple HTML mistake using browser DevTools.
Save, format, and submit a small project with Git.
Project tour
index.html is the working reference page. The name, course, education details, skills, and interests are fictional examples. Replace them with your own details when you make your version.
The document starts with the HTML doctype, language, character encoding, responsive viewport, and page title.
The page uses headings and paragraphs for readable content, strong for emphasis, and nested div elements to group related education facts.
Semantic elements show the role of each page area. The id values identify sections, while data-section demonstrates a custom data attribute.
style.css contains the page design, linked from index.html. Its numbered comments group the rules into page defaults, the introduction banner, content cards, and mobile layout. Try changing a color or spacing value and refresh the page to see the result.
Build in class
Work through these steps in order. Save and refresh the page after each change.

We know from this project :
1	Create index.html with a doctype, html, head, page title, body, and a few headings.	feat: add basic html structure
2	Add paragraphs, br, hr, strong, and em. Build About, Education, and Skills sections.	feat: add intro content
3	Group the sections with div elements. Add meaningful id and class values, plus one data-* attribute.	refactor: group content in divs
4	Copy the page to broken.html. Introduce one small HTML error, find it with DevTools, then fix it. Keep the corrected version.	fix: debug broken html
5	Format the file, tidy the folder, update this README for your own project, and push your repository.	docs: add readme
After practising with div, try using semantic elements such as header, main, section, and footer where their meaning fits. The working reference already shows one semantic version.


