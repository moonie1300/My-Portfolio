1. Created a multi-page site
Added working links for multi page functionality:
index.html
projects.html
contact.html

2. Built consistent navigation
Navigation exists on all pages
Uses relative paths (not absolute /index.html)
Links correctly between:
Home
Projects
Contact
Key learning:
Relative paths are safer for small static sites.

3. Created a Projects page with semantic structure
Used <section> to group each project
Used <h2> for project titles
Used <figure>, <img>, and <figcaption> for images
Used <a> links to project detail pages
Key learning:
<section> is for themed content, <article> is for standalone content. Both are valid depending on intent.

4. Fixed image paths
Moved images into /assets
Corrected image paths based on file location
Removed unnecessary ../ from root-level files
Key learning:
The browser resolves image paths relative to the HTML file, not the project root.

5. Fixed internal links
Corrected project links to match actual folder structure
Verified all links manually by clicking them
Key learning:
If a link doesn’t work, it’s almost always because the path is wrong, not because HTML is “being weird”