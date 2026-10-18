# Kelvin's Tech Blog

## Project description

Kelvin's Tech Blog is a beginner-friendly technology blog built with semantic HTML only. It shares learning resources about web development, data analysis, and AI automation. The project intentionally avoids CSS, JavaScript, Bootstrap, Tailwind, and other frameworks so the HTML structure and accessibility can be assessed directly.

## Pages included

- `index.html` — Home page and featured articles.
- `about.html` — Blog purpose, values, and areas of focus.
- `services.html` — Learning topics, resources, and a sample data table.
- `blog.html` — Article listing grouped by topic.
- `blog-post.html` — Example full-length tutorial with fragment links.
- `categories.html` — Topic categories and a glossary.
- `media.html` — Material on video and audion to visual listeners
- `contact.html` — Contact information and a labelled contact form.
- `pages/application.html` — Technology mentorship application form.

## HTML features used

- Valid HTML document structure, language, title, viewport and description metadata.
- Semantic landmarks: `header`, `nav`, `main`, `section`, `article`, `aside`, `address`, and `footer`.
- Logical heading levels, paragraphs, `strong`, `em`, ordered lists, unordered lists, and description lists.
- Internal, external, relative, email, and fragment links.
- Relative links from the child `pages` folder to parent-folder pages.
- Images with meaningful alternative text, plus `figure` and `figcaption`.
- A data table with `caption`, column headers, and row headers.
- Forms using labels, text, email, telephone, date, URL, radio, checkbox, select, textarea, fieldset, legend, required fields, and native constraints.
- Native submit buttons and keyboard-usable controls.

## What I learned

- How to organise a multi-page website with HTML alone.
- How semantic elements help explain a page's structure.
- How to connect pages using relative paths and fragment identifiers.
- How to label form controls and group related choices.
- How to use native browser validation and accessible table headers.
- Why HTML validation is important before submitting a project.

## Challenges encountered

- Keeping navigation consistent across all pages.
- Correctly writing relative paths from `pages/application.html` to files in the parent folder.
- Choosing useful alternative text for images.
- Grouping related form controls while ensuring every data-entry control has a label.
- Remembering that a form action does not create a working backend.

## Resources and media licences/attributions

- youtube.come, the Audios and Video
- MDN Web Docs, HTML documentation: https://developer.mozilla.org/en-US/docs/Web/HTML
- Nu HTML Checker: https://validator.w3.org/nu/
- `images/tech-workspace.svg` is an original simple illustration created for this educational project; no third-party image is embedded.
- No third-party audio or video is included. The `media/` folder is reserved for future licensed media.
- Review all external resources and any future media licences before public publication.

## Validation status

Run every HTML file through the Nu HTML Checker before final submission:

1. Open https://validator.w3.org/nu/
2. Choose the file upload option and validate each HTML file.
3. Fix reported errors and warnings that affect correctness or accessibility.
4. Save a screenshot of the successful validation result for each page.
